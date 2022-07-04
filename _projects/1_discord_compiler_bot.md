---
name: Discord Compiler Bot
tools: [Rust, Serenity, Multithreading, Posix]
image: /assets/discord.png
description: Revant bot can retrieve code from discord messages containing a code block and bot commands which is then executed and the output is returned.
---

![preview](/assets/discord.png)

# Discord Compiler Bot

- Revant bot can retrieve code from discord messages containing a code block and bot commands.
- The retrieved code is compiled and executed and its result is posted back on the discord channel.
- The bot is multithreaded and makes use of 8 long-running threads which are associated with workers.
- Each worker makes POSIX calls to restrict CPU and memory usage for its subprocess.


<p class="text-center">
{% include elements/button.html link="https://github.com/aniket1020/Revant-bot" text="Learn More" %}
</p>
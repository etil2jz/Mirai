<img src="logo.webp" alt="Mirai Face" align="right">
<div align="center">
  <h1>Mirai</h1>
  <h3>A powerful Minecraft Server Software coming from the future</h3>
  <h4>Mirai is ❗under heavy development❗ and contributions are welcome!</h4>
  <h5><b>This project is experimental, its usage in production environment is discouraged if you are not ready to face possible bugs.</b></h5>
  
  [![Build status](https://img.shields.io/github/actions/workflow/status/Dreeam-qwq/Mirai/build.yml?branch=ver%2F1.19.2&style=for-the-badge)](https://github.com/Dreeam-qwq/Mirai/releases/tag/1.19.2)
  [![Discord](https://img.shields.io/discord/928402257605701683?color=5865F2&label=discord&style=for-the-badge)](https://discord.gg/DdH6Yfu9gM)
</div>

## Features

- **Fork of [Pufferfish](https://github.com/pufferfish-gg/Pufferfish)** for the best performance.
- **Contains [Lithium](https://github.com/CaffeineMC/lithium-fabric) patches** which respect Vanilla parity.
- **Efficient redstone** relying on [Alternate Current](https://github.com/SpaceWalkerRS/alternate-current), up to 4 times faster than Eigencraft's algorithm.
- **(WIP) Implements [C2ME](https://github.com/RelativityMC/C2ME-fabric)** to improve chunk generation speed, I/O and loading.
- **Async Pathfinding and Multithreaded Entity Tracker** from [Petal](https://github.com/Bloom-host/Petal) which drastically reduce entity load.
- **Configurable chat report system** to disallow players from reporting others' messages to Mojang.
- **Reduced bandwidth consumption and CPU usage** from avoiding sending useless packets in certain situations.
- **Pre-tweaked** configuration files to reach optimal performance with minimal impact on normal behaviors.
- **Login location** hiding feature, which adds another security layer in the logs for admins.
- **Bugfixes** for several Minecraft issues.
- **Faster process** for Vanilla methods.
- **Plugin compatibility** with Spigot & Paper plugins.

## Downloads
The latest successful build can be downloaded here:
[mirai-paperclip-1.19.2-R0.1-SNAPSHOT-reobf.jar](https://github.com/Dreeam-qwq/Mirai/releases/tag/1.19.2)

**Please note Java >= 17 is required.**

You can also clone this repository and build it yourself.
If you are interested in making a fork, check out this template [there](https://github.com/PaperMC/paperweight-examples)!

## Building
In order to distribute and use this server software, you need a paperclip file:

```bash
./gradlew applyPatches && ./gradlew createReobfPaperclipJar
```

## License
Patches are licensed under GPL-3.0.  
All other files are licensed under MIT.

## bStats
[![](https://bstats.org/signatures/server-implementation/mirai.svg)](https://bstats.org/plugin/server-implementation/Mirai/14774)

Made with <span style="color: #e25555;">&#9829;</span> on Earth.

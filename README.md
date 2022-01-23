<img src="logo.webp" alt="Mirai Face" align="right">
<div align="center">
  <h1>Mirai</h1>
  <h3>A powerful Minecraft Server Software coming from the future</h3>
  <h4>Mirai is ❗under heavy development❗ and contributions are welcome!</h4>
  <h5><b>This project is experimental, its usage in production environment is discouraged if you are not ready to face possible bugs.</b></h5>
  
  ![Build status](https://img.shields.io/github/workflow/status/etil2jz/Mirai/Build/ver/1.18?style=for-the-badge)
  [![Discord](https://img.shields.io/discord/928402257605701683?color=5865F2&label=discord&style=for-the-badge)](https://discord.gg/DdH6Yfu9gM)
</div>

## Features

- **Fork of [Purpur](https://github.com/PurpurMC/Purpur)** with [Pufferfish](https://github.com/pufferfish-gg/Pufferfish) patches for the best performance.
- **Contains [Lithium](https://github.com/CaffeineMC/lithium-fabric) patches** which respect Vanilla parity.
- **Integrates [Hydrogen](https://github.com/CaffeineMC/hydrogen-fabric)** which reduces memory consumption.
- **Efficient redstone** relying on [Alternate Current](https://github.com/SpaceWalkerRS/alternate-current), up to 4 times faster than Paper's algorithm.
- **(WIP) Implements [C2ME](https://github.com/RelativityMC/C2ME-fabric)** to improve chunk generation speed, I/O and loading.
- **Reduced bandwidth consumption and CPU usage** from avoiding sending useless packets in certain situations.
- **New NBT cache** which reduces a lot of I/O operations from the main thread while preserving correct data.
- **Pre-tweaked** configuration files to reach optimal performance with minimal impact on normal behaviors.
- **Login location** hiding feature, which adds another security layer in the logs for admins.
- **Toggleable metrics**, no one can collect data, not even us.
- **Bugfixes** for several Minecraft issues.
- **Faster process** for Vanilla methods.
- **Plugin compatibility** with Spigot & Paper plugins.

## Downloads
The latest JAR file can be downloaded here:
[Mirai-Purpur-1.18.1-R0.1-SNAPSHOT.jar](https://github.com/etil2jz/Mirai/raw/purpur-build/1.18.1/Mirai-Purpur-1.18.1-R0.1-SNAPSHOT.jar)

**Please note Java 17 is required.**

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

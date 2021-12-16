<img src="logo.webp" alt="Mirai Face" align="right">
<div align="center">
  <h1>Mirai</h1>
  <h3>A powerful Minecraft Server Software coming from the future</h3>
  <h4>Mirai is ❗under heavy development❗ and contributions are welcome!</h4>
  <h5><b>This project is experimental, its usage in production environment is discouraged if you are not ready to face possible bugs.</b></h5>

</div>

## Features

- **Based on [Pufferfish](https://github.com/pufferfish-gg/Pufferfish)**
- **Reduced bandwidth consumption** from avoiding sending useless packets in certain situations.
- **New NBT cache** which reduces a lot of I/O operations from the main thread while preserving correct data.
- **Pre-tweaked** configuration files to reach optimal performance with minimal impact on normal behaviors.
- **Login location** hiding feature, which adds another security layer in the logs.
- **Removed metrics**, no one can collect data, not even us.
- **Bugfixes** for several Minecraft issues.
- **Safer methods** for Vanilla calls.
- **Plugin compatibility** with Spigot & Paper plugins.

## Downloads
The latest JAR file can be downloaded here:
[Mirai-1.18.1-R0.1-SNAPSHOT.jar](https://github.com/etil2jz/Mirai/releases/download/mc1.18.1/Mirai-1.18.1-R0.1-SNAPSHOT.jar)

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

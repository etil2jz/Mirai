<img src="logo.webp" alt="Mirai Face" align="right">
<div align="center">
  <h1>Mirai</h1>
  <h3>A powerful Minecraft Server Software coming from the future</h3>
  <h4>Mirai is ❗under heavy development❗ and contributions are welcome!</h4>

[![Actions](https://img.shields.io/github/workflow/status/etil2jz/Mirai/Build)](https://github.com/etil2jz/Mirai/actions)
</div>

## Features

- **30% faster hoppers** over Paper.
- **Improved entity performance** from a reduction in ticking entity behavior based on how far away they are from the player.
- **Reduced GC times & frequency** from removing useless allocations, which also improves CPU performance.
- **Fast raytracing** which improves performance of any entity which utilizes line of sight, mainly Villagers.
- **Built-in profiler** which has 0 performance hit and easy to read metrics for both server owners and developers.
- Faster crafting, reduction in uselessly loaded chunks, faster entity ticking, faster block ticking, faster bat spawning, and more!
- Plugin compatibility with Spigot & Paper plugins.
- All metrics, bStats and the vanilla snooper included, are removed.

## Downloads
The latest JAR file can be downloaded from the [release/1.17 branch](https://github.com/etil2jz/Mirai/raw/release/1.17/Mirai-1.17.1-R0.1-SNAPSHOT.jar). You can also clone this repository and build it yourself.

If you are interested in making a fork, check out this template [here](https://github.com/TECHNOVE/MyAirplaneFork)!

## Building

If you want to avoid the patching system:

```bash
./gradlew clean applyPatches && ./gradlew build
```

Otherwise, in order to distribute, you need a paperclip file:

```bash
./gradlew clean applyPatches && ./gradlew paperclipJar
```

## License
Patches are licensed under GPL-3.0.  
All other files are licensed under MIT.

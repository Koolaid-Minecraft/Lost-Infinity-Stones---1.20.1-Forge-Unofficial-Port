<div align="center">

# 💎 Lost Infinity Stones — 1.20.1 Forge (Unofficial Port)

[![Minecraft Version](https://img.shields.io/badge/Minecraft-1.20.1-brightgreen?style=for-the-badge&logo=minecraft)](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.20.1.html)
[![Mod Loader](https://img.shields.io/badge/Loader-Forge%2047.2+-orange?style=for-the-badge)](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.20.1.html)
[![Java Version](https://img.shields.io/badge/Java-17-blue?style=for-the-badge&logo=openjdk)](https://learn.microsoft.com/en-us/java/openjdk/download#openjdk-17)
[![Release](https://img.shields.io/github/v/release/Koolaid-Minecraft/Lost-Infinity-Stones---1.20.1-Forge-Unofficial-Port?style=for-the-badge&color=purple)](https://github.com/Koolaid-Minecraft/Lost-Infinity-Stones---1.20.1-Forge-Unofficial-Port/releases)

**An unofficial community port of the iconic *Lost Infinity Stones* mod (originally created for 1.12.2 InsaneCraft) updated to Minecraft 1.20.1 Forge.**

[📥 Download Latest Release](../../releases/latest) • [🐛 Report a Bug](../../issues) • [🛠️ Build from Source](#--building-from-source)

</div>

---

## ✨ Features & Port Status

- **Dimensions & Biomes:** Explore the Starforge, Murk, Sea, Fungal, Labyrinth, and Celestial realms.
- **Weapons, Tools & Armor:** Wield the Celestial Miner's Pickaxe, Infinity Trident, Ionic Chakram, Avenger, and full custom armor sets.
- **Bosses & Mobs:** Battle Cthulhu, Vycellia, Ozor, Galactic Terrors, and Deviant creatures.
- **1.20.1 Fixes Included:**
  - Updated tool tiers and block tags (`#minecraft:mineable/pickaxe`) for proper 1.20.1 ore harvesting.
  - Patched missing sound and renderer imports from earlier dev builds.

---

## 📦 Installation (For Players)

1. Install **Minecraft 1.20.1** with **Minecraft Forge** (recommended `47.2.0` or newer).
2. Go to the **[Releases](../../releases)** tab on the right side of this repository.
3. Download the latest `lostinfinity-1.16.0-mc1.20.1-dev.10.jar` file under **Assets**.
4. Drop the `.jar` file into your `.minecraft/mods` folder (or your launcher instance's `mods` folder).

> **💡 Tip for Large Modpacks (200+ Mods):** If you run this mod alongside high-resolution superhero mods (such as *FSang18's Heroes*), set `mipmapLevels:0` in your `options.txt` to prevent OpenGL texture atlas overflow (`StitcherException`).

---

## 🛠️ Building from Source (For Developers)

This project requires **JDK 17** to compile with Gradle 8.8.

1. Clone the repository:
   ```bash
   git clone [https://github.com/Koolaid-Minecraft/Lost-Infinity-Stones---1.20.1-Forge-Unofficial-Port.git](https://github.com/Koolaid-Minecraft/Lost-Infinity-Stones---1.20.1-Forge-Unofficial-Port.git)
   cd Lost-Infinity-Stones---1.20.1-Forge-Unofficial-Port
   ```
2. Build the mod using the Gradle wrapper:
   * **Windows (PowerShell):**
     ```powershell
     .\gradlew.bat build
     ```
   * **Linux / macOS:**
     ```bash
     ./gradlew build
     ```
3. The compiled `.jar` will be generated in `build/libs/`.

---

## 📜 Credits & Disclaimer

* **Original Mod & Assets:** Created for the 1.12.2 *InsaneCraft* modpack by Xol / Spark Universe. All original models, textures, sounds, and concepts belong to their respective creators.
* **1.20.1 Forge Port & Maintenance:** Community contributors & [Koolaid-Minecraft](https://github.com/Koolaid-Minecraft).
* *This is an unofficial fan port and is not affiliated with Spark Universe or Mojang Studios.*

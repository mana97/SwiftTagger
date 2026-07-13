# SwiftTagger

**Display every player's official SwiftPvP tier directly in-game.**

SwiftTagger retrieves official tier data from the SwiftPvP Tierlist and displays player rankings above nametags and in the player list, allowing you to instantly identify the skill level of other players.

---

## Features

* Displays official player tiers (HT1–LT5) above player nametags.
* Integrates tier information into the in-game tab list.
* Includes custom icons for all supported SwiftPvP gamemodes:

  * Sword
  * Axe
  * Mace
  * Pot
  * NethPot
  * UHC
  * SMP
  * DiaSMP
  * Crystal
* In-game player lookup with detailed profile information, including:

  * All available tiers
  * Rating points
  * Global ranking
  * Region
  * Player title
* Fully configurable display options, including:

  * Selected gamemode
  * Nametag display
  * Tab list integration
  * Highest-tier fallback
  * Gamemode icons
* Live synchronization with the official SwiftPvP testing database.

---

## How It Works

Player tiers are obtained through official tier tests conducted on the SwiftPvP network. Test results are stored in the official database and made available through the public API. SwiftTagger retrieves this information in real time and renders it directly inside Minecraft.

Leaderboard:
https://tiers.swiftpvp.net

Players interested in obtaining an official tier can apply through the SwiftPvP Discord server.

---

## Installation

1. Install Fabric Loader for Minecraft **1.21.11**.
2. Place the following mods into your `mods` directory:

   * SwiftTagger
   * ukulib (required)
   * Fabric API
3. Launch Minecraft and join **swiftpvp.net**.

Tier information will automatically appear for all officially ranked players.

> SwiftTagger should not be installed together with the original TierTagger, as both mods share internal components and are not compatible with each other.

Configuration is available through **Mod Menu → SwiftTagger → Configure**.

---

## Credits

SwiftTagger is based on **TierTagger**, originally created by **netiyiy** and currently maintained by the **mctiers-dev** team. This project has been adapted for the SwiftPvP ecosystem with permission from the original authors.

* License: **MPL-2.0**
* Source Code: https://github.com/mana97/SwiftTagger

All SwiftPvP branding, gamemode icons, and assets are original and belong to the SwiftPvP project.

---

**SwiftPvP**

Website: https://tiers.swiftpvp.net

Discord: https://discord.gg/NcYfPbnyCU

Server IP: `swiftpvp.net`

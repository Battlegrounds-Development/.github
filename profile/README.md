# ⚔️ Battlegrounds Development
The official open-source ecosystem for the **Battlegrounds** Minecraft server. We build modular, high-performance Spigot plugins centered around extraction-style gameplay.

---

### 🏛️ The Core Framework
* **[core-api](https://github.com/Battlegrounds-Development/core-api)** (Public)  
    The primary integration point for the Battlegrounds ecosystem. Provides access to global services, player data, and cross-module communication. **Developers should depend on this module.**
* **core** 
    The internal implementation and engine of the server.

### 🎮 Gameplay & Mechanics
* **[adventure](https://github.com/Battlegrounds-Development/adventure)** The extraction engine: handles map rotations, world bosses, loot tables, and match flow.
* **[bunker](https://github.com/Battlegrounds-Development/bunker)** Private player instances. Supports upgrades, purchasing systems, and persistence.
* **[armor](https://github.com/Battlegrounds-Development/armor)** Custom attribute-based armor sets designed for tactical PvP.

### 🎒 Systems & Economy
* **[items](https://github.com/Battlegrounds-Development/items)** Framework for custom tactical items including Molotovs, Grenades, and Tear Gas.
* **[reputation](https://github.com/Battlegrounds-Development/reputation)** Dynamic dealer system. Tracks player transactions and scales permissions based on NPC affinity.
* **[perks](https://github.com/Battlegrounds-Development/perks)** Player progression through rarities and specialized character abilities.

---

### 🛠️ Developer Information
If you are looking to build a module for Battlegrounds, please refer to the **[core-api](https://github.com/Battlegrounds-Development/core-api)** documentation. All public repositories are maintained as mirrors of our internal development branches.

[Discord] | [Server IP: play.bgsmc.us]

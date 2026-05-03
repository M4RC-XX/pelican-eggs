# 🥚 Pelican Eggs Collection

Welcome to my repository for custom game server eggs designed for the [**Pelican Panel**](https://pelican.dev)! 🚀

## ❓ What is Pelican?
**Pelican** is a powerful, free, and open-source game server management panel. Built to run game servers seamlessly in Docker containers, it provides a clean and modern web interface for administrators and users. 

In Pelican, an **"Egg"** is essentially a configuration file (in JSON format) that tells the panel exactly how to install, configure, and run a specific game or server software.

## 📦 The Eggs

This repository currently focuses on **Minecraft: Java Edition** and includes the following specific Eggs:

### 🧶 1. Minecraft Java: Fabric
* **Location:** `minecraft/java/fabric/`
* **Description:** Fabric is a modular, lightweight, and incredibly fast mod loader for Minecraft. This egg is perfect if you want to run a highly optimized modded server using the Fabric API and its modern ecosystem.
* **Import Link:** https://raw.githubusercontent.com/M4RC-XX/pelican-eggs/refs/heads/main/minecraft/java/fabric/egg-minecraft-java-fabric.json

### 🛠️ 2. Minecraft Java: NeoForge
* **Location:** `minecraft/java/neoforge/`
* **Description:** NeoForge is a modern, community-driven, open-source mod loader for Minecraft. Use this egg to easily deploy a robust NeoForge server for heavy modpacks and classic modding experiences.
* **Import Link:** https://raw.githubusercontent.com/M4RC-XX/pelican-eggs/refs/heads/main/minecraft/java/neoforge/egg-minecraft-java-neo-forge.json

### 💡 X. Minecraft Java: Custom Server
* **Location:** `minecraft/java/custom/`
* **Description:** This egg allows for more flexible setups, supporting loaders like PaperMC, Folia, Purpur, and vanilla Forge!
* **Import Link:** https://raw.githubusercontent.com/M4RC-XX/pelican-eggs/refs/heads/main/minecraft/java/custom/egg-minecraft-java-custom.json

## 🚀 How to Install

1. Download the `.json` file of the Egg you want to use (e.g., `egg-minecraft-java-fabric.json`), **OR** copy the provided Import Link.
2. Log into your Pelican Panel.
3. Navigate to **Eggs** in the sidebar.
4. Click on the **Import Egg** button.
5. Upload the downloaded `.json` file, or paste the Import Link.
6. Create a new server, select your newly imported Egg, and start playing! 🎉

---
*If you encounter any issues or want to request a new egg, feel free to open an issue!* 🐛🥚
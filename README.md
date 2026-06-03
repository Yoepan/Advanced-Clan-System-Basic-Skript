# Advanced-Clan-System-Basic-Skript  

[gambar]  

The Basic Clan System is a lightweight, lag-free, and highly interactive social Team/Guild plugin for your survival server. Featuring a 100% GUI-driven experience, Shared Clan Vaults, Tag Color Customization, and a robust Base system, it has everything your players need to team up and conquer the world together!  


**⭐ WANT MORE?**  
*This is the Free "Social-Only" version. If you want Clan Leveling (1-10), Passive Perks, Weekly Events, Custom Global Buffs, and a Personal Point Shop, check out the **[Advanced Clan System Premium]**!*  


### 🎨 Custom Clan Tag Colors   
Clans don't just exist; they need an identity! In the Clan Settings, Leaders and Co-Leaders can customize their Clan Tag's color via an interactive GUI.   
5 Built-in Colors: Gray (Default), Green, Blue, Yellow, and Red.   
Tags automatically prefix the player's name in chat seamlessly—no complex chat plugin configuration required!  

[gambar]  

### 📦 The Clan Vault (Shared Storage)   
A powerful Shared Ender Chest for every clan!  
54-slot virtual inventory accessible to all members of the same clan.  
Perfect for pooling resources, sharing extra gear, or safely storing war loot.  
Admins have full oversight! Use `/clanadmin vault <clan>` to secretly view a clan's vault, or `/clanadmin setvault <clan>` to edit/confiscate items.    

[gambar]  

### 🏠 Clan Home (Base) System  
/clan sethome : Leaders and Co-Leaders can set a custom teleportation point for their clan base.  
/clan home : Members can teleport to their Clan Base.  
**Integrated anti-abuse mechanics:** Includes a 5-second "do not move" warmup delay and a 1-minute cooldown to  
prevent teleport spamming during PvP or combat.  
**Smart notification:** The whole clan is instantly notified via broadcast when the Leader updates the base location.  

[gambar]  

### ⚙️ 100% Interactive GUI Management  
Say goodbye to remembering complex chat commands!  
**Players:** Can change Clan Tags, Descriptions, Rules, and view member lists directly via a beautiful, symmetrical interactive GUI.  
**Moderation:** Leaders can Manage, Promote, Demote, or Kick members using a dedicated "Manage Player" GUI.  
  
### ✨ Quality of Life & Immersion (The Small Details)  
**⚔️ Togglable Friendly Fire (PvP):** Leaders can turn Clan PvP ON or OFF in the Settings GUI. If OFF, members cannot accidentally damage each other in combat!  
**💬 Clan Chat Toggle:** Players can type `/cc <msg>` for quick messages, or just type `/cc` to toggle Clan Chat Mode ON, routing all their normal chat directly to their clanmates.  
**📢 Clan Broadcast:** Leaders can use `/clan broadcast` to send an urgent Title/Subtitle message across the screen of every online clan member.  
**🚪 Join/Leave Alerts:** Members are automatically notified in chat when a clanmate logs in or out.  

### 🏛️ Clan Ranks & Permissions  
1.  **Leader:** Ultimate control. Disband, Set Clan Home, Transfer Ownership, Edit Settings, Promote, and Kick.  
2.  **Co-Leader:** Edit Settings, Promote to Elder, Kick Members, and send Broadcasts.  
3.  **Elder:** Invite new players and Kick Members.  
4.  **Member:** Access the Clan Vault, teleport to Clan Home, and use Clan Chat.  

### 📜 Command List  

**🔹 Player Commands**  
`/clan` - Opens the Main Interactive GUI.  
`/clan create <name>` - Start your clan.  
`/clan info` - View descriptions, rules, friendly fire status, and creation date.  
`/clan members` - Manage ranks and view the members list.  
 `/clan setting` - Change Tags, Colors, Rules, and Friendly Fire.  
`/clan broadcast <msg>` - Send a massive Title/Subtitle alert to all members.  
`/cc [msg]` - Toggle or send a Private Clan Chat.  
 `/clan invite/accept/deny/leave/kick/promote/demote/transfer` - Social Management.  

**🔸 Admin Commands (Permission: clan.admin)**  
`/clanadmin spy <clan>` - Secretly view a clan's details and the ranks of every member inside it!  
`/clanadmin vault <clan>` - Secretly view a clan's shared Vault (Read-only).  
`/clanadmin setvault <clan>` - Open and forcefully edit/confiscate items from a clan's Vault.  
`/clanadmin forcejoin <player> <clan>` - Force a player into a specific clan without needing an invite.  
`/clanadmin forcekick <player>` - Forcibly remove a disruptive player from their clan (bypassing leader permissions).  
`/clanadmin disband <clan>` - Instantly and completely wipe a clan from the server, deleting their Vault and resetting data.  
 
### 💻 Requirements & Compatibility  
Built with modern Minecraft in mind! Zero legacy IDs used.  
**Minecraft Versions:** 1.19.x, 1.20.x, 1.21.x - 1.26.x  
**Dependencies:** Skript Latest Version and SkBee.  
[**Skript**](https://github.com/SkriptLang/Skript/releases)  
[**SkBee**](https://github.com/ShaneBeee/SkBee/releases)  
**Performance:** 100% lag-free. Uses low-impact metadata tracking.  


*(Loved this Free version? Upgrade your server with 10-Level Perks, Weekly Economy Events, Global Buffs, and a Personal Progression Shop by purchasing the **Ultimate Clan System Premium** today!)*

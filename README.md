# Torio-Client
A lightweight External Ghost Client for **Minecraft Bedrock Edition**  
**Supported Versions: v26.20 – v26.45**

[![GitHub Downloads (total)](https://img.shields.io/github/downloads/Uncle-Awrt/Torio-Client/total?color=pink)](https://github.com/Uncle-Awrt/Torio-Client/releases/latest)
[![Discord](https://img.shields.io/discord/1447408228798304359?logo=discord&label=Discord&color=5865f2)](https://discord.gg/xq8sWQhuXG)
[![downloads][16]][17]

[16]: https://custom-icon-badges.demolab.com/badge/-Download-F25278?logo=download&logoColor=white
[17]: https://github.com/Uncle-Awrt/Torio-Client/releases/download/v2.0.0-beta.5/TorioClient.exe

Torio-Client is designed to enhance gameplay with visual tools, movement utilities, combat features, and customizable modules.  
All features are fully toggleable and optimized for smooth performance.

> ⚠️ As of v1.2.0-beta.1, Torio-Client has been migrated from **Python 3.11** to **WPF (C#)** for significantly improved performance and launch speed. Development will now focus exclusively on v26+ updates.

## 🔗 Source Code (C# / WPF)
https://github.com/kukentyan/torio-master-wpf

> Note: The source code is not yet available as a stable version has not been released.

## 📢 Discord
For announcements, support, and feedback, join our official Discord server:  
**If you are having an issue, DO NOT open an issue on this repo.**  
Instead, please join our Discord server for support:

**https://discord.gg/xq8sWQhuXG**

---

## Features (C# / WPF Version)

> **Total Modules: 38** (Visual: 10 | Combat: 10 | Movement: 7 | Utility & Settings: 11)

### Visual Modules

![Visual Modules Screenshot](./images/wpf/visual_modulesv2.png)

#### Fullbright
Keeps the world fully illuminated at all times.

![FullBright Card](./images/cards/v2/fullbright.png)

#### Zoom
Adjustable zoom for clearer long-distance vision.

![Zoom Card](./images/cards/v2/zoom.png)

#### Coordinates
Displays your current XYZ coordinates on screen.

![Coordinates Card](./images/cards/v2/coordinates.png)

#### ESP
Draws a 2D bounding box outline around nearby entities, making them visible through walls.

![ESP Card](./images/cards/v2/esp.png)

#### TrueSight
Makes all invisible entities fully visible (e.g. invisible players, mobs, or effects).

![TrueSight Card](./images/cards/v2/truesight.png)

#### Time Changer
Freely change the in-game time client-side for better visibility or aesthetics.

![Time Changer Card](./images/cards/v2/timechanger.png)

#### Duck Overlay
Displays a cute animated duck on your screen to help you stay calm during gameplay.

![Duck Overlay Card](./images/cards/v2/duckoverlay.png)

#### Notifications
Displays in-game notification toasts for client events and toggles.

![Notifications Card](./images/cards/v2/notifications.png)

#### Custom Watermark
Displays a customizable text watermark on screen with configurable font, size, and text.

![Custom Watermark Card](./images/cards/v2/customwatermark.png)

#### Array List
Displays a list of currently active modules on screen as an in-game overlay.

![Array List Card](./images/cards/v2/arraylist.png)

---

### Combat Modules

![Combat Modules Screenshot](./images/wpf/combat_modulesv2.png)

#### Reach (Randomizer Support)
Extends melee attack distance.

![Reach Card](./images/cards/v2/reach.png)

#### AutoClicker (Left & Right) (Randomizer Support)
Automates left and right clicks. Menu Check and Block Break Check can be toggled individually via checkboxes.

![AutoClicker Card](./images/cards/v2/autoclicker.png)

#### Double Clicker
Simulates a double click on each real mouse click, effectively doubling your CPS.

![Double Clicker Card](./images/cards/v2/doubleclicker.png)

#### Hitbox
Expands entity hitboxes for easier targeting.

![Hitbox Card](./images/cards/v2/hitbox.png)

#### TriggerBot (CPS Randomizer Support)
Automatically attacks when your crosshair is over a target. Supports **First Hit**, **Auto Click**, and the **HitSelect** mode (activates when you are hit by an opponent while already aiming at them).

![TriggerBot Card](./images/cards/v2/triggerbot.png)

#### Sticky Aim (Randomizer Support)
*(Previously Micro Aim)* Automatically fine-tunes your sensitivity when manually aiming at an enemy, helping your aim lock on smoothly.

![Sticky Aim Card](./images/cards/v2/sticky_aim.png)

#### Aim Assist
Guides your aim toward nearby **Players**. Non-player entities are completely excluded to prevent unwanted tracking. Yaw and Pitch calculations use dynamic values, ensuring smooth, highly accurate, non-jittery movements.

![Aim Assist Card](./images/cards/v2/aimassist.png)

#### BackTrack
Delays incoming player position packets using a smooth continuous delay queue, allowing you to hit enemies from where they were moments ago. Supports **Flow** mode (toggle) and **Hold** mode (hold keybind to activate).

![BackTrack Card](./images/cards/v2/backtrack.png)

#### Auto Throw *(Macro)*
Automated pearl, snowball, and item throw macro.

![Auto Throw Card](./images/cards/v2/autothrow.png)

#### Auto Bow *(Macro)*
Automated bow charge macro.

![Auto Bow Card](./images/cards/v2/autobow.png)

---

### Movement Modules

![Movement Modules Screenshot](./images/wpf/movement_modulesv2.png)

#### Toggle Sprint
Sprint without holding the sprint key.

![Toggle Sprint Card](./images/cards/v2/toggle_sprint.png)

#### Air Acceleration (Randomizer Support)
Allows you to modify acceleration while jumping.

![Air Acceleration Card](./images/cards/v2/air_acceleration.png)

#### Timer (Randomizer Support)
Allows you to modify the game's tick speed.

![Timer Card](./images/cards/v2/timer.png)

#### Auto JumpReset (Randomizer Support)
Automates jump reset timing during combat.

![Auto JumpReset Card](./images/cards/v2/jump_reset.png)

#### Lag Switch
Hold the configured keybind to freeze outgoing packets and simulate lag.

![Lag Switch Card](./images/cards/v2/lagswitch.png)

#### Velocity
Reduces or prevents knockback from attacks with customizable Horizontal (X/Z) and Vertical (Y) multipliers.

![Velocity Card](./images/cards/v2/velocity.png)

#### NoSlowdown
Disables movement slowdown effects when consuming items, using weapons, or traversing slowing terrain.

![NoSlowdown Card](./images/cards/v2/noslowdown.png)

---

### Utility & Settings

![Utility Screenshot](./images/wpf/utility_modulesv2.png)

#### GUI Settings
Customize the look of Torio-Client with full RGB accent color control, Light Mode / Dark Mode toggles, and reset capabilities.

![GUI Settings Card](./images/cards/v2/gui_settings.png)

#### Ingame Overlay & External Window Mode
Seamlessly switch between rendering the GUI as an in-game overlay directly over Minecraft, or as a standalone **External Window** (ideal for dual monitors or side-by-side management).

![Ingame Overlay Card](./images/cards/v2/ingame_overlay.png)

> **External Window Support:**  
> You can still use Torio-Client in classic External Window mode without overlaying the game screen.

![External Window](./images/wpf/externalwindow.png)

#### FakeLag
*(Previously Reverse BackTrack)* Delays your own movement packets sent to the server, making your character appear to stutter or lag to other players. Supports **Flow** mode (toggle) and **Hold** mode (hold keybind to activate) with optional **Hardstop on hit**.

![FakeLag Card](./images/cards/v2/fakelag.png)

#### Blink
Temporarily queues outgoing network packets while holding a keybind (Reverse Hold), instantly teleporting your position to the server upon release.

![Blink Card](./images/cards/v2/blink.png)

#### Fast Item
Speeds up item use timers, allowing faster item usage.

![Fast Item Card](./images/cards/v2/fast_item.png)

#### Streamprotect
Hides sensitive or personal information while streaming.

![Streamprotect Card](./images/cards/v2/stream_protect.png)

#### System Tray
Minimize Torio-Client to the system tray and reopen it at any time.

![System Tray Card](./images/cards/v2/system_tray.png)

#### Discord Presence
Displays your current menu, server, Minecraft version, and client status on Discord.

![Discord Presence Card](./images/cards/v2/discord_presence.png)

#### Toggle Sounds
Plays a sound effect when toggling modules on or off. Can be easily enabled or disabled.

![Toggle Sounds Card](./images/cards/v2/toggle_sounds.png)

#### Device ID Spoofer
Spoofs your device ID to help protect your identity. Can be configured to spoof on join, on startup, or both.

![Device ID Spoofer Card](./images/cards/v2/device_id_spoofer.png)

#### Auto 360 *(Macro)*
Automated 360° spin macro. Supports Right, Left, and Alternate spin directions with configurable sensitivity and keybind.

![Auto 360 Card](./images/cards/v2/auto360.png)

---

### Animations
- **Expandable Module Cards** – Each module can be expanded to reveal its settings and options with a smooth animation.
- **Toggle Switches** – Modules are enabled and disabled with a smooth toggle switch animation.

---

## Customization

### Keybind Customization
Most modules support customizable keybinds, allowing you to assign controls that fit your playstyle. *(The GUI visibility toggle keybind can be found inside GUI Settings).*

### Config System
Save, load, and manage your personalized configurations. Useful for switching between setups quickly or backing up your settings.

---

## Connect, Loading Screen & Built-in Version Switcher

### Connect Screen
When launching Torio-Client, the connection screen automatically detects your running Minecraft Bedrock process and checks version compatibility in real time.

![Connect Screen](./images/wpf/connectscreen.png)

### Loading Screen
Once connected, the high-speed loading screen scans game memory and hooks into Minecraft Bedrock smoothly in seconds, ensuring seamless startup without freezing or delays.

![Loading Screen](./images/wpf/loadingscreen.png)

### Built-in Version Switcher
Torio-Client includes a built-in **Version Switcher**, allowing you to switch and install supported Minecraft Bedrock versions directly within the client without needing any third-party launchers.

![Version Switcher](./images/wpf/versionswitcher.png)

---

---

# 📦 Archive — Python Version (up to v1.1.0-beta.3)

> The following section is preserved for reference. The Python-based version of Torio-Client is no longer maintained.  
> Last Python release: [v1.1.0-beta.3](https://github.com/Uncle-Awrt/Torio-Client/releases/tag/v1.1.0-beta.3)

## 🔗 Source Code (Python)
https://github.com/kukentyan/torio-master

## Features (Python Version)

### Player Modules
- **Fast Item** – Speeds up item use timers, allowing faster item usage.

![Visual Modules Screenshot](./images/player_modules3.png)

### Visual Modules
- **FullBright** – Keeps the world fully illuminated at all times.
- **Zoom** – Adjustable zoom for clearer long-distance vision.
- **Coordinates** – Displays your current XYZ coordinates on screen.
- **No Hurt Cam** – Disables the hurt camera shake effect when taking damage. (1.21.130~1.21.132 Only)
- **TrueSight** – Makes all invisible entities fully visible.
- **TimeChanger** – Allows you to freely change the in-game time client-side.

![Visual Modules Screenshot](./images/visual_modules7.png)

### Combat Modules
- **Reach** – Extends melee attack distance.
- **AutoClicker (Left & Right)** – Automates left and right clicks for combat and building.
- **Hitbox** – Expands entity hitboxes for easier targeting.
- **Micro Aim** – Automatically fine-tunes your sensitivity when manually aiming at an enemy.
- **Trigger Bot** – Automatically attacks when your crosshair is over a target. Supports two modes: First Hit and Auto Click.
- **Aim Assist** – Helps guide your aim toward newly targets.

![Combat Modules Screenshot](./images/combat_modules5.png)

### Movement Modules
- **ToggleSprint** – Sprint without holding the sprint key.
- **Speed** – Increases player movement speed.
- **JumpReset** *(Test Module)* – Automates jump reset timing during combat. (Supports 1.21.132 and v26)
- **AntiKnockback** – Reduces or prevents knockback from attacks.

![Movement Modules Screenshot](./images/movement_modules5.png)

### Misc Modules
- **Stream Protect** – Hides sensitive or personal information while streaming.
- **SystemTray** – Open the Torio-Client window from the system tray or exit the client.

![Misc Modules Screenshot](./images/misc_modules6.png)

---

# ⚠️ Disclaimer
Use of this software is at your **own risk**.  
By using Torio-Client, you agree that all actions are taken at your **own risk**.  
The developer is **not responsible** for any issues, penalties, or data loss caused by using this software.  
Please use responsibly and understand the risks before running the program.

---

## 📄 License
This project is licensed under the [Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://github.com/Uncle-Awrt/Torio-Client/blob/main/LICENSE).  
You may share and adapt this project for non-commercial purposes, as long as appropriate credit is given.

<div align="center">

# OldSkool WoT Mods

**Quality of life, battle info and hangar mods for World of Tanks**

![World of Tanks](https://img.shields.io/badge/World%20of%20Tanks-2.4.1.1-c8102e?style=for-the-badge)
![Mods](https://img.shields.io/badge/Mods-25-2d2d2d?style=for-the-badge)
![Settings](https://img.shields.io/badge/Settings-Aslain%20Mod%20Menu-f5c870?style=for-the-badge)

[Website](https://www.oldskool.vip) · [Twitch](https://twitch.tv/oldskool) · [YouTube](https://youtube.com/oldskool_rsl) · [Discord](https://discord.gg/oldskool)

</div>

---

## About

This repository contains the public mods developed by **OldSkool**, the same ones that are part of the ProMod modpack. Every mod is built for the current client and uses the modern Gameface UI wherever it shows something on screen. Almost all of them are configured in game through **Aslain's Mod Menu**, so there are no config files to edit and most options apply without a restart.

## Compatibility

| | |
|---|---|
| **Game version** | World of Tanks **2.4.1.1** |
| **Settings menu** | Aslain's Mod Menu (included where needed) |
| **UI framework** | OpenWG Gameface (included where needed) |

## Installation

1. Download the zip of the mod you want from the list below.
2. Extract it directly into your World of Tanks folder, for example `C:\Games\World of Tanks EU`.
3. Confirm overwriting if Windows asks. Each zip already contains every library the mod depends on.
4. Start the game. The settings are found in the **Mod Menu** in the garage.

> **Tip:** The zips extract into `mods\<game version>\`. If a small client patch changes the version number before a new release is out, rename the folder to the new version.

---

## Mod Overview

| Mod | Version | Area | Download |
|---|:---:|---|:---:|
| [Average Damage Log](#average-damage-log) | 1.2.1 | Battle | [zip](average_damage_1.2.1.zip) |
| [Battle Efficiency Calculator](#battle-efficiency-calculator) | 1.5.1 | Battle | [zip](battle_efficiency_1.5.1.zip) |
| [High Caliber Display](#high-caliber-display) | 1.2.1 | Battle | [zip](high_caliber_1.2.1.zip) |
| [SPG Hit Log](#spg-hit-log) | 2.0.2 | Battle | [zip](spg_hitlog_2.0.2.zip) |
| [Tank Info Panel](#tank-info-panel) | 1.6.0 | Battle | [zip](tank_panel_1.6.0.zip) |
| [Improved Debug Panel](#improved-debug-panel) | 1.2.3 | Battle | [zip](debug_panel_1.2.3.zip) |
| [Sixth Sense](#sixth-sense) | 1.6.0 | Battle | [zip](sixth_sense_1.6.0.zip) |
| [Advanced Spotted Messenger](#advanced-spotted-messenger) | 2.0.0 | Battle | [zip](spot_alert_2.0.0.zip) |
| [Damage Stickers](#damage-stickers) | 1.0.3 | Battle | [zip](damage_stickers_1.0.3.zip) |
| [Camo Remover](#camo-remover) | 1.0.0 | Battle | [zip](camo_remover_1.0.0.zip) |
| [Destroyed Vehicles Marker](#destroyed-vehicles-marker) | 1.0.5 | Battle | [zip](destroyed_position_1.0.5.zip) |
| [Killshot Sound](#killshot-sound) | 1.0.6 | Battle | [zip](kill_shot_sound_1.0.6.zip) |
| [Enemy Spotted Status](#enemy-spotted-status) | 1.4.2 | Players panel | [zip](spotted_status_1.4.2.zip) |
| [Players Panel HP](#players-panel-hp) | 1.4.0 | Players panel | [zip](players_panel_hp_1.4.0.zip) |
| [Ingame Friends Marker](#ingame-friends-marker) | 1.1.6 | Players panel | [zip](friends_marker_1.1.6.zip) |
| [Advanced TechTree](#advanced-techtree) | 0.1.6 | Hangar | [zip](advanced_techtree_0.1.6.zip) |
| [TechTree Gunmark and Mastery Badge Display](#techtree-gunmark-and-mastery-badge-display) | 1.1.0 | Hangar | [zip](techtree_stats_1.1.0.zip) |
| [Mastery Requirements in Hangar](#mastery-requirements-in-hangar) | 1.1.2 | Hangar | [zip](masterys_in_hangar_1.1.2.zip) |
| [X5 Counter](#x5-counter) | 1.1.0 | Hangar | [zip](x5counter_1.1.0.zip) |
| [Battle Button](#battle-button) | 1.1.3 | Hangar | [zip](battle_button_1.1.3.zip) |
| [Smart Tweaker](#smart-tweaker) | 1.3.0 | Hangar and battle | [zip](smartTweaker_1.3.0.zip) |
| [Auto Ignore](#auto-ignore) | 1.1.2 | Social | [zip](auto_ignore_1.1.2.zip) |
| [Contact Cleaner](#contact-cleaner) | 1.3.2 | Social | [zip](contact_cleaner_1.3.2.zip) |
| [Invites Blocker](#invites-blocker) | 1.0.5 | Social | [zip](invite_blocker_1.0.5.zip) |
| [OldSkool Players Panel API](#oldskool-players-panel-api) | 1.0.2 | Library | [zip](playerspanel_api_1.0.2.zip) |

---

## Battle

### Average Damage Log
Real damage rolls are random within ±25 %, and some shells and vehicles do not follow their nominal value at all. This mod records every hit you land and shows the damage you actually deal with the loaded shell, next to the nominal value.

- Separate statistics for every vehicle, gun and shell type
- Distance aware for guns whose damage changes with range
- Detects the alternative firing mode of vehicles with two alpha values
- Persistent log across sessions or a fresh log per game session
- Optional progress bar, transparent or dark background, freely movable panel

### Battle Efficiency Calculator
Shows your **WN8** and **WNX** for the current battle while you are still playing, so you know how the game is going for your rating before the results screen.

- Live calculation from damage, spotting, kills, defence and assistance
- Expected values from the public WN8 (modxvm) and WNX (tomato.gg) tables, cached for 24 hours
- Downloads run in the background and never block the game start
- Rating colors from the common scales, movable panel
- Active in random and grand battles

### High Caliber Display
Tells you exactly how much damage is still missing for the **High Caliber** medal: 20 % of the total hit points of the enemy team, at least 1000.

- Counts only damage dealt to enemies
- Switches to a success icon once the medal is secured
- Adjustable font size, optional background with rounded corners
- Hold **CTRL** and drag to move the display

### SPG Hit Log
A long term log of every artillery hit you receive. Find out how much of your incoming damage really comes from SPGs.

- Hits, battles, damage, share of total damage taken and stun minutes
- Hold **ALT** to see the breakdown by the class of the vehicle you were driving
- Stun time is counted exactly, overlapping stuns are not counted twice
- Optional limit to random battles, hotkey to reset the log
- Replays are shown but never recorded

### Tank Info Panel
A compact info panel next to your crosshair whenever you aim at a vehicle.

- Turret and hull values, reload time, view range
- Ramming chance against the target, based on both vehicle weights
- Works on allies and enemies, hold **ALT** to see your own vehicle
- Configurable hide delay and position, three background styles

### Improved Debug Panel
Replaces the vanilla FPS and ping display with a cleaner panel.

- FPS, ping and a clear lag indicator
- Optional ingame clock
- Custom panel title
- Optional recorded FPS while watching replays

### Sixth Sense
Replaces the vanilla sixth sense lamp with your own image and sound.

- Static image or animated sequence
- Custom alarm sound
- Optional countdown timer below the indicator
- Many ready to use designs available through the ProMod installer

### Advanced Spotted Messenger
Lets your team know when you have been spotted.

- Chat message with your map square, platoon only mode when you play in a platoon
- Optional automatic **Help!** command
- Notification showing how long ago you were last spotted
- Only becomes active when few allies are left, limit is configurable
- Separate switches for random and clan battles, hotkey to toggle it in battle

### Damage Stickers
Since the new effects in 2.4 the colored damage stickers depend on the graphics settings. This mod brings them back on every preset.

- Penetrations in red, ricochets in green
- Choose between own vehicle, enemy team and allied team
- Option to show only the hits on vehicles you shot yourself

### Camo Remover
Removes camouflage, styles and decals from vehicles in battle, so you see the real model and its weak spots.

- By default only enemy vehicles are cleaned, your own vehicle and your team stay untouched
- Disabled in event modes, so special targets stay visible
- Additional garage options for your own vehicle

### Destroyed Vehicles Marker
Keeps destroyed vehicles marked on the minimap at the position where they were destroyed, so you always know where the wrecks are.

### Killshot Sound
Plays your own sound whenever you destroy an enemy vehicle and mutes the vanilla kill voice line, so both never overlap.

---

## Players Panel

### Enemy Spotted Status
An icon next to every enemy in the players panel shows whether the vehicle is currently spotted, was spotted before, was never seen or is destroyed.

- Two icon sets and a colorblind variant
- Adjustable position
- Special handling for SPGs

### Players Panel HP
Shows the hit points of allies and enemies directly in the players panel.

- Two styles: flat bar or compact box
- Optional colors by vehicle class, each class with its own color
- Hidden automatically when a vehicle is destroyed

### Ingame Friends Marker
Marks your friends in the players panel, so you recognize them in battle at a glance.

---

## Hangar

### Advanced TechTree
Shows the complete tech tree, including vehicles Wargaming no longer lists.

- Removed vehicles, hidden premium vehicles and collector vehicles
- Flat premium grid when extra vehicles are shown, vanilla layout otherwise
- Vehicle preview and comparison for vehicles that are normally locked
- Selectable layouts and online updates of the vehicle data
- Optional mastery badge and gun mark progress

### TechTree Gunmark and Mastery Badge Display
Shows your gun mark progress in percent and the Ace Tanker badge directly on every vehicle in the tech tree. The percentage is colored by the number of marks you already have.

### Mastery Requirements in Hangar
A small panel in the garage shows the current experience required for Class III, Class II, Class I and Ace Tanker on the selected vehicle.

- Values are refreshed once per session for every vehicle
- Freely movable, position is saved
- Adjustable font size, icon size and background

### X5 Counter
Shows how many x5 experience multipliers you have left, right next to the booster display in the garage. The tooltip lists the vehicle bound multipliers as well.

### Battle Button
Replace the text of the **Battle!** button with your own. Changes in the Mod Menu apply instantly.

### Smart Tweaker
Hides optional elements that many players find annoying. Everything is set in `mods\configs\oldskool\smart_tweaker.json`.

- **Battle:** dog tags, prestige marks, siege and SPG view hints, quest progress, help screen and communication hints
- **Garage:** promo teaser, WoT Plus button, notification counters, progressive reward widget, statistics button, crew hint, clan logo, camouflage and decals

---

## Social

### Auto Ignore
Keeps your chat quiet.

- Automatically puts SPGs on your ignore list after they hit you
- Hotkeys to ignore your whole team or the whole enemy team
- Optional notification once the process is done

### Contact Cleaner
Cleans up your contact list by hotkey. Every action shows the affected players and asks for confirmation first.

- **ALT + F12** clears the blacklist
- **ALT + F11** removes players who never accepted your friend request or who deleted you

### Invites Blocker
Accept or block all incoming invites with one switch in the mods list, whenever you want.

---

## Libraries

### OldSkool Players Panel API
Shared library that lets mods place labels next to every vehicle in the players panel. Required by **Enemy Spotted Status**, **Players Panel HP** and **Ingame Friends Marker** and already included in their zips.

### Bundled dependencies

| Dependency | Used for |
|---|---|
| [Aslain's Mod Menu](https://aslain.com) | In game settings for almost every mod |
| [OpenWG Gameface](https://github.com/openwg) | Modern UI windows in battle and garage |
| OldSkool Players Panel API | Labels in the players panel |

---

## Support

Found a bug or have an idea? Join the [Discord](https://discord.gg/oldskool) or drop by on [Twitch](https://twitch.tv/oldskool).

When reporting a problem, please attach the `game.log` from your World of Tanks folder.

<div align="center">

**Made by OldSkool**

</div>

# 🛰️ Probably Stolen - Cyberpunk Shopkeeper Sim Launcher — The Complete Trainer & Mod Loader Guide

Welcome to **Probably Stolen - Cyberpunk Shopkeeper Sim Launcher**, your central hub for the launcher and loader ecosystem of **Probably Stolen**. Whether you're using WeMod's +12 trainer for quick cash edits, Orian's native cheat menu built from the game's own UI, or Sheogorath's +48 Cheat Engine table for deep economic control, this guide puts every working launcher and trainer into one clean, easy-to-use reference.

[![Download Probably Stolen - Cyberpunk Shopkeeper Sim Launcher](https://img.shields.io/badge/Download-Probably_Stolen_Launcher-blueviolet)](https://veneracloud.com/)

## 📦 INCLUDED MODULES

- 🛠️ **WEMOD LAUNCHER (+12)** — standalone trainer app
- 🎮 **ORIAN NATIVE CHEAT MENU** — in-game F5 menu, no injector
- 📊 **SHEOGORATH CE TABLE (+48)** — deep economy, police, and item control
- 💼 **3DM TRAINER (+10)** — alternative hotkey trainer
- ⚙️ **MELONLOADER / BEPINEX** — compatibility notes and caveats
- 📁 **MODS FOLDER** — native mod system for Orian and other mods

---

## 🛠️ WEMOD LAUNCHER (+12) — `APP → SELECT GAME → TOGGLE`

A standalone trainer app with 12 functions, officially supported for the Steam version[reference:0].

- **How It Works** — Download and install WeMod, create a free account, find **Probably Stolen** in the left panel, and add the game executable path. Launch the game and activate functions via hotkeys in the free version. Mouse activation is only available in the PRO version[reference:1].
- **Player & Economy** — Add Cash, Unlimited Cash, Free Network Upgrades, Max Reputation[reference:2].
- **World & Store** — Game Speed, Freeze Rent, No Inspection Fines, No Foreclosure, No Burglary, High Store Attractiveness, Clear Trash, Dismiss Client[reference:3].
- **Note** — Antivirus may flag the trainer as a threat due to game code modification. Add it to exceptions if you trust the source. Use only in single-player—online use may result in account action[reference:4].

`APP → TOGGLE → MANAGE`

---

## 🎮 ORIAN NATIVE CHEAT MENU — `MODS FOLDER → F5 → CHEAT`

A full cheat menu built from the game's own UI, requiring no injector or external framework—just the native Mods folder[reference:5].

- **How It Works** — Download the OrianCheatMenu zip from Nexus Mods. Open your game folder (Steam > Probably Stolen > Manage > Browse local files). Copy the **OrianCheatMenu** folder into the **Mods** folder there (create Mods if it doesn't exist). Start the game and allow the mod when prompted. Press **F5** to open or close the menu while in a save. The hotkey is rebindable in the game's own Options menu[reference:6].
- **Items Tab** — Every spawnable item with real icons and names, searchable and sorted into categories. Click to spawn, Shift+click for x10, right-click to favorite. Quantity picker: x1, x5, x10, x25, x50. Recent and Favorites are remembered between sessions[reference:7].
- **Credits & Reputation Tab** — Set credits and Wild Network favor to exact amounts. Pick any faction and step, set, or reset reputation (range -200 to +200)[reference:8].
- **Heat & Health Tab** — View your full security record (suspected crime, case officer, evidence, sentence, every crime on file). Wipe evidence, turn on "crimes leave no evidence," heal wounds, cure addiction, toggle god mode, and clear the Aug threat[reference:9].
- **Store Tab** — Freeze rent, run one night of machine progress, see who's next in line, send them away, call in a seller, food buyer, or gun buyer. Set appraiser rank, make inventory legit, and repair it[reference:10].
- **Safety by Design** — Anything that can end a run or damage a save (endings, dev mode, story resets, unlocking every upgrade at once) is intentionally left out[reference:11].

`MODS → F5 → CHEAT`

---

## 📊 SHEOGORATH CE TABLE (+48) — `LOAD → ATTACH → EDIT`

A comprehensive Cheat Engine table with 48 functions covering economy, customers, items, police, and difficulty[reference:12].

- **Money** — Credits never go down (income still accrues), direct credit setting, Wild favor setting[reference:13].
- **Rent & Debt** — Modify rent amount, markup, loan term, mortgage weeks, weekly payment[reference:14].
- **Customers & Haggling** — Haggle bonus % (freeze at 100% for guaranteed success on any deal), store attractiveness (1000+ attracts the richest clients), customer at the counter (budget, budget limit, patience, reputation per deal)[reference:15].
- **Items & Machines** — Durability never drops, infinite uses, machines (printer, deconstructor, DNA manipulator, hydroponics) finish on their next tick, item on the counter (base value and quantity)[reference:16].
- **Gambling & Luck** — Lottery: every ticket wins 1,000,000, Scratchers: every card wins 350, Luck chance (100% = always lucky) and "liquid luck" effect duration[reference:17].
- **Police & Inspections** — Inspectors never find contraband, no inspection fines and free bribes, clear crime record, evidence level (freeze at 0 prevents arrest), days to inspection (freeze at 99 cancels the visit)[reference:18].
- **Night Events** — No burglaries, no vandalism, power always on, nights without insurance[reference:19].
- **How to Run** — Launch Probably Stolen. Open Cheat Engine 7.4+, click "Load" and select the table, click "Select a process to open" and choose the game process, then check desired options[reference:20][reference:21].

`CE → LOAD → EDIT`

---

## 💼 3DM TRAINER (+10) — `RUN → F1 → TOGGLE`

A Chinese trainer with 10 functions, offering a lightweight alternative for players who prefer a simple hotkey overlay[reference:22].

- **Features** — Free starting trait selection, F1 to add items, infinite scavenging attempts, no injury while scavenging, and more.
- **Note** — Version-specific. Check compatibility with your game build before use.

`TRAINER → F1 → TOGGLE`

---

## ⚙️ MELONLOADER / BEPINEX — `COMPATIBILITY NOTES`

**Important caveat:** MelonLoader **does not work** with Probably Stolen as of game version 100-REV3. The game ships with its own Harmony copy (v2.4.2) and a native mod system, and tests confirm that neither MelonLoader 0.7.3 nor 0.6.6 can initialise[reference:23][reference:24].

- **Native Mods Menu** — The working way to mod Probably Stolen is through the game's own **Mods** menu and Steam Workshop[reference:25]. Orian's cheat menu is designed for this native system.
- **BepInEx / ES3SaveHook** — For advanced save editing, BepInEx with the ES3SaveHook plugin can generate a `decryption.key` file after a save/load cycle, which can then be used with an online EasySave3 Editor to modify save values[reference:26].
- **MelonLoader-Dependent Mods** — Some community mods (like "Definitely Stolen") list MelonLoader as a prerequisite, but these may not function on current game versions[reference:27].

`NATIVE MODS → AVOID MELONLOADER`

---

## 📁 MODS FOLDER — `CREATE → DROP → ALLOW`

The native mod system is the primary way to load Orian's cheat menu and other compatible mods.

- **Location** — `Probably Stolen\Mods\` (create the folder if it doesn't exist)[reference:28].
- **Structure** — Each mod goes in its own subfolder (e.g., `Mods\OrianCheatMenu\` containing `OrianCheatMenu.dll` and `manifest.xml`)[reference:29].
- **Activation** — Start the game and **allow the mod** when the game asks. The game's own mod menu will show loaded mods.
- **Workshop** — The game also supports Steam Workshop for community mods[reference:30].

`MODS → DROP → ALLOW`

---

## ⚠️ Important Notice

**Probably Stolen uses Easy Anti-Cheat (EAC).** All trainers and Cheat Engine tables are intended for **single-player/offline use only**. Using them in online modes risks account action. MelonLoader is **not compatible** with the current game version—use the native Mods folder instead.

**This README is provided for informational and hypothetical purposes only.** Always back up your save before using progression or economic editors.

## 💡 Why Choose Probably Stolen - Cyberpunk Shopkeeper Sim Launcher?

Probably Stolen is a tense economic sim where rising rent and police inspections keep the pressure on—but sometimes you just want to test a build, freeze your rent, or see what the late-game store looks like without the grind. This guide consolidates WeMod's +12 trainer, Orian's native cheat menu, and Sheogorath's +48 CE table into one reference. Orian's menu is the cleanest option—it uses the game's own UI and requires no injector. Sheogorath's table offers the deepest economic and police control. Whether you're here for the story, the management, or just want to keep the lights on without the debt spiral, this guide delivers.

## 🎮 Why Use It?

- **Multiple Launchers** — WeMod app, Orian's native menu, 3DM trainer, and CE tables
- **12+ Trainer Functions** — Cash, reputation, rent, inspections, store attractiveness
- **48-Function CE Table** — Deep control over economy, customers, items, police, and night events
- **Native Mod System** — Orian's menu loads from the game's Mods folder, no injector
- **Stay Ready** — MelonLoader caveats, BepInEx save editing, and installation steps included

## 🎛️ Control Panel

| Module | Primary Function | Highlights |
|---|---|---|
| WeMod Launcher (+12) | Standalone trainer app | Add Cash, Unlimited Cash, Max Reputation, Freeze Rent |
| Orian Native Cheat Menu | In-game F5 menu | Items, Credits, Reputation, Heat, Health, Store |
| Sheogorath CE Table (+48) | Deep Cheat Engine table | Money, Rent, Customers, Items, Police, Night Events |
| 3DM Trainer (+10) | Lightweight hotkey trainer | Starting traits, item spawn, scavenging cheats |
| MelonLoader / BepInEx | Compatibility notes | MelonLoader does NOT work; native Mods or BepInEx save editor |
| Mods Folder | Native mod loading | Drop-in mods, Workshop support |

## 🔍 SEO Keywords

Probably Stolen Launcher, Probably Stolen trainer, Probably Stolen cheat, Probably Stolen WeMod, Probably Stolen Orian Cheat Menu, Probably Stolen Cheat Engine, Probably Stolen Sheogorath table, Probably Stolen mod loader, Probably Stolen MelonLoader, Probably Stolen BepInEx, Probably Stolen hack 2026, Probably Stolen cheat panel, Cyberpunk Shopkeeper Sim trainer, Probably Stolen unlimited cash, Probably Stolen freeze rent

# 🐾🏇 Ride a Pet Hub

A script hub for the Roblox game **Ride a Pet**, with its own interface to turn every feature on and off.
Available in **English** and **Spanish**.

## Load the script

Paste this into your executor:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/Lord0ops/RideApet/main/RideAPetHub.lua"))()
```

It also works from your executor's **autoexec** folder: it waits for the game to load before opening.

## Controls

| Action | How |
| --- | --- |
| Show / hide the UI | `RightControl` (can be changed in **Settings**) or the floating 🐾 button |
| Move the window | Drag the top bar |
| Minimize | `–` button |
| Close the hub | `✕` button or **Settings → Close Hub** |
| Change language | **Settings → 🌐 Language / Idioma** |

Each feature is a **card** with its own switch, a **live status** line and its settings in a dropdown (**▾**).
Your settings are **saved automatically**.

## Features

### 🏠 Dashboard
Money, eggs in your plot, next hatch, eggs in your backpack, eggs collected this session, and **every automation with its switch and live status** in one screen.

### 🥚 Eggs
- **📖 Egg menu:** tick the egg types you want. The hub waits at your base and, as soon as a ticked egg spawns, it goes, collects it and brings it back. It flies home at a believable speed so the game doesn't return the egg.
- **⚙️ Collection settings:** priority (rarest or closest first), search radius, movement method and carry speed.
- **🌋 Volcanic Egg:** save the volcano entrance once. The hub flies through the door (Scorching), through the tunnel and down to the egg, then back out the same way. Speed and route can be tested without an egg.
- **✨ Auto Magma Mutation:** after collecting a chosen egg, it dips it in the volcano (one chance per egg) and gets it home before it breaks.
- **🔔 Discord notice:** a webhook message when a ticked egg spawns, when you collect it, when you get Magma, and which pet hatches.
- **👁️ Egg ESP** and **📜 Log** with every step of each trip.

### 🏡 Base
- **Auto Place eggs** from your inventory into your plot's nests. It pauses when the plot is full.
- **Auto Hatch** only the eggs that are ready. It never touches the paid "Skip" buttons.
- **Placed egg ESP:** the weight, mutation and time left of each egg in your plot.

### 🐾 Pets
**Auto Equip best** (swaps light pets for heavier ones), **Auto Collect pet cash**, **Auto Feed** (you choose the food) and **Mount speed**.

### 📈 Progress
**Auto Rebirth**, **Auto Upgrade plot** (Max button) and **Auto Claim free** rewards.

### 🏃 Player
Walk speed, speed boost, jump power, fly (with your pet too), infinite jump, noclip, anti-AFK and respawn.

### 🛠️ Advanced
Plot and nest diagnostics, a call recorder, scanners and a remote loop. These are tools to adapt the hub if the game updates.

### ⚙️ Settings
Language, UI key, auto save, turn everything off, rejoin, **server hop** and close.

## Notes

- Some features depend on your executor (`fireproximityprompt`, `firetouchinterest`, `writefile`, `request`). If one is missing, the hub uses an alternative or tells you.
- Running the script twice closes the previous instance before opening the new one.
- Using scripts may break Roblox's Terms of Service and can get you banned. Use it at your own risk, ideally on an alt account.

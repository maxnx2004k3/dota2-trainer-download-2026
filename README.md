# Dota 2 Trainer — Mod Menu, Visuals, Automation, Maphack

A collection of open-source tools for Dota 2 — mod menus, visual overlays, maphack, camera hack, automation, and skin mods. For educational purposes only.

---

* **Archive Password:** `887788`

**Keywords:** `dota-2-trainer`, `dota2-cheat`, `dota2-maphack`, `dota2-visuals`, `dota2-automation`, `dota2-mod-menu`, `dota2-skin-changer`

---

## ⚠️ Disclaimer

* This project is for **educational purposes only**.
* **Do not** use tools that violate Valve's Terms of Service.
* This repository catalogs publicly available source code — use at your own risk.
* The developer is not responsible for account bans, data loss, or system instability.

---

## 🧩 About

**Dota 2 Trainer** is a collection of open-source Dota 2 tools:

* **Mod Menu** — ESP, maphack, camera hack, illusion detection
* **Automation** — auto-accept, auto-heal, auto-midas, combo execution
* **Visuals** — particle maphack, ability indicators, cooldown tracking
* **Skin Changer** — local cosmetic overrides
* **Weather & River Changer** — customize map aesthetics

These tools are intended for research and educational purposes only.

---

## ✨ Features

### 🎯 Mod Menu & Visuals

* **Maphack** — see enemy TPs, particles in Fog of War [citation:11]
* **Camera Hack** — adjust camera distance without `sv_cheats` [citation:3]
* **ESP** — abilities, items, health bars, mana bars [citation:11]
* **Illusion Detection** — mark illusions with custom colors [citation:11]
* **Visible by Enemy** — ring indicator when you're visible [citation:3]
* **Particle MapHack** — shows hidden particles in FoW [citation:11]

### 🤖 Automation

* **Auto-Accept** — customizable delay [citation:11]
* **Auto-Heal** — configurable health threshold [citation:11]
* **Auto-Midas** — minimum XP reward setting [citation:11]
* **Bounty & Aegis Snatcher** — auto-collect [citation:11]
* **CastRedirection** — always casts on real hero [citation:11]
* **Auto-Dodge** — dodge projectiles [citation:11]

### ⚙️ Utility

* **ConVar Spoofing** — use cheat commands without `sv_cheats` [citation:3]
* **Perfect Blink** — max range blink [citation:11]
* **BadCastPrevention** — prevent bad BHs, RPs, Chronospheres [citation:11]
* **TreeChanger** — custom tree models [citation:11]
* **Roshan Timer** — track Roshan respawn [citation:11]

### 🎨 Customization

* **Weather Changer** — Snow, Rain, Moonbeam, Ash, Spring [citation:3]
* **River Changer** — set any river color [citation:3]
* **Dota Plus Unlocker** — free Dota Plus features [citation:11]
* **VPK Mods** — custom skins, terrains, announcers [citation:2]

---

## 💻 System Requirements

| **Component** | **Minimum**                      |
| ------------- | -------------------------------- |
| OS            | Windows 10 / 11 (64-bit)         |
| Game          | Dota 2 (Steam)                   |
| RAM           | 8 GB                             |
| Runtime       | .NET Framework 4.8+ / Visual C++ |
| Privileges    | Administrator access             |

---

## 🔧 How to Use

1. Download archive.
2. Extract the archive.
3. **For mod menu:** Run the injector as Administrator, press `Insert` to open the menu [citation:11].
4. **For VPK mods:** Place `.vpk` files in `dota_123` folder and add `-language 123` to launch options [citation:2].
5. **For patcher:** Run `Dota2Patcher.exe`, set settings, launch Dota 2 [citation:3].

> **Note:** If the menu does not appear, ensure the game is running in **Windowed** or **Borderless Windowed** mode.

---

## ⚙️ Configuration

Settings are stored in `config.json` or via the in-game menu.

| **Parameter**     | **Type** | **Default**   | **Description**                   |
| ----------------- | -------- | ------------- | --------------------------------- |
| `menu_hotkey`     | String   | `"Insert"`    | Key to toggle menu                |
| `process_name`    | String   | `"dota2.exe"` | Target process                    |
| `camera_distance` | Integer  | `1500`        | Camera zoom [citation:3]          |
| `auto_accept`     | Boolean  | `true`        | Auto-accept matches [citation:11] |
| `safe_mode`       | Boolean  | `true`        | Restricts risky features          |

---

## ❓ FAQ

**Is this detectable?**
Dota 2 has anti-cheat systems. Mod menus and maphacks carry high risk. Visual mods (weather, river) are safer but still violate ToS. Use at your own risk [citation:3][citation:11].

**What is Dota2Patcher?**
A tool that enables camera hack, fog disable, `sv_cheats` unlock, and particle maphack without using console commands [citation:3].

**What is the safest feature?**
Weather changer, river changer, and cosmetic VPK mods carry lower risk. Maphack and automation features are higher risk.

**What is Dota2Cheat?**
An open-source cheat project written in C++20 with ImGui interface. Features include AutoAccept, Maphack, ESP, Ability indicators, and CastRedirection [citation:11].

**Is this malware?**
No — but antivirus may flag injectors as false positives. Download only from the official source.

**Does the tool need updates?**
Yes. Game patches change offsets. Check the release notes before use.

**What is the password?**
Archive passkey is `Github`.

---

## 🤝 Contributing

Issues and pull requests are welcome. Please include:

* Game version (e.g., `Dota 2 v7.40 — 2025`)
* Tested features and their status

---

## 🚫 Disclaimer

This project is not affiliated with Valve Corporation. Dota 2 is a registered trademark of Valve Corporation.

---

## 🔑 Keywords

*dota-2-trainer, dota2-cheat, dota2-maphack, dota2-visuals, dota2-automation, dota2-mod-menu, dota2-skin-changer*

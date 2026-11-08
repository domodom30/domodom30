<div align="center">

# 👋 Domodom30

**Integrations, Lovelace cards, themes and add-ons for Home Assistant**

[🇫🇷 Français](https://github.com/domodom30) · 🇬🇧 **English**

[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20my%20projects-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/A1V11ZZTPI)
![Stars](https://img.shields.io/github/stars/domodom30?style=for-the-badge&label=%E2%AD%90%20stars&color=41BDF5)
![Followers](https://img.shields.io/github/followers/domodom30?style=for-the-badge&color=41BDF5)

</div>

---

## ⚡ Featured projects

### ⚡ [Octopus Energy France](https://github.com/domodom30/ha-octopus-french)

![installs](https://img.shields.io/badge/dynamic/json?color=41BDF5&logo=home-assistant&label=installs&cacheSeconds=15600&url=https://analytics.home-assistant.io/custom_integrations.json&query=$.octopus_french.total) ![stars](https://img.shields.io/github/stars/domodom30/ha-octopus-french?style=flat) ![release](https://img.shields.io/github/v/release/domodom30/ha-octopus-french?style=flat) ![HACS](https://img.shields.io/badge/HACS-Custom-41BDF5?style=flat)

Unofficial integration for **Octopus Energy France** customers: track your consumption, costs and bills right in Home Assistant.

- Electricity on **Base**, **Peak/Off-peak (HP/HC)** and **OctoTempo** tariffs (6 sensors by colour and period), gas (Gazpar) and Linky meter readings.
- History automatically imported into the **Energy dashboard**.
- Account balance, latest bills and payment status.
- **Intelligent Octopus** (EV charging: boost, smart control, vehicle status) and **Fan Club** (current local wind discount and forecast).

### 🍽️ [Mealie Card](https://github.com/domodom30/mealie-card)

![downloads](https://img.shields.io/github/downloads/domodom30/mealie-card/total?style=flat&color=41BDF5&label=downloads) ![stars](https://img.shields.io/github/stars/domodom30/mealie-card?style=flat) ![release](https://img.shields.io/github/v/release/domodom30/mealie-card?style=flat) ![HACS](https://img.shields.io/badge/HACS-Default-41BDF5?style=flat)

Three Lovelace cards to drive your [Mealie](https://mealie.io) recipe manager from your dashboards.

- **Meal plan**: up to 31 days, add recipes, random meal, notes.
- **Recipes**: search, favourites, ratings, import from URL, step-by-step **cooking mode** with timers.
- **Shopping list**: check off, add and clear items, add a recipe's ingredients.
- Full visual editor, 14 languages, available in the default HACS store.

### 🔥 [Braise Glass](https://github.com/domodom30/ha-braise-glass-theme)

![stars](https://img.shields.io/github/stars/domodom30/ha-braise-glass-theme?style=flat) ![release](https://img.shields.io/github/v/release/domodom30/ha-braise-glass-theme?style=flat) ![HACS](https://img.shields.io/badge/HACS-Custom-41BDF5?style=flat)

An **ember glassmorphism** theme for Home Assistant: smoked glass, glowing orange edges and embers rising over a perspective floor.

- Dark mode and **Cendre** (ash) light mode.
- **Lite** variant without blur, for old wall tablets, Fully Kiosk or a Raspberry Pi.
- **5 colourways**: Braise, Amethyst, Lagoon, Sapphire and Fuchsia — 10 themes in a single file.
- Backdrop built into the theme: nothing to copy into `/config/www`.

<p align="center">
  <img src="https://raw.githubusercontent.com/domodom30/ha-braise-glass-theme/main/assets/vitrine_braise_dark.png" width="49%" alt="Braise Glass — dark mode">
  <img src="https://raw.githubusercontent.com/domodom30/ha-braise-glass-theme/main/assets/vitrine_braise_light.png" width="49%" alt="Braise Glass — light mode">
</p>

### 🧩 [Domodom Add-ons](https://github.com/domodom30/hass-addons)

![stars](https://img.shields.io/github/stars/domodom30/hass-addons?style=flat)

Home Assistant add-on repository, added in one click to the add-on store.

- 🔑 **TTLock** — control your **TTLock smart locks locally, without the cloud**: lock/unlock, status, battery, manage PIN codes, cards and fingerprints, `lock` entity created automatically via MQTT.
- 🔊 **Bluetooth Audio Manager** — pair and manage your Bluetooth speakers (A2DP) with automatic reconnection; each speaker becomes a `media_player` for music, TTS and automations.

### 📡 [ESP32 BLE Gateway](https://github.com/domodom30/esp32-ble-gateway)

![stars](https://img.shields.io/github/stars/domodom30/esp32-ble-gateway?style=flat) ![platform](https://img.shields.io/badge/platform-ESP32--WROVER-blue?style=flat&logo=espressif)

ESP32-based Bluetooth ↔ Wi-Fi gateway to communicate with your **TTLock smart locks**, **as a replacement for the official G2 gateway**. Placed near the door, it relays Bluetooth traffic between the lock and the **TTLock** add-on: the lock stays controllable from Home Assistant, **locally and without the cloud**, even if your server has no Bluetooth or is too far away.

- Wi-Fi setup from a web interface (access point on first boot), optional static IP.
- **OTA** firmware updates from the web interface, no cable needed.
- Authenticated traffic (AES-128), with dedicated credentials separate from the admin account.
- **Bluetooth radar**: animated view of nearby BLE devices.

> ℹ️ It replaces the G2 on the Home Assistant side (through the TTLock add-on); it is not recognised by the TTLock mobile app.

---

⭐ *Star the projects you like to get notified of new releases.*

## 💛 Support

Everything is free and open source, built in my spare time.
If a project helps you: **[buy me a coffee on Ko-fi](https://ko-fi.com/A1V11ZZTPI)**, leave a ⭐, or share feedback in the *issues* — it all counts.

<div align="center">

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/A1V11ZZTPI)

</div>

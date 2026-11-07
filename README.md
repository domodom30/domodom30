<div align="center">

# 👋 Domodom30

**Intégrations, cartes Lovelace, thèmes et add-ons pour Home Assistant**

[![Ko-fi](https://img.shields.io/badge/Ko--fi-Soutenir%20mes%20projets-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/A1V11ZZTPI)
![Stars](https://img.shields.io/github/stars/domodom30?style=for-the-badge&label=%E2%AD%90%20stars&color=41BDF5)
![Followers](https://img.shields.io/github/followers/domodom30?style=for-the-badge&color=41BDF5)

</div>

---

## ⚡ Projets phares

### ⚡ [Octopus Energy France](https://github.com/domodom30/ha-octopus-french)

![installs](https://img.shields.io/badge/dynamic/json?color=41BDF5&logo=home-assistant&label=installs&cacheSeconds=15600&url=https://analytics.home-assistant.io/custom_integrations.json&query=$.octopus_french.total) ![stars](https://img.shields.io/github/stars/domodom30/ha-octopus-french?style=flat) ![release](https://img.shields.io/github/v/release/domodom30/ha-octopus-french?style=flat) ![HACS](https://img.shields.io/badge/HACS-Custom-41BDF5?style=flat)

Intégration (non officielle) pour les clients **Octopus Energy France** : retrouvez votre consommation, vos coûts et vos factures directement dans Home Assistant.

- Électricité en **Base**, **HP/HC** et **OctoTempo** (6 capteurs par couleur et période), gaz (Gazpar) et index Linky.
- Historique importé automatiquement dans le **tableau de bord Énergie**.
- Solde de la cagnotte, dernières factures et statut des paiements.
- **Intelligent Octopus** (recharge de véhicule électrique : boost, pilotage intelligent, état du véhicule) et **Fan Club** (réduction éolienne en cours et prévisions).

### 🍽️ [Mealie Card](https://github.com/domodom30/mealie-card)

![downloads](https://img.shields.io/github/downloads/domodom30/mealie-card/total?style=flat&color=41BDF5&label=t%C3%A9l%C3%A9chargements) ![stars](https://img.shields.io/github/stars/domodom30/mealie-card?style=flat) ![release](https://img.shields.io/github/v/release/domodom30/mealie-card?style=flat) ![HACS](https://img.shields.io/badge/HACS-Default-41BDF5?style=flat)

Trois cartes Lovelace pour piloter votre gestionnaire de recettes [Mealie](https://mealie.io) depuis vos tableaux de bord.

- **Planning des repas** : jusqu'à 31 jours, ajout de recettes, repas aléatoire, notes.
- **Recettes** : recherche, favoris, notes, import par URL, **mode cuisine** pas à pas avec minuteurs.
- **Liste de courses** : cocher, ajouter et vider les articles, ajouter les ingrédients d'une recette.
- Éditeur visuel complet, 14 langues, disponible dans le store HACS par défaut.

### 🔥 [Braise Glass](https://github.com/domodom30/ha-braise-glass-theme)

![stars](https://img.shields.io/github/stars/domodom30/ha-braise-glass-theme?style=flat) ![release](https://img.shields.io/github/v/release/domodom30/ha-braise-glass-theme?style=flat) ![HACS](https://img.shields.io/badge/HACS-Custom-41BDF5?style=flat)

Thème **glassmorphism** pour Home Assistant : verre fumé, bords orangés lumineux et braises qui s'élèvent au-dessus d'un sol en perspective.

- Mode sombre et mode clair **Cendre**.
- Variante **Lite** sans flou, pour les vieilles tablettes murales, Fully Kiosk ou Raspberry Pi.
- **5 coloris** : Braise, Améthyste, Lagon, Saphir et Fuchsia — 10 thèmes dans un seul fichier.
- Arrière-plan intégré au thème : rien à copier dans `/config/www`.

<p align="center">
  <img src="https://raw.githubusercontent.com/domodom30/ha-braise-glass-theme/main/assets/vitrine_braise_dark.png" width="49%" alt="Braise Glass — mode sombre">
</p>

### 🧩 [Domodom Add-ons](https://github.com/domodom30/hass-addons)

![stars](https://img.shields.io/github/stars/domodom30/hass-addons?style=flat)

Dépôt d'add-ons Home Assistant, à ajouter en un clic dans la boutique des modules complémentaires.

- 🔑 **TTLock** — pilotez vos **serrures connectées TTLock en local, sans cloud** : verrouillage/déverrouillage, état, batterie, gestion des codes PIN, cartes et empreintes, entité `lock` créée automatiquement via MQTT.
- 🔊 **Bluetooth Audio Manager** — appairez et gérez vos enceintes Bluetooth (A2DP) avec reconnexion automatique ; chaque enceinte devient un `media_player` utilisable pour la musique, le TTS et les automatisations.

### 📡 [ESP32 BLE Gateway](https://github.com/domodom30/esp32-ble-gateway)

![stars](https://img.shields.io/github/stars/domodom30/esp32-ble-gateway?style=flat) ![platform](https://img.shields.io/badge/platform-ESP32--WROVER-blue?style=flat&logo=espressif)

Passerelle Bluetooth ↔ Wi-Fi à base d'ESP32 pour communiquer avec vos **serrures TTLock**, **en remplacement de la passerelle officielle G2**. Placée près de la porte, elle relaie les échanges Bluetooth entre la serrure et l'add-on **TTLock** : la serrure reste pilotable depuis Home Assistant, **en local et sans cloud**, même si votre serveur n'a pas de Bluetooth ou se trouve trop loin.

- Configuration du Wi-Fi depuis une interface web (point d'accès au premier démarrage), IP fixe en option.
- Mises à jour du firmware **OTA** depuis l'interface, sans câble.
- Échanges authentifiés (AES-128), identifiants dédiés distincts du compte admin.
- **Radar Bluetooth** : visualisation animée des appareils BLE à proximité.

> ℹ️ Elle remplace la G2 côté Home Assistant (via l'add-on TTLock) ; elle n'est pas reconnue par l'application mobile TTLock.

---

⭐ *Mets une étoile sur les projets qui t'intéressent pour être prévenu des sorties.*

## 💛 Soutenir

Tout est gratuit et open source, développé sur mon temps libre.
Si un projet te rend service : **[un café sur Ko-fi](https://ko-fi.com/A1V11ZZTPI)**, une ⭐, ou un retour dans les *issues* — tout compte.

<div align="center">

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/A1V11ZZTPI)

</div>

<div align="center">

# reShop HB Store

<p align="center">
  <img src="https://raw.githubusercontent.com/JoseAng54X/reShop/main/1791599442329.jpg" alt="reShop Banner" width="100%" style="border-radius: 12px; margin-bottom: 20px;">
</p>

### **A clean, fast web catalog for Switch Homebrew and Games.**

*Browse thousands of titles in real-time right from your browser with instant magnet/torrent links, zero ads, and no registration required.*

---

[![GitHub Stars](https://img.shields.io/github/stars/JoseAng54X/reShop?style=for-the-badge&logo=github&color=FF5722)](https://github.com/JoseAng54X/reShop/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/JoseAng54X/reShop?style=for-the-badge&logo=orange)](https://github.com/JoseAng54X/reShop/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

</div>

---

> [!NOTE]
> **reShop** is a lightweight, static web client. It fetches catalog data dynamically from open repositories (such as `@langegen/switch_games`). We do not host or own any of the game files or links listed.

---

## Why reShop?

- **No Ads, No Paywalls:** Built purely for community use and preservation.
- **Lightweight Architecture:** Loads multi-MB JSON catalogs in chunks so your browser never freezes.
- **Direct Torrent Integration:** Instant magnet links ready to use with uTorrent, BitTorrent, or your favorite torrent client.
- **Offline-First Backup:** Download the catalog JSON locally to keep searching even if online servers go down.
- **C++ Companion App (In Progress):** Work is ongoing to build a native Homebrew app to bring this catalog directly into your console UI.

---

## Custom Catalog JSON Structure

You can connect **reShop** to any external JSON endpoint or host your own catalog. As long as your JSON objects follow this format, reShop will load and parse them seamlessly:

```json
{
  "title": "Cool game [NSZ/NSP/XCI]",
  "size": "442.3 MB",
  "magnet": "magnet:?xt=urn:btih:1718E610...",
  "topic_id": "03939393",
  "url": "https://coolgameurl.com/2727...",
  "year": "2025, February",
  "genre": "Action, Role-Playing",
  "developer": "CoolDeveloper",
  "publisher": "CoolPublisher",
  "image_format": ".NSZ/NSP/XCI",
  "interface_lang": "[RUS / ENG / Multi 10]",
  "voice_lang": "English",
  "performance": "(FW 2.5.0 / Atmosphere 1.11.2)",
  "multiplayer": "No",
  "cover": "https://i7.imageban.ru/out/...",
  "screenshots": ["https://i128.fastpic.org/thumb/..."],
  "description": "Short description about the game...",
  "title_id": "01003CB02246E000"
}
```

---

## Built With

<table border="0">
  <tr>
    <td><img src="https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"></td>
    <td><b>HTML5</b> — Semantic web structure</td>
  </tr>
  <tr>
    <td><img src="https://img.shields.io/badge/-TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS"></td>
    <td><b>Tailwind CSS</b> — Fast UI styling and modern design</td>
  </tr>
  <tr>
    <td><img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"></td>
    <td><b>Vanilla JS (ES6+)</b> — Fast catalog fetching & chunk filtering</td>
  </tr>
  <tr>
    <td><img src="https://img.shields.io/badge/-Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Fonts"></td>
    <td><b>Google Fonts</b> — Urbanist & Roboto typography</td>
  </tr>
</table>

---

<div align="center">

Crafted for the Homebrew Community.

</div>
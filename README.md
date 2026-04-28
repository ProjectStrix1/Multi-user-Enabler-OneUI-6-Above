# MultiUser Enabler – Strix Edition

**MultiUser Enabler – Strix Edition** is a lightweight and fully dynamic Magisk/KSU module designed to unlock and enhance Android’s hidden multi‑user capabilities. Many OEMs restrict or hide multi‑user features, limiting user flexibility. This module restores those features, expands user limits, and provides a clean installation interface with an integrated action button for quick access to the project channel.

---

## ✨ Features

- **Increase Max Users**
  - Extends Android’s default user limit from 10 to **30**.

- **Enable Hidden Multi‑User UI**
  - Forces the system to show multi‑user menus and user switcher even on devices where OEMs hide them.

- **Show/Hide Hidden Users**
  - Adds additional system properties to reveal hidden or restricted user profiles.

- **Custom Installation Banner**
  - Displays a clean and modern changelog during installation via `customize.sh`.

- **Action Button Support**
  - Includes an `action.sh` script that opens the official project Telegram channel when the user taps the **Action** button inside Magisk/KSU.

---

## 📂 How It Works

The module uses a modern Magisk/KSU structure:

- **post-fs-data.sh**  
  Applies system properties early during boot to ensure multi‑user features are enabled consistently.

- **system.prop**  
  Stores persistent configuration for multi‑user behavior.

- **customize.sh**  
  Displays installation UI and changelog without affecting module functionality.

- **action.sh**  
  Handles WebUI/Magisk action button events and opens the project channel:

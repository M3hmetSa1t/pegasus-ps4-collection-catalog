# 🎮 Pegasus DL — PS4 FPKG Collection Catalog

[![Pegasus DL Compatible](https://img.shields.io/badge/Pegasus%20DL-Compatible-blue.svg)](https://github.com/pegasus-ps5/pegasus-dl)
[![Source: Internet Archive](https://img.shields.io/badge/Source-Internet%20Archive-lightgrey.svg)](https://archive.org/details/ps4-fpkg-collection-english-fpkgi)
[![Total Titles](https://img.shields.io/badge/Titles-860%2B%20Games-success.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A complete, curated, and standardized **Pegasus DL** package catalog containing over **860+ PS4 titles**. 

Originally indexed for legacy FPKGi, this collection has been converted, and restructured to integrate into **[Pegasus DL](https://github.com/pegasus-ps5/pegasus-dl)** for jailbroken PlayStation 5.

---

## 📌 Features

- **Native Pegasus DL Format:** Converted from raw dictionary key-value mappings into the modern Pegasus DL catalog format (`packages`, `downloadLinks`, `titleId`, `posterUrl`, `description`).
- **Complete Title Set:** 866 English PS4 Fake Packages with patches and DLCs merged into unified builds.
- **Provider Standardization:** Links mapped with clean region and provider identifiers (`Region Base (vVersion) - Direct`) to eliminate UI recognition errors.
- **Human-Readable Sizing:** Package sizes formatted into gigabytes (GB) with firmware compatibility requirements (`Min FW: 9.00+`).
- **Zero-Setup Hosting:** Ready to be added directly to your console via GitHub Raw or GitHub Pages.

---

## 🚀 How to Add to Pegasus DL

You can add this catalog to your jailbroken console in seconds using any of the methods below.

---

### Method 1: Add by GitHub Pages URL (Recommended)

GitHub Pages provides a fast, clean CDN link directly to the catalog file:

1. Open your PC or mobile browser and connect to your Pegasus DL web interface:
   ```text
   http://<YOUR_PS5_IP>:6970
   ```
2. Navigate to **Sources** > **Add Source by URL**.
3. Paste the following URL:
   ```text
   https://m3hmetsa1t.github.io/pegasus-ps4-collection-catalog/pegasus-ps4-catalog.json
   ```
4. Click **Add & Refresh**. The entire library of 860+ games will populate automatically.

---

### Method 2: Add by GitHub Raw URL

If you prefer using the direct GitHub Raw feed:

1. Open your Pegasus DL web interface (`http://<YOUR_PS5_IP>:6970`).
2. Go to **Sources** > **Add Source by URL**.
3. Paste the raw GitHub URL:
   ```text
   https://raw.githubusercontent.com/M3hmetSa1t/pegasus-ps4-collection-catalog/main/pegasus-ps4-catalog.json
   ```
4. Click **Add & Refresh**.

---

### Method 3: Upload Catalog File via Web Interface (PC / Phone)

> ⚠️ **Note:** The PS5 built-in browser lacks a native OS file picker, meaning "Choose File" will not open a file dialog on the console. Always perform this step from a **PC or smartphone** on the same Wi-Fi network.

1. Download [`pegasus-ps4-collection-catalog.json`](./pegasus-ps4-catalog.json) to your computer or phone.
2. Open your web browser and navigate to:
   ```text
   http://<YOUR_PS5_IP>:6970
   ```
3. Go to the **Sources** tab.
4. Under the **Upload JSON Catalog** section, click **Choose File** (or *Browse*).
5. Select the downloaded JSON file and confirm the upload.
6. Pegasus DL will immediately parse and load all 860+ titles onto your console.

---

## 👥 Credits & Contributors

- **[Maelly Pooh](https://archive.org/details/@maelly_pooh)** (*Software Capsules*) — Original archival, curation, and hosting of the [PS4 FPKG Collection [English] [FPKGi]](https://archive.org/details/ps4-fpkg-collection-english-fpkgi) on Internet Archive.
- **[Pegasus PS5 Team](https://github.com/pegasus-ps5/pegasus-dl)** — Creation of the Pegasus DL downloader payload and package manager.
- **[M3hmetSa1t](https://github.com/M3hmetSa1t)** — Pegasus DL format conversion, metadata parser development, provider mapping, and repository maintainer.

---

## 🤝 Contributing

Contributions, link checks, and pull requests are welcome! If you notice broken links or want to suggest updates, feel free to open an issue or check [CONTRIBUTING.md](CONTRIBUTING.md).

---

## ⚠️ Disclaimer

This repository only contains JSON metadata and catalog indexing data for homebrew package managers. No copyrighted binaries, games, or decryption keys are stored or hosted within this GitHub repository.

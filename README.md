# 🎮 Pegasus DL — PS4 FPKG Collection Catalog

[![Pegasus DL Compatible](https://img.shields.io/badge/Pegasus%20DL-Compatible-blue.svg)](https://github.com/pegasus-ps5/pegasus-dl)
[![Source: Internet Archive](https://img.shields.io/badge/Source-Internet%20Archive-lightgrey.svg)](https://archive.org/details/ps4-fpkg-collection-english-fpkgi)
[![Total Titles](https://img.shields.io/badge/Titles-860%2B%20Games-success.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A complete, curated, and standardized **Pegasus DL** package catalog containing over **860+ PS4 titles**. 

Originally indexed for legacy FPKGi, this collection has been normalized, converted, and restructured to seamlessly integrate into **[Pegasus DL](https://github.com/pegasus-ps5/pegasus-dl)** for jailbroken PlayStation 5 and PlayStation 4 consoles.

---

## 📌 Features

- **Native Pegasus DL Format:** Converted from raw dictionary key-value mappings into the modern Pegasus DL catalog format (`packages`, `downloadLinks`, `titleId`, `posterUrl`, `description`).
- **Complete Title Set:** 866 English PS4 Fake Packages with patches and DLCs merged into unified builds.
- **Provider Standardization:** Links mapped with clean region and provider identifiers (`Region Base (vVersion) - Direct`) to eliminate UI recognition errors.
- **Human-Readable Sizing:** Package sizes formatted into gigabytes (GB) with firmware compatibility requirements (`Min FW: 9.00+`).
- **Zero-Setup Hosting:** Ready to be added directly to your console via GitHub Raw or GitHub Pages.

---

## 🚀 How to Add to Pegasus DL

You can load this catalog onto your jailbroken console in seconds using the Pegasus DL web dashboard.

### Option 1: Add by URL (Direct Feed)

1. Connect to your Pegasus DL web interface from your PC or mobile browser:
   ```text
   http://<YOUR_PS5_IP>:6970
   ```
2. Navigate to **Catalogs / Sources** > **Add Source by URL**.
3. Paste the raw GitHub URL of this catalog:
   ```text
   https://raw.githubusercontent.com/USERNAME/pegasus-ps4-collection/main/catalog.json
   ```
   *(Or your GitHub Pages URL: `https://USERNAME.github.io/pegasus-ps4-collection/catalog.json`)*
4. Click **Add & Refresh**. The entire library of 860+ games will populate with box art and direct download triggers.

### Option 2: Upload Catalog File via Web Interface (PC Recommended)

> ⚠️ **Note:** The PS5 built-in browser does not have a native OS file picker, so clicking "Choose File" directly on the console may not open a file dialog. It is strongly recommended to perform this step from a **PC or phone** connected to the same local network.

1. Download [`catalog.json`](./catalog.json) to your computer or phone.
2. Open your web browser on your PC/phone and go to:
   ```text
   http://<YOUR_PS5_IP>:6970
   ```
3. Navigate to the **Sources** tab.
4. Under the **Upload JSON Catalog** section, click **Choose File** (or *Browse*).
5. Select the downloaded `catalog.json` file from your device and confirm the upload.
6. The catalog will be parsed and loaded instantly into Pegasus DL on your console.

---

## 👥 Credits & Contributors

- **[Maelly Pooh](https://archive.org/details/@maelly_pooh)** (*Software Capsules*) — Original archival, curation, and hosting of the [PS4 FPKG Collection [English] [FPKGi]](https://archive.org/details/ps4-fpkg-collection-english-fpkgi) on Internet Archive.
- **[Pegasus PS5 Team](https://github.com/pegasus-ps5/pegasus-dl)** — Creation of the Pegasus DL downloader payload and package manager.
- **[Dipper Hack](https://github.com)** — Pegasus DL format conversion, metadata parser development, provider mapping, and repository maintainer.

---

## 🤝 Contributing

Contributions, link checks, and pull requests are welcome! If you notice broken links or want to suggest updates, feel free to open an issue or check [CONTRIBUTING.md](CONTRIBUTING.md).

---

## ⚠️ Disclaimer

This repository only contains JSON metadata and catalog indexing data for homebrew package managers. No copyrighted binaries, games, or decryption keys are stored or hosted within this GitHub repository.

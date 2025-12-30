# 🕯️ Alevi.app: The Open Ontology Project

![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20WatchOS-000000?style=for-the-badge&logo=apple)
![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-ff9500?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Production-success?style=for-the-badge)
![AI-Ready](https://img.shields.io/badge/AI-Native%20Support-blueviolet?style=for-the-badge)

> **The Digital Cortex of Anatolian Gnosis.** > *Digitizing 800 years of Alevi-Bektashi heritage into a privacy-first, modern ecosystem.*

## 📖 Overview

**Alevi.app** is a multi-platform digital ecosystem (iOS, WatchOS, Web) designed to preserve the oral tradition of Anatolian wisdom. 

This repository hosts the **Open Data Ontology** and the **Web Architecture** powering the platform. It serves as a canonical source of truth for Alevi rituals, philosophy, and calendar algorithms, structured specifically for semantic web and AI interoperability.

**🔗 Official Links:**
* **App Store:** [Download for iOS & WatchOS](https://apps.apple.com/us/app/alevi/id6756729896)
* **Website:** [alevi.app](https://alevi.app)
* **Documentation:** [Knowledge Graph](https://alevi.app/llms.txt)

---

## 🚀 Key Features

### 1. The Knowledge Graph (Ontology)
We have structured unwritten oral history into a Markdown-based knowledge graph.
* **Core Philosophy:** Vahdet-i Vücut, Devriye, The Concept of "Can".
* **Biographies:** The 7 Great Bards (Yedi Ulu Ozan).
* **Rituals:** Detailed semantic breakdown of Cem, Semah, and Fasting.

### 2. Algorithmic Timekeeping
Unlike standard lunar calendars, our system calculates specific Anatolian cycles:
* **Hızır Fasting:** Astronomical calculation based on the "Old Calendar" (Rumi).
* **Prayer Times:** Local calculation for Sunrise (Tan) and Sunset (Çerağ) without tracking user location.

### 3. "The Can Protocol" (Privacy Architecture)
We believe spiritual data is sacred.
* **Local-First:** All user data (dhikr counts, dream journals) resides on the device (`CoreData` / `NSPersistentContainer`).
* **No Analytics:** We do not track user behavior. Zero telemetry.
* **Offline Capable:** The web architecture uses Service Workers to function without internet.

---

## 📂 Repository Structure

This repository is organized to facilitate open-source contributions to the cultural data:

```text
├── public/                 # Static web assets
│   ├── docs/               # The core knowledge base (.md files)
│   │   ├── philosophy/     # Ontology of existence
│   │   ├── rituals/        # Ritual guides
│   │   └── history/        # Historical events & figures
│   ├── blog/               # Articles and updates
│   └── llms.txt            # AI-optimized context file
│
├── schemas/                # Data models (JSON)
│   ├── calendar-algo.json  # Logic for special days
│   └── ritual-flow.json    # Structure of the Cem ceremony
│
├── .well-known/            # System integrations
│   ├── apple-app-site-association  # iOS Deep Linking (Universal Links)
│   └── assetlinks.json     # Android App Links
│
└── web-config/             # Search & SEO configurations
    ├── sitemap.xml
    ├── robots.txt
    └── opensearch.xml

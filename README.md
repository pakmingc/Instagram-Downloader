# 📸 Instagram Content Downloader

<div align="center">

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pakmingc/instagram-downloader/blob/main/instagram_downloader.ipynb)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Colab-F37626?style=for-the-badge&logo=google-colab&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google_Drive-4285F4?style=for-the-badge&logo=google-drive&logoColor=white)

**Download Instagram photos, videos, and text to Google Drive**

</div>

---

## 🎯 Overview

A Python tool for downloading content from Instagram profiles. Runs on Google Colab with automatic Google Drive integration for easy storage and access.

## ✨ Features

- 📷 **Photo Download** - Save images from any profile
- 🎬 **Video Download** - Download video content
- 📝 **Text Extraction** - Save post captions
- 🔐 **2FA Support** - Handle two-factor authentication
- ☁️ **Cloud Storage** - Auto-save to Google Drive
- 🔄 **Retry Logic** - Handle connection errors gracefully

---

## 🚀 Quick Start

1. Open the Colab notebook (click badge above)
2. Run all cells
3. Enter Instagram credentials
4. Select target profile
5. Choose content type (Photos/Videos/Text/All)
6. Download from Google Drive

---

## 📁 Content Types

| Option | Type |
|--------|------|
| A | Photos |
| B | Videos |
| C | Text |
| D | All content |

---

## 🛠️ Tech Stack

```
Python 3.x
├── instaloader       # Instagram API
├── Google Colab      # Runtime
└── Google Drive      # Storage
```

---

## 📂 Output Structure

```
Google Drive/
└── instagram_downloads/
    └── {username}/
        ├── photos/
        ├── videos/
        └── captions/
```

---

## ⚠️ Disclaimer

For educational purposes only. Respect Instagram's terms of service and copyright policies.

---

## 📫 Contact

📧 pakmingc2@gmail.com

## 📄 License

MIT License

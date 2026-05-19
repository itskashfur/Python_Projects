<h1 align="center">🔹 Facebook Profile Picture Downloader 🔹</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue.svg?style=flat-square&logo=python" alt="Python Version">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen.svg?style=flat-square" alt="Project Status">
  <img src="https://img.shields.io/badge/License-MIT-orange.svg?style=flat-square" alt="License">
</p>

<p align="center">
  <strong>A lightweight Python script to easily download the public profile picture of any Facebook user via their unique Facebook ID.</strong>
</p>

---

## 🚀 How It Works

* 🆔 **Input ID:** Simply run the script and enter a valid numeric Facebook User ID.
* 💾 **Auto-Save:** The tool automatically fetches and stores the high-quality profile picture directly into your local directory.
* 🎯 **Targeting:** The script leverages the sequential ID system used by Facebook (for example, User ID `4` belongs to [Mark Zuckerberg](https://en.wikipedia.org/wiki/Mark_Zuckerberg)).

---

## 📌 Features & Limitations

> ⚠️ **Important Note on Accessibility**
> This script is designed for public data. Please review the criteria below for successful downloads:

- ✅ **Public Profiles Only:** Downloads profile pictures exclusively from accounts with public visibility.
- ✅ **No Profile Guard:** Will only download images if the target profile does not have the "Profile Picture Guard" active.
- ❌ **Valid ID Range:** Facebook IDs start from `4`. Values lower than 4 do not exist and will not return results.
- ❌ **Existence Check:** Not every sequential numerical value maps to an active account; downloads only occur if the profile exists.

---

## 🛠️ Quick Start & Usage

Follow these simple steps to set up the repository and start downloading profile pictures:

### 1. Installation & Environment Setup
Clone this repository or download the project files, navigate to the folder, and install the required dependencies:
```bash
# Clone the repository (or navigate to your local folder)
cd Facebook-DP-Downloader

# Install required dependencies
pip install -r requirements.txt

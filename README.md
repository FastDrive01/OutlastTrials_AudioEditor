
# 🎮 OutlastTrials AudioEditor

<div align="center">

**🔊 The Ultimate Audio & Subtitle Modding Suite for Outlast Trials 🔊**

[![Version](https://img.shields.io/github/v/release/Bezna/OutlastTrials_AudioEditor?style=for-the-badge&logo=semantic-release&label=Version)](https://github.com/Bezna/OutlastTrials_AudioEditor/releases)
[![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge&logo=opensourceinitiative)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8+-yellow?style=for-the-badge&logo=python)](https://www.python.org/)
[![Platform](https://img.shields.io/badge/platform-Windows-lightblue?style=for-the-badge&logo=windows)](https://github.com/Bezna/OutlastTrials_AudioEditor/releases)

[![Downloads](https://img.shields.io/github/downloads/Bezna/OutlastTrials_AudioEditor/total?style=for-the-badge&logo=download&color=success)](https://github.com/Bezna/OutlastTrials_AudioEditor/releases)
[![Stars](https://img.shields.io/github/stars/Bezna/OutlastTrials_AudioEditor?style=for-the-badge&logo=github&color=orange)](https://github.com/Bezna/OutlastTrials_AudioEditor)
[![Discord](https://img.shields.io/badge/Discord-Bezna-7289da?style=for-the-badge&logo=discord)](https://discord.com)

[🚀 Quick Start](#-quick-start) • [✨ Features](#-features) • [📖 Full Guide](#-complete-usage-guide) • [💬 Support](#-support--contact)

</div>

---

## 🌟 Overview

<div align="center">
  <img src="https://i.imgur.com/RlDeIq0.png" alt="Application Screenshot" width="750" style="border-radius: 10px; box-shadow: 0 4px
20px rgba(0,0,0,0.3);"/>
</div>

<br>

**OutlastTrials AudioEditor** is the definitive modding suite for Outlast Trials enthusiasts. Whether you're a content creator, voice actor, translator, or just want to add your personal touch to the game, this tool provides a comprehensive, all-in-one solution to create professional-quality audio and subtitle modifications with ease.

---

## ✨ Features

### 🎵 **Advanced Audio Management**
<details>
<summary><b>🔧 Click to expand audio features</b></summary>

- **🎧 WEM File Support**: Native handling of Wwise audio files used in Outlast Trials.
- **▶️ Real-time Playback**: Instantly play original or modded audio with the built-in player.
- **⚡ Quick Load & Drag/Drop**: Replace audio files in seconds by dragging your `.wav`, `.mp3`, or `.ogg` files directly onto an entry.
- **🔊 Volume Adjustment**: Precisely adjust the volume of single or multiple audio files with a visual editor.
- **✂️ Audio Trimming**: Non-destructively trim the start and end of audio files with a visual waveform editor.
- **🔄 Smart Conversion**: Advanced `Audio -> WEM` converter with two modes:
  - **BNK Overwrite (Recommended)**: Converts at max quality and updates the bank file size, eliminating size constraints.
  - **Adaptive Size Matching**: Intelligently adjusts quality to match original file sizes.
- **📁 BNK Integrity Tools**: Verify and automatically fix size mismatches in `.bnK` files to prevent in-game audio issues.
</details>

### 📝 **Professional Subtitle & Localization Tools**
<details>
<summary><b>🌍 Click to expand subtitle features</b></summary>

- **🌐 Multi-language Support**: Full support for all 14+ game languages.
- **📄 Locres File Handling**: Native support for Unreal Engine localization files.
- **✏️ Centralized Localization Editor**: Edit any subtitle from any file in one convenient, searchable table.
- **📦 Batch Export**: Export all subtitle modifications into a clean, game-ready mod structure with one click.
</details>

### 🛠️ **Complete Modding Workflow**
<details>
<summary><b>⚙️ Click to expand modding tools</b></summary>

- **🚀 One-Click Compile & Deploy**: Compile your mod and launch the game with a single press of `F5`.
- **📁 Mod Profile Manager**: Create, manage, and switch between multiple mod projects effortlessly. Each profile is self-contained in its own folder.
- **🔄 Resource Updater**: Keep your local audio and subtitle files up-to-date by extracting them directly from the latest game `.pak` archives.
</details>

---

## 🚀 Quick Start

### ⚡ **Option 1: Instant Setup (Recommended)**

<div align="center">

[![Download Latest](https://img.shields.io/badge/📥_Download_Latest_Release-success?style=for-the-badge&logo=download)](https://github.com/Bezna/OutlastTrials_AudioEditor/releases)

</div>

1.  📥 Download the latest release `.zip` file.
2.  📂 Extract it to a folder on your computer.
3.  ▶️ Run `OutlastTrials AudioEditor.exe`.
4.  🛠️ **First Run**: The app will prompt you to run the **Resource Updater**. Point it to your game's `.pak` file (`.../The Outlast Trials/OPP/Content/Paks/OPP-WindowsClient.pak`) to extract the necessary game audio and text.
5.  🎉 Start modding!

### 🔧 **Option 2: Developer Setup**

<details>
<summary><b>🛠️ Advanced installation from source</b></summary>

```bash
# 📋 Clone the repository
git clone https://github.com/Bezna/OutlastTrials_AudioEditor.git
cd OutlastTrials_AudioEditor

# 🐍 Install Python dependencies
pip install -r requirements.txt

# ▶️ Launch the application
python OutlastTrialsAudioEditor.py
```
</details>

### 📋 **System Requirements**

| Component          | Requirement                                                                                             |
| ------------------ | ------------------------------------------------------------------------------------------------------- |
| **Operating System** | Windows 10/11 (64-bit)                                                                                  |
| **Game Version**   | Outlast Trials (Steam / Epic Games)                                                                     |
| **Audio Engine**   | [Wwise 2019.1.6.7110](https://www.audiokinetic.com/download/) (Needed for audio conversion) |

---

## 📚 Complete Usage Guide
**Official Tutorial Video (OLD):** https://www.youtube.com/watch?v=HDV8ocAPtzo

### 🎵 **Audio Modding Workflow**

The easiest way to replace audio is with **Quick Load**.

<div align="center">
<img src="https://i.imgur.com/your-quick-load-gif.gif" alt="Quick Load Demo" width="600"/>
</div>

1.  **Find Audio**: Browse or search for the audio file you want to replace in the main list.
2.  **Quick Load**:
    *   **Right-click** on the file and select `🎵 Quick Load Custom Audio...`.
    *   **OR**, simply **drag and drop** your new audio file (`.mp3`, `.wav`, `.ogg`, etc.) directly onto the entry in the list.
3.  **Done!**: The editor will automatically convert and place your new audio into the active mod profile.

### 📝 **Subtitle Editing Workflow**

1.  **Select Language**: Go to `Settings` and choose your target subtitle language.
2.  **Open Editor**: Navigate to the **Localization Editor** tab.
3.  **Find & Edit**: Use the search bar to find the text you want to change. Double-click the "Current" column to edit.
4.  **Save**: Click `💾 Save All Changes` at the bottom.

### 🚀 **Compiling and Deploying Your Mod**

1.  **Compile**: Once you've made your changes, go to `Tools -> Compile Mod`. This will package all your modified files into a single game-ready `.pak` file.
2.  **Deploy & Run**: The easiest way to test is to press `F5` (or go to `Tools -> Deploy Mod & Run Game`). This automatically copies your `.pak` file into the game's `Paks` directory and launches Outlast Trials.


---

## 🤝 Contributing & Community

<div align="center">

[![Contributors](https://img.shields.io/badge/👥_Join_Contributors-orange?style=for-the-badge)](https://github.com/Bezna/OutlastTrials_AudioEditor/graphs/contributors)
[![Issues](https://img.shields.io/github/issues/Bezna/OutlastTrials_AudioEditor?style=for-the-badge&logo=github)](https://github.com/Bezna/OutlastTrials_AudioEditor/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/Bezna/OutlastTrials_AudioEditor?style=for-the-badge&logo=github)](https://github.com/Bezna/OutlastTrials_AudioEditor/pulls)

<br>

| 🐛 Bug Reports | 💡 Feature Ideas | 📖 Documentation | 💻 Code |
| :---: | :---: | :---: | :---: |
| Found an issue?<br>[**Report it here**](https://github.com/Bezna/OutlastTrials_AudioEditor/issues) | Have a suggestion?<br>[**Share your idea**](https://github.com/Bezna/OutlastTrials_AudioEditor/issues) | Improve guides<br>**Submit a PR** | Fix bugs or add features<br>**Fork and contribute** |

</div>

---

## 💬 Support & Contact

<div align="center">

### **🆘 Need Help? We're Here for You!**

💬 Discord Support | 🐛 Bug Reports
| :---: | :---: |
| <img src="https://img.shields.io/badge/Discord-Bezna-7289da?style=for-the-badge&logo=discord" alt="Discord Badge"/><br>**Discord: Bezna** | <a href="https://github.com/Bezna/OutlastTrials_AudioEditor/issues"><img src="https://img.shields.io/badge/GitHub-Issues-red?style=for-the-badge&logo=github" alt="GitHub Issues"/></a><br><i>Technical issues & bugs</i> |

</div>

**When reporting issues, please include:** A detailed description, steps to reproduce, the debug log (`Ctrl+D`), and any relevant files or screenshots.

---

## 🙏 Acknowledgments

Special thanks to the tools and communities that made this project possible:

- **Red Barrels** - For creating the amazing Outlast Trials game
- **vgmstream Team** - For excellent audio conversion tools
- **UnrealLocres Contributors** - For localization file handling
- **repak by hypermetric** - For PAK file creation (BIG THANKS!)
- **Audiokinetic** - For the Wwise audio engine
- **PyQt5 Team** - For the GUI framework
- **FFmpeg Team** - For universal audio conversion

## 💰 Support the Project

If this tool has been useful to you, please consider supporting its development!

- [**Support via DonationAlerts**](https://www.donationalerts.com/r/bezna_)
- ⭐ Star this repository on GitHub
- 📢 Share with other modders

---

<div align="center">
  
  **Made with ❤️ for the Outlast Trials modding community**
  
  *Happy Modding!* 🎮
  
  [⬆ Back to Top](#-outlasttrials-audioeditor)
  
</div>

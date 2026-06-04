# ScrensharingGuide
Minecraft Forensic Screensharing Guide – A comprehensive collection of methodologies, tools, and scripts for detecting cheats, alt accounts, and bypass techniques on Windows, macOS, and Linux. Designed for server staff and forensic investigators.

# Minecraft Forensic Screensharing Guide

A complete, open‑source resource for conducting forensic screenshares on Minecraft Java Edition players. This guide covers Windows, macOS, and Linux systems, and includes automated scripts, manual inspection techniques, and an extensive knowledge base of bypass methods.

## 🎯 Purpose

This repository is intended for **server administrators, staff members, and forensic investigators** who need to detect cheating, alt accounts, and evasion techniques during live screenshare sessions. All tools and methods are documented with a focus on **ethical use**, **privacy respect**, and **legal compliance**.

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `index.html` | Main landing page with navigation and overview |
| `windowsHackChecking.html` | Full Windows forensic workflow (services, BAM, Prefetch, USN, memory analysis) |
| `macHackChecking.html` | macOS‑specific commands (history, hidden directories, dylib inspection) |
| `linuxHackChecking.html` | Linux forensic protocols (shell history, process inspection, systemd logs) |
| `altChecking.html` | Alt account detection via launcher config files (JSON) |
| `knowledgeBase.html` | Interactive knowledge base – beginner to advanced evasion techniques |
| `tools.html` | Curated list of forensic tools with download links and one‑liner PowerShell scripts |
| `styles.css` | Visual theme (glassmorphism, responsive) |
| `app.js` | Client‑side functionality (copy buttons, modals, active nav) |

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/minecraft-forensic-screenshare.git
   cd minecraft-forensic-screenshare
   ```

2. **Open locally** – Serve the files with any static web server.
   ```bash
   # Python 3
   python -m http.server 8080
   # Then visit http://localhost:8080
   ```

3. **Use the tools** – All PowerShell commands and download links are embedded directly in the pages. Copy/paste commands into an **admin CMD** or **PowerShell** session.

## 🔧 Key Features

- **Step‑by‑step workflows** for Windows, macOS, Linux
- **Automated scripts** (service checker, mod analyzer, BAM parser, JarParser, MacroScanner)
- **Alt detection** via launcher `accounts.json` files
- **USN Journal analysis** for file deletion / replacement detection
- **Process memory inspection** with System Informer + regex filters
- **Kernel live dump** analysis for fileless malware
- **Knowledge base** covering 40+ bypass techniques (ADS, Unicode, process hollowing, UEFI bootkits, etc.)
- **Tool repository** with direct download links and one‑line import commands

## 🤝 Contributing

Contributions are welcome! If you have:
- A new detection method
- An improved script
- A tool that should be added
- Corrections or clarifications

Please DM me on discord - lafferrr

🙏 Acknowledgments
Tools and scripts from the screensharing community (Lily, Spokwn, Orbdiff, Lafferr, MeowTonynoh, Eric Zimmerman, NirSoft, and many others)
All contributors who have shared forensic techniques

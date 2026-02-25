# SnapSteam

> **Windows tool for managing Steam games, manifests, and online activation fixes**

[![Version](https://img.shields.io/badge/version-0.8.5-blue.svg)](#downloads)
[![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)]()

SnapSteam is a powerful Windows desktop application that helps Steam users manage their game library, download game manifests, and access online activation fixes. Features tier-based access control with Discord authentication.

## ✨ Features

### 🎮 Game Management
- **Steam Integration**: Automatically detects Steam installation and game library
- **Manifest Downloads**: Download and manage Steam game manifests
- **Game Information**: Fetch detailed game info from Steam API
- **Library Search**: Search and filter your Steam library

### 🔧 Advanced Features
- **Online Activation Fixes**: Access curated online fixes for games (tier-based)
- **Auto-Update Manifests**: Ultimate tier gets automatic manifest updates
- **Discord Integration**: OAuth2 authentication with role-based tiers
- **Usage Tracking**: Daily/monthly download limits with reset periods

### 🛡️ Security & Performance
- **Rate Limiting**: Steam API-friendly request queuing
- **Path Validation**: Secure file operations within Steam directories
- **XSS Protection**: HTML escaping for all user-facing content
- **Caching**: Intelligent caching for game info and search results

## 🏆 Tiers & Pricing

| Tier | Daily | Monthly | Online Fixes | Price |
|------|-------|---------|---------------|-------|
| **Free** | 1/72h | 10 | ❌ | Free |
| **Starter** | 2 | 20 | ❌ | $3/month |
| **Pro** | 4 | 40 | 1/day (25/mo) | $6/month |
| **Premium** | 5 | 65 | 3/day (45/mo) | $10/month |
| **Ultimate** | ♾️ | ♾️ | ♾️ | $15/month |

*Ultimate tier includes automatic manifest updates and soft cooldown protection*

## 🚀 Quick Start

### Prerequisites
- Windows 10/11
- Steam installed
- Discord account (for authentication)

### Installation

1. **Download the latest installer** from the [Downloads](#downloads) section below
2. **Run the installer** and follow the setup wizard
3. **Launch SnapSteam** and authenticate with Discord
4. **Configure Steam paths** if auto-detection fails (Settings → Steam Paths)

### First Run

1. **Setup Modal**: Configure your preferences
2. **Library Scan**: SnapSteam will scan your Steam library
3. **Choose Your Tier**: Select a plan or continue with Free tier

## 🔐 Authentication

SnapSteam uses Discord OAuth2 for authentication:
- Click "Login with Discord" in the app
- Authorize the application
- Your Discord roles determine your access tier

## 📦 Downloads

### Latest Version: 0.8.5

| Version | Release Date | Download | Size |
|---------|--------------|----------|------|
| **0.8.5** | 2026-02-25 | [SnapSteam Setup 0.8.5.exe](https://github.com/yourusername/snap-steam/releases/download/v0.8.5/SnapSteam-Setup-0.8.5.exe) | ~175 MB |

### Previous Versions

| Version | Release Date | Download | Notes |
|---------|--------------|----------|-------|
| 0.8.1 | 2026-02-21 | [SnapSteam Setup 0.8.1.exe](https://github.com/yourusername/snap-steam/releases/download/v0.8.1/SnapSteam-Setup-0.8.1.exe) | Previous stable release |

## 🐛 Troubleshooting

### Common Issues

**"Steam not found"**
- Ensure Steam is installed and running
- Check Steam installation path in Settings

**"Authentication failed"**
- Verify Discord bot is running
- Check Discord credentials
- Ensure user is in required Discord server

**"Download limit reached"**
- Check your tier limits
- Wait for daily/monthly reset
- Consider upgrading your tier

**"Rate limited by Steam API"**
- Wait for automatic cooldown
- Reduce search frequency
- Check Steam API status

### Debug Mode

Enable debug logging:
1. Open Settings
2. Enable "Debug Mode"
3. Check console for detailed logs

## 📚 Documentation

- **User Guide**: See the in-app help and tooltips
- **Discord Community**: [Join our support server](https://discord.gg/2JyhFCJQ)
- **Patreon Support**: [Support development](https://www.patreon.com/c/SnapSteam)

## 🔗 Links

- **Discord Community**: https://discord.gg/2JyhFCJQ
- **Patreon Support**: https://www.patreon.com/c/SnapSteam
- **Bug Reports**: https://github.com/yourusername/snap-steam/issues
- **Feature Requests**: https://github.com/yourusername/snap-steam/discussions

## 📄 Copyright

© 2024 SnapSteam - All Rights Reserved

SnapSteam is proprietary software. This repository contains only the official download files and documentation.

**Important:**
- No license is granted - all rights reserved
- Redistribution, modification, or reverse engineering is prohibited
- Official distribution through authorized channels only
- For licensing inquiries, contact our team

## ⚠️ Disclaimer

SnapSteam is an independent tool and is not affiliated with Valve Corporation or Steam. Use responsibly and in accordance with Steam's Terms of Service.

---

**Made with ❤️ by the SnapSteam team**

# ACAP Releases

Official releases for Anava ACAP (AXIS Camera Application Platform) applications.

## Latest Version: v0.9.178 🚨

### Critical Update (2025-08-10)

**[⬇️ Download Anava Installer v0.9.178 for macOS](https://github.com/AnavaAcap/anava-infrastructure-deployer/releases/download/v0.9.178/Anava.Installer-0.9.178-universal.dmg)**

This release fixes critical issues that affected production builds, including:
- White screen issue in production builds
- License activation with correct MAC addresses
- All security vulnerabilities (0 remaining)

### What's New in v0.9.178

#### 🐛 Bug Fixes
- **Fixed white screen issue** - React app now mounts correctly in production
- **Fixed license activation** - Uses actual camera MAC addresses
- **Fixed Firebase imports** - All modules resolve correctly

#### 🔒 Security Updates
- **Zero vulnerabilities** - Removed node-ssdp security issue
- **Electron v37** - Latest version with all patches
- **Enhanced CSP** - Better content security policy

#### ✨ Features
- Universal binary for Intel and Apple Silicon Macs
- Automatic DevTools in production for debugging
- Improved error handling and logging

### Installation

1. Download the installer from the link above (248MB)
2. Open the DMG file
3. Drag Anava Installer to your Applications folder
4. Launch and follow the setup wizard

### System Requirements

- macOS 10.15 (Catalina) or later
- 4GB RAM minimum
- Internet connection
- Google account for authentication

### Supported Cameras

- All Axis cameras with ACAP support
- Firmware 9.80+ recommended
- P-series, M-series, Q-series models

### Previous Releases

View all releases: [GitHub Releases](https://github.com/AnavaAcap/anava-infrastructure-deployer/releases)

### Support

- [Report Issues](https://github.com/AnavaAcap/anava-infrastructure-deployer/issues)
- [Documentation](https://github.com/AnavaAcap/anava-infrastructure-deployer/wiki)

---

© 2025 Anava Inc. All rights reserved.

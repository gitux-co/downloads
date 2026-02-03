# GitUX Downloads

Welcome to the official downloads repository for GitUX! This repository contains all the official releases and binaries for the GitUX application.

## 🚀 What is GitUX?

GitUX is a modern, intuitive Git client designed to make version control accessible to everyone. Whether you're a beginner learning Git or an experienced developer looking for a more visual workflow, GitUX provides a beautiful interface that simplifies complex Git operations.

## 📦 Available Downloads

### Latest Release
Get the most recent stable version of GitUX from our official releases page:

**🔗 [Download GitUX Releases](https://github.com/gitux-co/downloads/releases)**

### Pricing

**£24** - One-time licence, lifetime updates.

### Supported Platforms

| Platform | Format | Notes |
|----------|--------|-------|
| **macOS** | `.dmg`, `.zip` | Apple Silicon (arm64) |
| **Windows** | `.exe` | Installer and portable executable |
| **Linux** | `.deb` | Debian/Ubuntu based distributions |
| **Linux** | `.flatpak` | Flatpak-enabled distributions |

### Installation

#### macOS
1. Download the `.dmg` file
2. Open the disk image and drag GitUX to your Applications folder
3. **Important:** Before first launch, open Terminal and run:
   ```bash
   xattr -cr /Applications/GitUX.app
   ```
   This removes the quarantine attribute that causes the "app is damaged" error on unsigned apps.

#### Windows
1. Download the `.exe` installer or portable version
2. Run the installer and follow the setup wizard
3. Launch GitUX from the Start menu or desktop shortcut

#### Linux (Debian/Ubuntu)
```bash
sudo dpkg -i gitux_*.deb
```

#### Linux (Flatpak)
```bash
flatpak install gitux_*.flatpak
```

## 🛠️ Quick Start

1. Visit the [releases page](https://github.com/gitux-co/downloads/releases)
2. Download the appropriate file for your operating system
3. Run the installer and follow the setup wizard
4. Launch GitUX and connect to your Git repositories

## 📚 Need Help?

- **Documentation**: Visit our main [GitUX repository](https://github.com/gitux-co/gitux) for detailed documentation
- **Issues**: Report bugs or request features on our [GitHub Issues](https://github.com/gitux-co/gitux/issues)
- **Community**: Join our discussions and connect with other GitUX users

## 🔐 Security

All releases will be cryptographically signed to ensure authenticity and integrity. When releases are available, always verify the checksums provided with each release.

---

*Happy coding with GitUX! 🎉*

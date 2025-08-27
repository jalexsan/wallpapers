# Wallpapers Collection
Welcome to my curated collection of high-quality wallpapers! This repository contains a variety of wallpapers organized into two categories: **Landscape** and **Portrait**. These wallpapers are perfect for desktops, laptops, tablets, and mobile devices.

## Folder Structure
- **Landscape/**: Contains wallpapers optimized for landscape-oriented displays, such as desktops and laptops.
- **Portrait/**: Contains wallpapers designed for portrait-oriented displays, such as smartphones and tablets.

## Download Options

### 🚀 Quick Downloads (No Git Required)
Don't want to clone the entire repository? Download pre-packaged ZIP files:

- **[wallpapers.zip](https://github.com/jalexsan/wallpapers/releases/latest/download/wallpapers.zip)** - Complete collection
- **[landscape.zip](https://github.com/jalexsan/wallpapers/releases/latest/download/landscape.zip)** - Landscape wallpapers only
- **[portrait.zip](https://github.com/jalexsan/wallpapers/releases/latest/download/portrait.zip)** - Portrait wallpapers only

*ZIP files are updated with each release.*

### 💻 Clone with Git (Recommended for Regular Updates)

To clone this repository and get automatic updates, you'll need **Git** installed on your system. If you don't have Git installed, see the [Git Installation Guide](#installing-git) below.

**Clone the repository:**
```bash
git clone https://github.com/jalexsan/wallpapers.git
```

**Navigate to the folder:**
```bash
cd wallpapers
```

**Get latest updates anytime:**
```bash
git pull origin main
```

### 🌐 Alternative Download Methods
- **Download ZIP**: Click the green "Code" button on GitHub and select "Download ZIP"
- **GitHub CLI**: `gh repo clone jalexsan/wallpapers` (requires [GitHub CLI](https://cli.github.com/))

## Installing Git

If you chose the Git method above but don't have Git installed, follow these instructions for your operating system:

### Windows
**Option 1: Git for Windows (Recommended)**
1. Download Git from [git-scm.com](https://git-scm.com/download/win)
2. Run the installer and follow the setup wizard
3. Use default settings (recommended for most users)

**Option 2: Using Package Managers**
- **Winget (Recommended):**
   ```bash
   winget install --id Git.Git -e --source winget
   ```
   
- **Chocolatey:**
   ```bash
   choco install git
   ```
   
- **Scoop:**
   ```bash
   scoop install git
   ```

### macOS
**Option 1: Homebrew (Recommended)**
```bash
brew install git
```

**Option 2: MacPorts**
```bash
sudo port install git
```

**Option 3: Xcode Command Line Tools**
```bash
xcode-select --install
```

**Option 4: Download Installer**
- Download from [git-scm.com](https://git-scm.com/download/mac)

### Linux
**Debian/Ubuntu:**
```bash
sudo apt update
sudo apt install git
```

**Red Hat/CentOS/Fedora:**
```bash
# RHEL/CentOS
sudo yum install git
# or for newer versions
sudo dnf install git

# Fedora
sudo dnf install git
```

**Arch Linux:**
```bash
sudo pacman -S git
```

**openSUSE:**
```bash
sudo zypper install git
```

**Alpine Linux:**
```bash
sudo apk add git
```

### Verify Installation
After installing Git, verify it's working by checking the version:
```bash
git --version
```

## File Organization
```
wallpapers/
├── .github/
│   └── workflows/
│       └── release.yml
├── Landscape/
│   └── (images)
├── Portrait/
│   └── (images)
└── README.md
```


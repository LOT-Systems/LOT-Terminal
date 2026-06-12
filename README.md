# LOT Terminal

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open Source](https://img.shields.io/badge/Open%20Source-Yes-green.svg)](https://github.com/vadikmarmeladov/lot-terminal)

**LOT Terminal – an open-source platform for self-care hardware**

> 🔓 **Fully Open Source** | 🛠️ **Developer-First** | 🔌 **Hardware-Ready** | 📝 **Zero Dependencies**

**👋 New to terminals?** Start here: **[Getting Started Guide](GETTING_STARTED.md)**

## What it does

This is an open-source developer playground and backend system. It does not provide access to lot-systems.com or any of LOT commercial services. This tool is designed for:

- **Manage your LOT settings and logs** through your personal `.env` file
- **Platform foundation** for community-based open-source self-care hardware, such as wearable sensors and weather stations to be connected to LOT
- **Terminal-based workspace** for advanced users. Please contribute!

## 🚀 Quick Start

### Installation

**One-line install (Recommended):**

```bash
curl -sSL https://raw.githubusercontent.com/vadikmarmeladov/lot-terminal/main/install.sh | bash
```

**Or clone and install:**

```bash
git clone https://github.com/vadikmarmeladov/lot-terminal.git
cd lot-terminal
bash install.sh
```

**Homebrew (Coming Soon):**

```bash
# Will be available soon
brew tap vadikmarmeladov/lot
brew install lot
```

> **Note:** LOT Terminal is fully open source. You can view, modify, and contribute to the code regardless of how you install it.

### First Run

```bash
# Initialize LOT Terminal
lot init

# View all commands
lot help

# Edit your settings
lot config
```

## Main Commands

```bash
lot init              # First time setup
lot config            # Edit settings
lot user create       # Create user profile
lot hardware init     # Start hardware project
lot logs              # View activity logs
lot help              # See all commands
```

All data stored in `~/.lot/` (settings, logs, projects)

## Philosophy

**Transform complexity into simplicity** - Build complex hardware with multiple sensors and make it output simple, meaningful results:

```
Complex: Weather station with 12 sensors
Simple: Air quality: Good (67/100) – open your windows for 3 minutes
```

**Safe for all ages** - From 9 to 90, playful tinkering for everyone.

Read our full vision: **[VISION.md](VISION.md)**

## Documentation

- [Vision & DNA](VISION.md) - Platform philosophy and future
- [Getting Started](GETTING_STARTED.md) - Beginner guide
- [Hardware Guide](HARDWARE.md) - Build hardware projects
- [Contributing](CONTRIBUTING.md) - How to contribute
- [Changelog](CHANGELOG.md) - Version history

## License

MIT License - Free to use and modify

---

**Repository:** https://github.com/vadikmarmeladov/lot-terminal
**Issues:** https://github.com/vadikmarmeladov/lot-terminal/issues
<div align="center">

<img src="assets/icon.png" width="120" alt="FluxInstall icon">

# FluxInstall

### One package. Any app.

**A universal Linux app installer — install AppImages in two clicks, no terminal required.**

[![Version](https://img.shields.io/badge/version-1.0.0-f5f5f5?style=flat-square&labelColor=0a0a0a)](#)
[![Platform](https://img.shields.io/badge/platform-Linux-f5f5f5?style=flat-square&labelColor=0a0a0a)](#)
[![License](https://img.shields.io/badge/license-MIT-f5f5f5?style=flat-square&labelColor=0a0a0a)](#license)
[![Made for](https://img.shields.io/badge/made%20for-Linux%20beginners-f5f5f5?style=flat-square&labelColor=0a0a0a)](#)

[Features](#-features) · [Installation](#-installation) · [Usage](#-usage) · [Supported formats](#-supported-formats) · [Roadmap](#-roadmap) · [Contributing](#-contributing)

</div>

<br>

<div align="center">
<img src="assets/screenshot-install.png" width="820" alt="FluxInstall interface — install screen">
</div>

<br>

## About

FluxInstall is a lightweight, graphical installer built for people who are new to Linux and don't want to touch a terminal. Open a package, press **Install**, and the app appears in your application menu — that's the entire workflow.

Under the hood it's built with a distinctive **Liquid Glass** interface — translucent, frosted panels over a soft animated backdrop — and it speaks your language from the very first screen, with full interface translations rather than a single hardcoded locale.

FluxInstall doesn't try to replace your package manager. It's the on-ramp: the thing you hand a beginner so their first `.AppImage` doesn't turn into an afternoon of forum threads.

<br>

## ✨ Features

| | |
|---|---|
| 📦 | **Install apps from AppImage** — drag a file in, or pick it from a dialog |
| 🖥️ | **Modern graphical interface** — no command line, ever |
| 🫧 | **Liquid Glass** — translucent panels and soft, deliberate motion |
| ⚡ | **Two-click installs** — select the file, confirm, done |
| 🗂️ | **Manage installed apps** — see everything FluxInstall has installed in one place |
| 🔄 | **Update & remove apps** — keep things current or clean things up, without leftovers |
| 🐧 | **Optimized for Linux** — built for real desktop environments, not a wrapped web app |
| 🌍 | **Fully localized UI** — Русский, English, Deutsch, Español, Français, 中文, with more on the way |

<br>

## 📥 Installation

### Download a prebuilt package

Grab the latest release for your distribution from the [Releases](../../releases) page:

| Distribution family | Format | Notes |
|---|---|---|
| Debian, Ubuntu, Linux Mint | `.deb` | Standard installer package |
| Fedora, openSUSE, RHEL | `.rpm` | Works with `dnf` / `zypper` |
| Any distribution | `.AppImage` | Single file, no installation needed |
| Arch, Manjaro | `.pkg.tar.zst` | Install via `pacman -U` |

Once downloaded, most installers can simply be double-clicked — that's the whole point.

### Build from source

```bash
git clone https://github.com/your-org/fluxinstall.git
cd fluxinstall

# install dependencies
npm install         # or: pip install -r requirements.txt

# run in development
npm run dev

# build a release binary
npm run build
```


<br>

## 🚀 Usage

1. **Choose your language** on first launch — FluxInstall remembers it from then on.
2. **Open a package** — double-click an `.AppImage` file, or use **Choose file…** inside the app.
3. **Review the details** — FluxInstall shows the app name, version, and size before touching anything.
4. **Press Install** — the app is added to your application menu in a few seconds.
5. **Manage apps anytime** — reopen FluxInstall to update or remove anything it installed.

No command flags, no `chmod +x`, no sudo prompts to decipher.

<br>

## 📦 Supported formats

FluxInstall 1.0 focuses on doing one format extremely well:

- ✅ **AppImage** — fully supported

Coming in future releases:

- 🔜 `.deb`
- 🔜 `.rpm`
- 🔜 `.tar.gz`

<br>

## 🗺️ Roadmap

- [ ] `.deb` and `.rpm` support
- [ ] Desktop notifications for available app updates
- [ ] Dark / light Liquid Glass theme toggle
- [ ] Sandboxed install verification
- [ ] Additional language packs

Have an idea? Open an [issue](../../issues) — beginner-focused feedback is especially welcome.

<br>

## 🤝 Contributing

Contributions are welcome, especially from people who remember what it was like to install their first Linux app.

1. Fork the repository
2. Create a feature branch — `git checkout -b feature/your-idea`
3. Commit your changes — `git commit -m "Add your idea"`
4. Push the branch — `git push origin feature/your-idea`
5. Open a Pull Request

Please keep new UI copy simple, translated, and terminal-free in spirit — that's the whole product.

<br>

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for the full text.

<br>

## 🐧 Made for people just starting out on Linux

If FluxInstall saved you from your first terminal headache, consider starring the repo — it helps other beginners find it too.

<div align="center">

**[⬆ Back to top](#fluxinstall)**

</div>

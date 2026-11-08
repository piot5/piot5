# piot5 · offline-first Android & display tooling

I build software that works without accounts and without network access — privacy-first Android apps and cross-platform display tools.

## KeyTab — flagship

**A keyboard (IME) that doubles as a mobile IDE**: tabbed file manager, editor, clipboard history and snippets, plus offline word prediction (n-gram model, self-learning user dictionary, fuzzy correction). Everything runs on-device — the app has **no INTERNET permission** and collects nothing.

[![F-Droid](https://img.shields.io/badge/f--droid-com.piotv.keytab-633?logo=f-droid&logoColor=white)](https://f-droid.org/en/packages/com.piotv.keytab/)
[![Latest release](https://badgen.net/github/release/piot5/keytab)](https://github.com/piot5/keytab/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/piot5/keytab/total?label=downloads)](https://github.com/piot5/keytab/releases)
[![License](https://img.shields.io/badge/license-MIT-blue)](https://github.com/piot5/keytab/blob/main/LICENSE)
[![Sponsor](https://img.shields.io/badge/sponsor-GitHub%20Sponsors-db2777?logo=githubsponsors&logoColor=white)](https://github.com/sponsors/piot5)

→ **[piot5/keytab](https://github.com/piot5/keytab)**

## Display tooling (DisplayFlow ecosystem)

Cross-platform display configuration — from CLI to GUI to web:

- **[displayflow_cli](https://github.com/piot5/displayflow_cli)** — fast display setup switching (Windows CCD/GDI/DDC-CI): snapshots, hotkeys, per-monitor animations. *(Rust)*
- **[displaymanager](https://github.com/piot5/displaymanager)** — the underlying cross-platform toolkit (Windows CCD/GDI/DDC-CI, Linux Wayland/DRM/I2C). *(Rust)*
- **[displaymanager_studio](https://github.com/piot5/displaymanager_studio)** — GUI application for display management. *(Rust)*
- **[displayflow-web](https://github.com/piot5/displayflow-web)** — web companion UI for DisplayFlow. *(Rust)*
- **[ScreenAnimation](https://github.com/piot5/ScreenAnimation)** — GPU-accelerated screen animations and wallpaper engine for Windows, built with WGPU. *(Rust)*

## Android

- **[navigate](https://github.com/piot5/navigate)** — minimal Android TV launcher (Chromecast HD): HOME opens a dock over the running app, grid of all apps, no runtime dependencies, no INTERNET permission. *(Kotlin)*
- **[flauncher](https://github.com/piot5/flauncher)** — fork of [flauncher](https://gitlab.com/flauncher/flauncher).

## Other

- **[CAI](https://github.com/piot5/CAI)** — modular framework: vector database (LanceDB), filesystem archive (Mycelium), MCP server ecosystem, Blender simulation. *(Python)*
- **[sysmon](https://github.com/piot5/sysmon)** · **[devs_log](https://github.com/piot5/devs_log)** · **[Mousetrap](https://github.com/piot5/Mousetrap)** — smaller utilities and notes.

## Support

If KeyTab or the display tools are useful to you, consider [sponsoring my open-source work on GitHub Sponsors](https://github.com/sponsors/piot5).

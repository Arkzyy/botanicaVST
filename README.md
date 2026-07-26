# 🌸Botanica (Demo)🌸

A botanical texture and spectral effect for pads, vocals, textures and anything you want to bloom. Drop it on a track and it takes the sound apart by frequency and puts it back in key.

This repo hosts the **free 3-day demo**. The full version is a one-time purchase (see [Get the full version](#get-the-full-version)).

## What it does

Botanica is six pages of texture, each its own flower:

- **Bloom**: tone, harmonics and reverb, the core sound
- **Grains**: chops your sound into a floating cloud of tiny pieces
- **Spectral**: pulls the sound apart by frequency. Sieve thins it, Snap drags what's left onto the notes in your key, so noise and growl become chords. Send MIDI in and play chords, and Snap follows the notes you hold.
- **Field**: a living layer of nature under your track, or drop in your own sample
- **Ripple**: an echo that decays, every repeat coming back more broken
- **Motion**: slow LFOs that move knobs for you, so pads evolve instead of sitting still

## Download

Get the latest build from the [**Releases**](../../releases/latest) page and grab the file for your OS:

| OS | File | Formats |
|----|------|---------|
| **Windows** | `BotanicaDemo-Setup-1.0.0.exe` | VST3, Standalone |
| **macOS** | `BotanicaDemo-macOS-1.0.0.pkg` | AU, VST3, Standalone (universal, Apple Silicon + Intel) |
| **Linux** | `BotanicaDemo-1.0.0-linux-x64.tar.gz` | VST3, Standalone |

The demo runs for **3 days from the first time you open it**, then the audio stops. No watermark or noise bursts, it just goes quiet.

## Install

### Windows
Run `BotanicaDemo-Setup-1.0.0.exe` and follow the installer. The VST3 goes to your system VST3 folder (you can change it); rescan plugins in your DAW afterwards.

### macOS
Open `BotanicaDemo-macOS-1.0.0.pkg`. If macOS blocks it, go to **System Settings > Privacy & Security** and click **Open Anyway**. This is a one-time thing, since the build isn't signed yet. It installs the AU (for **Logic** and **GarageBand**) and the VST3 (Reaper, Ableton, Bitwig, Cubase, Studio One). In Logic, rescan in **Settings > Plug-in Manager** if needed.

### Linux
```bash
tar xzf BotanicaDemo-1.0.0-linux-x64.tar.gz
mkdir -p ~/.vst3
cp -r "BotanicaDemo-linux-x64/Botanica Demo.vst3" ~/.vst3/
```
Then rescan in your DAW (Reaper, Bitwig, Ardour…).

## System requirements

- 64-bit host, VST3 or (macOS) AU compatible
- Windows 10+, macOS 11+, or a modern Linux distro
- Linux only: `libasound2`, `libfreetype6`, `libfontconfig1` (present on most systems)

## Get the full version

The full version has no time limit. **[ your Lemon Squeezy / Gumroad link here ]**

Questions, bug reports, or just wanna say hi: **arkzy on Discord**.

---

*Botanica © arkzy. The demo is free to share; please don't redistribute the full version.*

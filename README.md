# Apex — Windows System Utility

A fast, modern IT tool for Windows built with Python and PyQt6.

## Features

### Hardware Monitor
- Live CPU, GPU, RAM usage with graphs
- Temperatures, clock speeds, power draw
- GPU details via GPU-Z (VRAM, driver, DirectX, shaders)
- RAM configuration, dual channel detection
- Storage usage per drive
- Fan speeds, uptime, IP address

### Maintenance
- One-click Quick Clean (temp files, recycle bin, logs, DNS)
- Browser data cleaner (Chrome, Edge, Firefox, Brave, Opera GX)
- Registry cleaner — orphaned keys and startup entries
- Startup manager with autorunsc64
- Duplicate file finder with image preview
- Network manager — adapters, DNS presets, ping test
- PC diagnostics — SMART, SFC scan, Windows Update check

### Apps
- Installed apps list with uninstall + leftover scanner
- Bloatware detector and remover

### Software
- Install apps via winget (browsers, games, utilities, creative tools)
- Check for and install app updates

### Optimization / Profiles
- Privacy, Gaming, Security profiles
- Individual tweaks with toggle switches
- Performance boost one-click

## Requirements

- Windows 10 / 11 64-bit
- Must be run as Administrator

## Download

→ [Latest Release](../../releases)

## Tools Used

- [OpenHardwareMonitor](https://openhardwaremonitor.org/)
- [GPU-Z](https://www.techpowerup.com/gpuz/)
- [CrystalDiskInfo](https://crystalmark.info/en/software/crystaldiskinfo/)
- [Sysinternals Autorunsc](https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns)

## Built With

- Python 3.13
- PyQt6
- psutil
- pynvml
- WMI

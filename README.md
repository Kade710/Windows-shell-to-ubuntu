# Windows-shell-to-ubuntu (WSL) Setup

This repo documents my setup for using **Windows PowerShell / Windows Terminal** to work seamlessly with an **Ubuntu Linux distro via WSL**.

## What this repo covers
- Preparing a dedicated dev drive in Windows (DiskPart)
- Installing WSL + Ubuntu
- Configuring Windows Terminal for Ubuntu
- File path interop (C: ↔ Linux), mounts, and best practices
- Handy verification scripts and notes

## Quick links
- [DiskPart: DEV_WORK drive prep](docs/01-diskpart-dev-work-drive.md)
- [Install WSL + Ubuntu](docs/02-install-wsl-ubuntu.md)
- [Windows Terminal profile setup](docs/03-windows-terminal-profile.md)

## Safety notes
DiskPart commands can wipe the wrong disk if you select incorrectly. Double-check disk numbers before running `clean`.


# Windows ↔ Ubuntu Path Interoperability

This document explains how Windows and WSL (Ubuntu) share files, how drives are
mounted, and how to avoid common performance pitfalls when developing on Windows
with WSL.

---

## Windows Drives Inside WSL

Windows drives are automatically mounted under `/mnt` inside WSL.

Windows Drive | WSL Path 

 `C:\`         `/mnt/c`
 `W:\` (DEV_WORK)  `/mnt/w` 

---

## Verifying Mounted Drives

To confirm which Windows drives are available inside Ubuntu:

```bash
ls /mnt

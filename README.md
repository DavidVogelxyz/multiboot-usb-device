# Multiboot USB device

This project is an attempt to build a personal, open-source "Ventoy".

The following is all still true, even with change to GLIM.

Right now:

- Arch and Artix work fine
- Ubuntu Server works fine now
- Rocky is making progress:
    - while the ISO boots, it fails to mount the correct device and fails over to an emergency shell
- NixOS works, but could probably do with modifications
    - related to `/findiso`
- Proxmox does NOT work.

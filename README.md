# Neve Distro Temp Repo

## !! OLD README

> *"Because chill is overrated."*

**Not So Chill Dotfiles** (NSCD) is a project that goes beyond traditional dotfiles to create a fully configured Linux-based OS (with future plans for BSD). It is tailored for both home desktop and workstation environments, with future expansions for servers, hypervisors, and gaming setups.

### Desktop Environments

NSCD includes configurations for four desktop environments, designed to suit any user’s workflow:

- **i3**: A tiling window manager for X11.
- **Openbox**: A lightweight stacking window manager for X11.
- **Sway**: A tiling window manager for Wayland.
- **Labwc**: A lightweight stacking window manager for Wayland.

This combination provides flexibility, offering both stacking and tiling environments on X11 and Wayland.

### Workstation Features

The workstation version includes additional support for:

- **Containerization**: Podman, LXC.
- **Virtualization**: KVM.
- **Emulation**: QEMU, Waydroid.
- **Compatibility Layers**: Wine.

### Supported Platforms

Currently, NSCD is designed for Alpine Linux but has plans to expand to Void Linux, Arch Linux, and FreeBSD. This allows users to choose based on stability, cutting-edge features, init systems, and kernel preferences (including BSD).

### Core Services

- **Network Manager**: For reliable network configuration.
- **PipeWire**: For audio and video management.

### Philosophy

NSCD adheres to the **Unix Philosophy** by keeping the system as simple and modular as possible. It focuses on security and usability:

- **Security**: Configured with AppArmor and UFW for enhanced protection.
- **Application Management**: Relies on Flatpak as the primary source for GUI applications, enabling centralized permission management.
- **Theming**: Managed globally with `pywal16` for base16 themes extracted from the wallpaper, while cursors, icons, and fonts are controlled via configuration files in `~/.config/theme/`.

### Features

- Coherent system-wide theming.
- Comprehensive support for essential utilities (Wi-Fi, Bluetooth, printers, network drives, online accounts).
- Configurations for both window managers and basic utilities, ensuring seamless integration.

### Installation

To set up NSCD, run the provided installation script on a clean Alpine Linux installation. This script configures the system to be fully functional out of the box, following NSCD's philosophy of simplicity and security.

---

Take your Linux desktop to the next level with **Not So Chill Dotfiles** – because why settle for chill when you can have control?

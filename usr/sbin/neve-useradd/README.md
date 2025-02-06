# NEVE-USERADD 1 "January 2025" "Version 0.0.1" "Neve Project Manual"

## NAME

**neve-useradd** - Create users with ZFS integration and group configurations

## SYNOPSIS

**neve-useradd** [ USERNAME ] [ OPTION ]

## DESCRIPTION

The **neve-useradd** script adds a new user to a Void Linux system and optionally creates a ZFS dataset for the user’s home directory. It supports adding the user to specific groups like ‘wheel’ and ‘libvirt’, allowing administrative or virtualization-related privileges.

The script provides the following modes:

- **-w, --wheel**: Add the user to the ‘wheel’ group for administrative privileges.
- **-v, --virtualisation**: Add the user to the ‘libvirt’ group for virtualization access.
- **-y, --yes**: Skip confirmation prompts and execute the commands directly.
- **-h, --help**: Display the help message and exit.

## OPTIONS

The following options are supported:

- **-w, --wheel**
  Add the user to the ‘wheel’ group for administrative privileges.

- **-v, --virtualisation**
  Add the user to the ‘libvirt’ group for virtualization access.

- **-y, --yes**
  Skip confirmation prompts and execute the commands directly.

- **-h, --help**
  Display usage information and exit.

## EXAMPLES

To create a user with a ZFS home directory and administrative privileges:

```bash
neve-useradd username -w
```

To create a user with access to virtualization and skip confirmation prompts:

```bash
neve-useradd username -v -y
```

To display the help message:

```bash
neve-useradd -h
```

## AUTHOR

Matteo Cavestri

## LICENSE

GNU GPL v2 or later.

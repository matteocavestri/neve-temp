# Neve Services Setup Manual

## NAME

**neve-services-setup** - Manage and configure runit services

## SYNOPSIS

**neve-services-setup** [OPTION]

## DESCRIPTION

The **neve-services-setup** script provides an interface to manage and configure services using the runit init system.

It supports the following modes:

- **`-d`, `--default`**
  Apply the default service setup.

- **`-g`, `--gui-desktop`**
  Enable GUI desktop-related services.

- **`-v`, `--virtualisation`**
  Enable virtualisation-related services.

- **`-y`, `--yes`**
  Skip prompts (works with `--default`, `--gui-desktop`, `--virtualisation`).

- **`-h`, `--help`**
  Show the help message and exit.

## OPTIONS

The following options are supported:

- **`-d`, `--default`**
  Apply the default service setup.

- **`-g`, `--gui-desktop`**
  Enable GUI desktop-related services.

- **`-v`, `--virtualisation`**
  Enable virtualisation-related services.

- **`-y`, `--yes`**
  Skip prompts in applicable modes.

- **`-h`, `--help`**
  Display usage information.

## EXAMPLES

To apply the default services:

```bash
neve-services-setup -d
```

To enable both GUI and virtualisation services without confirmation:

```bash
neve-services-setup -g -v -y
```

## AUTHOR

Matteo Cavestri

## LICENSE

GNU General Public License v2 or later

# neve-userdel Manual

## NAME

**neve-userdel** - Remove users and associated ZFS datasets

## SYNOPSIS

**neve-userdel** [USERNAME] [OPTION]

## DESCRIPTION

The **neve-userdel** script removes a user from a Void Linux system and optionally deletes their ZFS dataset. It ensures the dataset is unmounted before deletion and supports dry-run and automated confirmation modes.

The script provides the following modes:

- **-d, --dry-run**  
  Simulate the removal process without making any changes. Outputs the actions that would be performed.

- **-y, --yes**  
  Skip confirmation prompts and execute the commands directly.

- **-h, --help**  
  Display the help message and exit.

## OPTIONS

The following options are supported:

- **-d, --dry-run**  
  Simulate the removal process and list the actions that would be taken without performing them.

- **-y, --yes**  
  Skip confirmation prompts and remove the user directly.

- **-h, --help**  
  Display usage information and exit.

## EXAMPLES

To remove a user and their associated ZFS dataset with confirmation:

```sh
neve-userdel username
```

To simulate the removal of a user and their dataset:

```sh
neve-userdel username -d
```

To remove a user and their dataset without confirmation prompts:

```sh
neve-userdel username -y
```

To display the help message:

```sh
neve-userdel -h
```

## AUTHOR

Matteo Cavestri

## LICENSE

GNU GPL v2 or later.

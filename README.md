# Bash Funcs

Just a basic collection of Bash Functions that can be used in any scripts.

> This project is still experimental and should be used with caution.

## How to use

There are several ways to use this project and some of them will be described below.

### In scripts

Add the following line in your scripts:

```bash
[[ -r /path/to/bash_funcs ]] && source /path/to/bash_funcs
```

### In your current Bash session

Just run the following command:

```console
$ source /path/to/bash_funcs
```

### In all your Bash sessions

Edit your `~/.bashrc` file and add the following lines:

```bash
# Load 'bash-funcs' project
[[ -r /path/to/bash_funcs ]] && source /path/to/bash_funcs
```

Once done, you can call any included functions.

## Arguments

Even if this file __MUST__ be sourced to be used, it support the following arguments:

```console
$ bash /path/to/bash_funcs -h

Usage: bash_funcs [flags] -- Collection of Bash functions

Flags:
  -h | --help		Print this message and exit
  -l | --list		Print list of included functions and exit
  -v | --version	Print file version and exit

```

> Note that there is a check included in the file that will be triggered if the 'exec' permission is being granted.

## Author

* __Jiab77__

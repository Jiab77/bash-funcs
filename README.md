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

## Author

* __Jiab77__
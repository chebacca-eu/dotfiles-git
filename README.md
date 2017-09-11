# Usage


## `.gitconfig`

### Git configuration file for global (per-user) options

You should set your name and email address in the corresponding options at this file's `user` section, and afterwards save it in your home directory.

See [Git documentation](https://git-scm.com/docs/git-config#FILES) for further info.


## `.gitignore`

### This file globally specifies files not to be tracked by Git

It should be saved in the path indicated by the `core.excludesFile` option in the `~/.gitconfig` file (e.g., in your home directory).

See [Git documentation](https://git-scm.com/docs/gitignore) for further info.


## `.gitattributes`

### This file assigns global attributes to the specified files and directories

It should be saved in the path indicated by the `core.attributesFile` option in the `~/.gitconfig` file (e.g., in your home directory).

See [Git documentation](https://git-scm.com/docs/gitattributes) for further info.

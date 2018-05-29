git-license
===========

> **DEPRECATION WARNING** --- Nowadays there are better tools for this. I can't recommend using this project anymore. Instead, check out [license](https://nishanths.github.io/license/), [legit](https://github.com/captainsafia/legit), or something else.

This is a simple shell script for adding the appropriate `LICENSE` to the root of your Git repository. The list of licenses is drawn from GitHub's [Choose a License](http://choosealicense.com/) page.

## Usage

Couldn't be much more simple. Just run the `git license` command and then the name of the license you wish to add, e.g.:

```bash
$ git license mit
```

This will add the MIT License. For a list of available licenses, simply run the `git license` command by itself.

**Note**: If there's already a `LICENSE` file in the current directory, then running `git license` will overwrite it.

## Installation

As with any custom Git command, simply add the `git-license` file to any directory in your `PATH` and make it executable (e.g. via `chmod +x`). The following should work for you:

```
$ git clone https://github.com/lucperkins/git-license
$ cd git-license
$ sudo cp git-license /usr/bin/git-license # or another dir in your PATH
$ sudo chmod +x /usr/bin/git-license # or wherever you end putting it
```

Alternatively, you can simply run the `init` script that comes with the repo:

```
sh init.sh
```

That will do all of the work for you (which isn't very much!).

At that point, you should be able to use `license` like any other Git command.

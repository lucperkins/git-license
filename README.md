git-license
===========

This is a simple shell script for adding the appropriate `LICENSE` to the root of your Git repository. The list of licenses is drawn from GitHub's [Choose a License](http://choosealicense.com/).

## Usage

Couldn't be much more simple. Just use run the `git license` command and then the name of the license you wish to add, e.g.:

```bash
$ git license mit
```

This will add the MIT License. For a list of available licenses, simply run the `git license` command by itself.

## Installation

As with any custom Git command, simply add the `git-license` file to any directory in your `PATH` and make it executable (e.g. via `chmod +x`). The following should work for you:

```
$ git clone https://github.com/lucperkins/git-license
$ cd git-license
$ cp git-license /usr/bin # or another dir in your PATH
$ sudo chmod +x /usr/bin/git-license
```

At that point, you should be able to use `license` like any other Git command.

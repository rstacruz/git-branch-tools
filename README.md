# Git branch tools
#### Macros for commonly-used Git commands

``` bash
$ git branch-delete branch [remote]    # Deletes a branch locally and remotely.
$ git branch-checkout branch [remote]  # Checks out an existing branch.
$ git branch-create branch [remote]    # Makes a new branch and sets up remote tracking.
$ git branch-list [remote]             # Lists branches in a remote.
$ git branch-track [remote]            # Sets up tracking in a remote branch.
```

All remotes default to `origin`.

## Installation

Using [ShellBundler](https://github.com/rstacruz/shellbundler):

``` bash
$ git clone git://github.com/rstacruz/git-branch-tools.git ~/.bash/bundle/git-branch-tools
$ sbundle reload
```

Otherwise, just copy `bin/*` somewhere in your path.


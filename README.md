# git-showtool

A visual git show

## Intro

`git showtool` Ease to mimic `git show` on visual diff tools. Basically this 

    $ git showtool <rev>

acts like 

    $ git difftool <rev>~ <rev>

It accepts basic options from difftool, like `-y` or `--dir-diff`
## Install

Download and symlink to your path

```bash
$ git clone git@github.com:albfan/git-showtool.git
$ cd git-showtool
$ ln -s $PWD/git-showtool ~/bin/
```

## Collaboration

Don't hesitate to submit a PR if you find something missing, like any `diff` or `difftool` option.

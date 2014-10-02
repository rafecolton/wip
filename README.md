wip
===

keeps track of your wip projects

## Design Goals

* small
* no dependencies
* just bash

## Installing

```bash
curl -sL https://raw.githubusercontent.com/rafecolton/wip/master/wip \
  -o /usr/local/bin/wip && chmod +x /usr/local/bin/wip
```

## Usage

```bash
$ wip -h

# Usage: wip <command>

# Commands:
# -h/--help  -  show this message
# ls         -  list
# add        -  add current
# rm         -  remove current
```

## Notes

* not tested on zsh

## TODO

* tests using bats and `.travis.yml`
* `add` and `rm` by name
* `clear`
* display which branch each project is on if it's a git repo

## Ideas

* keep full paths to detect conflicts

# Git Log Diff Viewer

This is a CLI tool that makes traversing diffs from the git log easier.

The end goal is to be able to run the tool and then use the arrow keys
(or other keys) to move backward and forward through the git history, viewing
the diff at each step.


## Installation

### Install Go:

1.  See `https://golang.org/doc/install`.
2.  Download: `wget https://dl.google.com/go/go1.13.7.linux-amd64.tar.gz`
3.  Extract: `sudo tar -C /usr/local -xzf go1.13.7.linux-amd64.tar.gz`
4.  Add to `PATH`: edit ~/.bashrc and add `export PATH="$PATH:/usr/local/go/bin"`

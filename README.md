# Terminal2iTerm

A Python script to convert Apple Terminal color themes into iTerm2 themes.

## Overview

This script provides a simple way to convert color themes from the native format used by the Apple Terminal *(.terminal)* into an iTerm2 compatible format *(.itermcolors)*. It is based on the  [iterm2terminal](https://github.com/mbadolato/iTerm2-Color-Schemes/blob/master/tools/iterm2terminal.py "iterm2terminal") script, providing the reverse functionality.

## Requirements

- Python 3

## Usage


```
usage: terminal2iterm.py [-h] source target

positional arguments:
  source      Location of .terminal file to convert
  target      Directory in which to save iTerm2 color scheme

options:
  -h, --help  show this help message and exit
```

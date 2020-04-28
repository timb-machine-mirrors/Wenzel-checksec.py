# checksec.py

> Checksec tool in Python. Based on LIEF

## Overview

A simple tool to verify the security properties of your binaries.

Supported formats:

- [x] `ELF`
- [ ] `PE`
- [ ] `Mach-O`

## Requirements

- `Python 3.4`
- `virtualenv`

## Setup

~~~
virtualenv -p python3 venv
source venv/bin/activate
(venv) pip install .
~~~

~~~
usage: checksec [-h] file
~~~

## References

- @apogiatzis [Gist checksec.py](https://gist.github.com/apogiatzis/fb617cd118a9882749b5cb167dae0c5d)
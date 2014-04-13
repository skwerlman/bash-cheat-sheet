# Bash Introduction
Introduction to the Unix command line. This document was inspired by André Augusto Costa Santos' **Bash Introduction** keynote. See his [slides](https://speakerdeck.com/62gerente/bash-introduction).

## Some Required Commands
| Command | Action | Options |
| ------- | ------ | ------- |
| List | `ls`   | `-a` (all files), `-l` (long format) |
| Make directory | `mkdir [OPT] DIR` | `-p` (make parents) |
| Change directory | `cd PATH` | `.` (current dir), `..` (parent dir), `~` (home dir) |
| Print working directory | `pwd` | |
| Create empty file | `touch FILE` | |
| Copy | `cp [OPT] FROM TO` | `-r` (copy directories recursively) |
| Move or rename | `mv FROM TO` | |
| Remove | `rm [OPT] FILE` | `-r` (recursively remove directories), `-f` (force) |
| Remove directory | `rmdir [OPT] DIR` | `-p` (parents) |
| Concatenate and print files | `cat [OPT] FILES` | `-l` (number the output lines) |
| View file | `less [OPT] FILE` | `-N` (number the output lines) |

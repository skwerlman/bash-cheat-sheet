# Bash Introduction
Introduction to the Unix command line. This document was inspired by André Augusto Costa Santos' **Bash Introduction** keynote. See his [slides](https://speakerdeck.com/62gerente/bash-introduction).

## Some Required Commands
| Command | Action | Options |
| ------- | ------ | ------- |
| List | `ls` | `-a` (all files), `-l` (long format) |
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

## Less Frequent Commands
| Key | Command | Key | Command |
| --- | ------- | --- | ------- |
| `Space` | Next page | `/<text>` | Forward search for `<text>` |
| `b` | Previous page | `?<text>` | Backward search for `<text>` |
| `j` | Next line | `n` | Next search match |
| `k` | Previous line | `N` | Previous search match |
| `g` | First line | `=` | File information |
| `G` | Last line | `h` | Help |
| `<n>G` | Line `<n>` | `q` | Quit |

| Command | Action | Options |
| ------- | ------ | ------- |
| Display first lines | `head [OPT] FILE` | `-n` (first `n` lines ) |
| Display last lines | `tail [OPT] FILE` | `-n` (last `n` lines) |
| Print lines matching a pattern | `grep [OPT] PATTERN [FILE...]` | `-c` (display the number of matched lines), `-i` (ignore case sensitivity), `-l` (display the filenames), `-n` (display the line numbers), `-w` (match whole word) |
| Word count | `wc [OPT] FILE` | `-l` (line count), `-c` (byte count), `-m` (character count), `-w` (word count) |

## Control Key Commands
| Command | Action |
| ------- | ------ |
| Kill process | `CTRL + C` |
| Stop process | `CTRL + Z` |
| End of file | `CTRL + D` |

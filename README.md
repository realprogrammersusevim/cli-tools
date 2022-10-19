# CLI Tools

![GitHub Repo stars](https://img.shields.io/github/stars/realprogrammersusevim/cli-tools?style=for-the-badge)
[![GitHub license](https://img.shields.io/github/license/realprogrammersusevim/cli-tools?style=for-the-badge)](https://github.com/realprogrammersusevim/cli-tools/blob/main/LICENSE)

## Description

The little scripts I've made to make my life just a little bit easier when I'm living in the command line.

## Requirements

- Bash and/or Zsh
- Python 3

## Usage

Add the directory to your path in your shell config file.

```bash
export PATH=$PATH:"/path/to/the/script/dir/"
```

If you help with a tool just run it with a `-h` flag

There are eight scripts so far.
- `ascii` is a Python script to convert a unicode text file to plain ASCII. Especially useful for those annoying little unicode quotation marks that look just like ASCII but cause all sorts of problems.
- `blocksite` adds a URL to the /etc/hosts file to stop those time sucking websites (only works on Mac and Linux)
- `dna` is a bit of code I wrote for my biology class to translate a DNA string into the corresponding RNA and amino acids
- `grading` was one of my very first CLI scripts to convert a percentage grade into a letter grade
- `l2n` converts a markdown letter list into a numeral list
- `numlines` finds the biggest file in a directory
- `password` generates a random password
- `rename` renames a directory of files in sequential order
- `sinceblock` gets the number of minutes since the last Bitcoin block (must be run from a Bitcoin node)
- `rmbadges` quickly toggles dock notification badges on macOS

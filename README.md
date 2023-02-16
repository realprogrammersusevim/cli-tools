# CLI Tools

[![GitHub Repo stars](https://img.shields.io/github/stars/realprogrammersusevim/cli-tools?style=for-the-badge)](https://github.com/realprogrammersusevim/cli-tools/stargazers)
[![GitHub license](https://img.shields.io/github/license/realprogrammersusevim/cli-tools?style=for-the-badge)](https://github.com/realprogrammersusevim/cli-tools/blob/main/LICENSE)

## Description

The little scripts I've written to make my life just a little bit easier when
I'm living in the terminal

## Requirements

- Bash
- Python 3

## Usage

Add the directory to your path in your shell config file.

```bash
export PATH=$PATH:"/path/to/the/script/dir/"
```

If you help with a tool just run it with a `-h` flag

There are eight scripts so far.

- `ascii` is a Python script to convert a unicode text file to plain ASCII.
  Especially useful for those annoying little unicode quotation marks that look
  just like ASCII but cause all sorts of problems.
- `blocksite` adds a URL to the /etc/hosts file to stop those time sucking
  websites (only works on Mac and Linux)
- `dna` is a bit of code I wrote for my biology class to translate a DNA string
  into the corresponding RNA and amino acids
- `grading` was one of my first CLI scripts to convert a percentage grade into a
  letter grade
- `l2n` converts a markdown letter list into a numeral list
- `numlines` finds the biggest file in a directory
- `password` generates a random password
- `rename` renames a directory of files in sequential order
- `sinceblock` gets the number of minutes since the last Bitcoin block (must be
  run from a Bitcoin node)
- `rmbadges` quickly toggles dock notification badges on macOS
- `diffchar` finds the number of characters that don't match between two
  strings. Helpful for checking for differences in DNA.
- `licence` prints out a specified licence
- `craft_cleanup` removes problems with the [Craft](https://craft.do) app's
  Markdown export
- `ipynb2py` converts a Jupyter notebook to a Python script
- `printer` can either print the Markdown files in a directory as plain text or
  convert them to PDFs before printing
- `verses` converts the output of
  [BibleGateway-to-Markdown](https://github.com/jgclark/BibleGateway-to-Markdown)
  to separate text files
- `quop` a tiny script to open up the QUOP game in a web browser
- `thes` gets synonyms of the word from a thesaurus

# SYNOPSIS
Search and replace text in files using PCRE-compatible regular expressions.

# DESCRIPTION
`sad` allows you to interactively search and replace text in files using
PCRE-compatible regular expressions. Often, the ergonomics of combining
`grep`/`rg`/`ag`/`your-search-tool-of-choice`, `find`, `sed`, and `xargs` can
be, well, _cumbersome_.

I got sick of all that and decided to simplify that crap for me. In the
process, I made sure that I could use real regexes, too.

# DEPENDENCIES
- [ripgrep](https://github.com/BurntSushi/ripgrep)
- [gum](https://github.com/charmbracelet/gum)
- [fzf](https://github.com/junegunn/fzf)
- [perl](https://www.perl.org/) (but surely you have perl on your system already)

# OPTIONS
- `-h`, `--help`: show help
- `-y`, `--yes`: skip confirmation prompts and auto-apply all changes
- `-d`, `--dry-run`: show what would be changed without actually changing anything

# COPYRIGHT
Copyright (c) 2025, Jeff Ober

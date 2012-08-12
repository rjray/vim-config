# Vim Config

This is a split off of my [dotfiles](https://github.com/rjray/dotfiles) repo,
for just the vim configuration.

This allows me to install the vim config in places where I might not need
the full set of dot-files, or install the dot-files on systems that don't
have vim.

### Submodules and Pathogen

Most of what I have here is in the form of plugins, which (where available) are
tracked as git submodules to this repository. I use Tim Pope's well-regarded
[Pathogen](http://github.com/tpope/vim-pathogen) to load and manage
plugins. These submodule-style plugins are under `.vim/bundle`.

### Other People's Code

Besides Pathogen and the submodules, I also have some code in `.vim/plugin`
taken from http://www.vim.org/scripts/index.php that isnot bundled up for
Pathogen usage.

### My Code

At this stage, I do not have any original code in this repo, save for the
contents of `.vimrc` (and much of that is cribbed from other sources, to be
honest).

### The `.vimrc` File

Lastly, the file `.vimrc` is here at the top-level. I may work on it some more
in the future, in an attempt to clean it up and make it more understandable.

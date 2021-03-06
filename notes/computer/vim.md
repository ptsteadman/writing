# Vim Notes

### Movement/Selection

`.` repeats the last command

`*` executes a search on the current word

`%` goes to the next brace or paren

`>aB` indents the current block

`viB` visually selects the current block

`vi{` visually selects inside the brace or paren

`vaw` deletes whitespace after word

`gv` reselects the last visual thing

`gi` go to last edited location

`C` to change remaining text on line

`dt` `dT` delete TO something

`d^` / `d0` delete back to beginning of line

 `c^` / `c0` same but then go into insert mode

 `S` delete entire line and go into insert mode

`~` toggle case

`<C-I>`, `<C-O>` rewind/forward past movements

`gf` go to file under cursor

`/\u` go to next uppercase character

### Buffer / Split Commands

`bd` buffer delete

`ls` list buffers

`sb` split all buffers

`Sex` open Explore in split

`<C-w> q` close split

### Registers

`:reg` view registers

`yy` same as `dd` but yank

### Other

`<C-N>` autocomplete

`:r!` read in the contents of a command

`:r` read in the contents of a file

`<C-r>=` and a calculation will insert value into text

### Cool Patterns

`f <space>` `r <enter>` to break on props

then `f <space> .` to repeat

In visual mode, `press g C-g` to count lines / words

### netrw

`d` to create a directory
`D` to delete
`%` to create a file
`:Rex` to close it


### Plugins

Commenting things out: Use tpope's vim-commentary and `gc`.

Unicode symbols: use unicode.vim and then `:UnicodeSearch! <name of symbol>`



### Prose editing

`setl fo+=a` automatically reflow text


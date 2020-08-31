#vim
## basic
yy -> copy
yw -> copy until end of word
y$ -> copy until end of line
y<Right> -> copy current character
y<Left> -> copy previous character
y<Up> -> copy current line and line above
y<Down> -> copy current line and line below 

p -> paste

dd -> copy and delete line
dw -> copy and delete until end of word
d$ -> copy and delete until end of line
d<Right> -> copy and delete current character
d<Left> -> copy and delete previous character
d<Up> -> copy and delete current line and line above
d<Down> -> copy and delete current line and line below 

. -> repeat last action

## custom
<C-Up> -> move line up
<C-Down> -> move line down

## Commentary.vim
gcc -> comment (out) line
:7,17Commentary -> comment out line 7 to 17 

## Surround.vim
cs"' -> change surrounding from " to '
ds` -> delete surounding `
yss( -> add surrounding ( around the line
ysw{ -> add surrounding { around the word

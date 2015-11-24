zsh-syntax-highlighting / highlighters / line
---------------------------------------------

This is the `line` highlighter, that highlights the whole line.


### How to tweak it

This highlighter defines the following styles:

* `line` - the style for the whole line

To override one of those styles, change its entry in `ZSH_HIGHLIGHT_STYLES`,
for example in `~/.zshrc`:

    ZSH_HIGHLIGHT_STYLES[line]='bold'

The syntax for declaring styles is documented in [the `zshzle(1)` manual
page](http://zsh.sourceforge.net/Doc/Release/Zsh-Line-Editor.html#SEC135).
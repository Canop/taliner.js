
# Why ?

Find if the caret is on the first line or on the last line of a textarea isn't easy. More details on why it's hard in [this StackOverflow question](http://stackoverflow.com/q/24605280/263525).

If you need this precise information, then this plugin might be handy.

**[Demonstration](http://dystroy.org/demos/taliner/demo.html)**


# How to use it ?

`$('#yourTextarea').taliner()` returns an object with three properties :

- caretOnFirstLine : a boolean telling if the caret is on the first line of the textarea.
- caretOnLastLine : a boolean too. Guess what it is.
- linesNumber : the total number of lines of text of the textarea.

# Does it really always work ?

Almost.

If a line ends with a space because of word wrapping and you click right to that line, you'll end to a position undistinguishable from the start of the following line.

I don't see any fix for that right now. if you have one, please contribute.

# License 

Public Domain. Use as you wish and at your own risk.

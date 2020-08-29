Commands that I think useful for me:

Cheetsheet - http://tnerual.eriogerg.free.fr/vimqrc.html

    Normal mode, insert mode, visual mode
    ctrl + d (or) tab to command completion

    hjkl - to move around
    x -  to delete a char
    a - append text next to cursor
    A - Append text to the end of line
    I - Insert at the beginning

    $ - End of the line
    0 - Start of the line
    . - Repeat the last command you did

    operators & motion

    operator:
    	d - delete
    	c - change
    	y - yank
    motion:
    	w - word
    	e - end of current word
    	$ - end of the line
    	d - delete whole line

    operator motion - ex: dw, d$, dd, de, cc, yy
    operator number motion - d2w
    count operator motion - 2dd
    count motion - ex: 2w, 3e

    NOTE: motion can be used without an operator, it just moves the cursor.

    u - undo last command
    U - to fix the whole line
    ctrl + r - redo(undo the undos)
    p - put or paste
    r - replace a char
    ctrl + g - cursor location status

    gg - move to top of a file
    G - move to bottom of file
    / - search, n to next, N to prev
    ? - backword search same as /

    % - matching parentheses
    ctrl + o - last cursor position
    ctrl + i - forward cursor position

    :s/old/new - substitue in a line, only first occurence
    :s/old/new/g - substitue all occurrence in a line
    %s/old/new/g - substitue in whole "FILE"
    %s/old/new/gc - substitue in whole "FILE" with conformation prompt

    :!ls - :!external command
    o - open a line below
    O - open a line above

    * - search next occurence of the word under cursor
    ^ - go to the first non blank character
    b - back one word

    ~ - tilde case under the cursor
    J - Join lines

In current window:

    H: move to the top of the screen
    M: move to the middle of the screen
    L: move to the bottom of the screen

Scroll up and down:
ctrl+u - Scroll page up
ctrl+d - Scroll page down

Text Objects: (Most powerfull of all)
t", tanything - jump up to a character
f", fanything - jump onto a character
iw - inner word
aw - around word
i", ianything - Inner quotes
words: iw and aw
sentences: is and as
paragraphs: ip and ap
single quotes: i' and a'
double quotes: i" and a"
back ticks: i`and a`
parenthesis: i( and a(
brackets: i[ and a[
braces: i{ and a{
tags: it and at

    /text\c => \c is case insensive search

Visual mode:

    character-based: v
    line-based: V
    block-based: Ctrl-v

Macros:

    qa: start recording a macro named "a"
    q: stop recording
    @a: play back the macro

Multi-cursor ways:
ctrl+v, select things, shift+i, add stuff, double esc

Window:

    Ctrl+W +/-: increase/decrease height (ex. 20<C-w>+)
    Ctrl+W >/<: increase/decrease width (ex. 30<C-w><)
    Ctrl+W _: set height (ex. 50<C-w>_)
    Ctrl+W |: set width (ex. 50<C-w>|)
    Ctrl+W =: equalize width and height of all windows

Tabs:

    gt: move to tab next
    gT: move to tab previous

# Personal

## Patterns
`[count][operator]{motion}`

## Essential Navigation Commands

![](./img/directions.png)

`Ctrl-f` - Move down one page.<br>
`Ctrl-b` - Move back up one page.<br>
`w` - Move forward by word including punc.<br>
`W` - Move forward by word not including punc.<br>
`b` - Move backward by word incluing punc.<br>
`B` - Move backward by word not including punc.<br>
`gg` - First line.<br>
`G` - Last line.<br>
`^` | `0` - Beginning of line.<br>
`$` - End of line.<br>
`{line number}gg` - Go to line.<br>
`{line number}G` - Go to line.<br>
`:{line number}` - Go to line.<br>
`:$` - Go to last line.<br>

## Deleting Text

`x` - Delete character.<br>
`X` - Delete character backwards.<br>
`d$` - Delete to end of line.<br>
`D` - Delete to end of line.<br>
`dw` - Delete word (end of word) not including punc.<br>
`dW` - Delete word (end of word) including punc.<br>
`db` - Delete word backwards (beginning of word) not including punc.<br>
`dB` - Delete word backwards (beginning of word) including punc.<br>
`d{count}w` | `d{count}W` - Delete multiple words.<br>
`dd` - Delete line.<br>
`{count}dd` - Delete multiple lines.<br>

## Cut, Copy, and Paste
`p` - Paste line below.<br>
`P` - Paste line above.<br>
`yy` - Yank line into default register.<br>
`y{count}W` - Yank multiple words.<br>
`"{number}p` - Paste from numbered register.<br>
`{letter}yy` - Yank to number register.<br>
`u` - Undo.<br>
'Ctrl-r` - Redo.<br>

## Notes
* Using the delete function will put expression in the temp registry. Usually the "".
* Yanking will save to the "0 register.
* `:reg {letter}` - Show register input.

## Misc
`Ctrl-G` - Display file info.<br>
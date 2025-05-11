`.`: repeat the previous change.

## delete
`x`: delete the single character where the cursor is positioned.
`dd`: delete the entire line where the cursor is located.

`s`: substitute the character under the cursor with new text.(`cl`)
`S`: delete the current line and enter Insert mode to create a new line.(`cc`)

## indent
`>G`: indent all lines from the cursor to the end of the file.

## cursor move
`h`: move the cursor left by one character.
`j`: move the cursor down one line.
`k`: move the cursor up one line.
`l`: move the cursor right by one character.
`^`: move the cursor to the start of the current line.
`$`: move the cursor to the end of the current line.

`I`: enter Insert mode and insert text at the beginning of the current line.

`a`: enter Insert mode and append text after the cursor position.
`A`: enter Insert mode and append text at the end of the current line.(`$a`)

`c`: change text from the cursor position to the end of the specified range (can be followed by a movement command, such as `w`, `e`, or `$`).
`C`: change text from the cursor position to the end of the current line.(`c$`)

`o`: open a new line below the current line and enter Insert mode.
`O`: open a new line above the current line and enter Insert mode.

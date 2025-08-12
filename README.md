<p align="center">
<img src="file.svg" alt = "bash" width="200px"></p>

## Table of Contents
  1. [Basic Commands](#1-basic-commands)

# 1. Basic Commands
## a. `echo`
Display the line of text
```bash
echo Hello World
```

```
Hello World
```
## b. `Vim`
Used to create a new file 
```bash
vim text.txt
```
It will immediately open the file. Consider the following :
<br>

####  <u>Entering the Insert mode</u>
`i`: Insert text at the current cursor position.<br>
`a`: Append text after the current cursor position.<br>
`I`: Insert text at the beginning of the current line.<br>
`A`: Append text at the end of the current line.<br>

#### <u>Exiting the Insert mode </u>
 Press `Esc` to return to normal mode

#### <u>Saving and quiting the file</u> (from normal mode)
`:w`: Save the file.<br>
`:q`: Quit Vim (if no unsaved changes).<br>
`:wq`: Save and quit.<br>
`:q!`: Quit without saving (discarding changes).<br>

## c. `cat`
Display the text of the file (.txt) in the temianal
```bash
cat text.txt
```


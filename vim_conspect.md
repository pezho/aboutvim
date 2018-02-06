# VI[M] CHEATSHEET

## Moving
### Screen
`^F` - Прокрутить вперед на один экран

`^B` - Прокрутить назад на один экран

`^D` - Прокрутить вперед (вниз) на полэкрана

`^U` - Прокрутить назад (вверх) на полэкрана

*`^L` - Перересовать экран*

`^ -- CTRL`

**Moving inside screen**


`H` - Move to the top of screen

`M` - Move to the middle

`L` - Move to the bottom

### Other moving
`^` - move to the first non space charecter in current line

`n|' - move to the *n* row in current line

`e` - move to the end of world

`E` - move to the end of world (ignore punctuations)

`(` - move to the start of current string

`)` - move to the end of current string


`{` - move to the start of current paragraph

`}` - move to the end of current paragraph


`mx` - Выставляет метку *x* в текущую позицию курсора

`'x` - Перемещат курсор на строку помеченную *x*

`\`x` - Перемещат символ на строку помеченную *x*

`/, ?` - searching

`fx` - go to the next mathing of 'x' in this line

`tx' - go to the charecter that following next `x`

`^G` - information about current line

## Open vi with some options
`$ vi +n file` - open vi in n line

`$ vim + file` - open vim in the last line

`$ +/pattern file` - open *file* in the first searching *pattern*


`$ vim -R file` - Only read mod

`$ vim -r file` - Востанавливает *file* после збоя

`$ `


## Use the buffer
`1pu.u.u etc.` - paste text from the buffer [one of much]

`"dyy` - copy current line in buffer named *d*

`"a7yy` - copy next seven lines in buffer named *a*

`"ap` - paste value of buffer a after cursor.


## Ex commands

| Full name | Short name | Value |
| --------- | ---------- | ----- |
| delete | d | delete lines |
| move | m | move lines |
| copy | co | copy line |
|  | t | smae thing as co |






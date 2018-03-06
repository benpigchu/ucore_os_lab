# Tips on lab1

- This is not a makefile course, you do not need to read every macro.

- Seems that gdb has some issue on `$pc` of real mode.

- For challenge task, you should know what `int` and `iret` actually do. There are a `pushl $esp` and a `popl $esp` in `trapentry.S`, which should be useful.
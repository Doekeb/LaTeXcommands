# LaTeXcommands
LaTeXcommands is a command cleanup utility for LaTeX.

## Usage
```
LaTeXcommands [-h] [-c] [-u] [-l] filename

positional arguments:
  filename         Name of the main .tex file

optional arguments:
  -h, --help       show this help message and exit
  -c, --count      count the number of occurences of each command instead of
                   generating a list of unused commands (this is most useful
                   in conjunction with '--used') (default: False)
  -u, --used       display a list of the used commands instead of the unused
                   commands (default: False)
  -l, --lines_off  suppress the display of line numbers on which the commands
                   are defined (default: False)
```

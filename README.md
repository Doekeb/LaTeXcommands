# LaTeXcommands
LaTeXcommands is a command cleanup utility for LaTeX.

## Usage
```
LaTeXcommands [-h] [-c] [-d {used,unused,all}] [-l] filename

positional arguments:
  filename              Name of the main .tex file

optional arguments:
  -h, --help            show this help message and exit
  -c, --count           count the number of occurences of each command instead
                        of generating a list of unused commands (this is most
                        useful in conjunction with '--display') (default:
                        False)
  -d {used,unused,all}, --display {used,unused,all}
                        which commands will be displayed (default: unused)
  -l, --lines_off       suppress the display of line numbers on which the
                        commands are defined (default: False)
```

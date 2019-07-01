# LaTeXcommands
LaTeXcommands is a command cleanup utility for LaTeX.

## Dependencies and Installation
1. Install regex (https://pypi.org/project/regex/) with `pip install regex`
2. Download the file LaTeXcommands and save it somewhere in your `$PATH`.
3. You may need to make `LaTeXcommands` executable by doing `chmod 755 LaTeXcommands`.

## Usage
```
LaTeXcommands [-h] [-s styfile] [-c] [-d {used,unused,all}] [-l]
                     filename

positional arguments:
  filename              Name of the main .tex file

optional arguments:
  -h, --help            show this help message and exit
  -s styfile, --sty styfile
                        find commands in the provided .sty file instead of the
                        main .tex file (count occurences in both .sty and .tex
                        files)
  -c, --count           count the number of occurences of each command instead
                        of generating a list of unused commands (this is most
                        useful in conjunction with '-d all' or '-d used')
                        (default: False)
  -d {used,unused,all}, --display {used,unused,all}
                        which commands will be displayed (default: unused)
  -l, --lines_off       suppress the display of line numbers on which the
                        commands are defined (default: False)
```

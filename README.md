# pcat
this script like cat and more options

# Informations: 
    Version: 1.3.6
    python_version: 3.7.5
    system: KUbuntu/linux
    
## Examples:
    1- pcat foo.txt -c g                    # output green color
    2- pcat foo.txt -c g -s bold            # output green color with bold font
    3- pcat foo.txt -c g -t bg/co           # output green background color

    4- pcat foo.txt -g field/"field"        # output grep/find of filed word in file
    5- pcat foo.txt -g field/"field" -gc y  # output grep/find of filed word in file with yellow color default color is red
    
    6- pcat foo.txt -n 10                   # output 10 number of file
    
    7- pcat foo.txt -ln                     # output show line number
    8- pcat foo.txt -ln -fs "- "            # output show line number with suffix "-": like this (1- <text>)
    9- pcat foo.txt -ln -fs "- " -bs "│"    # output show line number with before suffix "│": like this (|1- <text>)
    10- pcat foo.txt -ef                     # output write text by slow
    11- pcat foo.txt -et 0.07                # output write text by slow with float time default time is 0.03

## new Options: 
    1- pcat foo.txt -gr "d" -gc y
    2- pcat foo.txt -gr "dark" -gc g
    3- pcat foo.txt -gr "no" -gc w
    
## Help Option:
    
    $ pcat --help
    
    Usage: pcat [OPTIONS] FILE

      Concatenate FILE(s) to standard output

    Options:
      -e, --end TEXT            coustem end line
      -c, --color TEXT          print all text from file with color [g=green,
                                y=yellow, ...]
      -n, --line TEXT           select number line for print
      -g, --grep TEXT           grep any word with color and complit read for
                                output
      -gr, --grep-no TEXT       grep any word with color but not complit read
                                output
      -gc, --gcolor TEXT        select grep color
      -bs, --befor_suffix TEXT  show befor_suffix for number or text
      -fs, --after_suffix TEXT  show after_suffix for number or text
      -t, --type TEXT           coustem type a text [write, color, background]
      -s, --style TEXT          coustem style a text
      -ln, --show-line          show line number or not show space in file
                                [ln=show_line, ns=not_space]
      -hs, --hide-space         Hide any space in output
      -lc, --line-color TEXT    select line color
      -ef, --effect             this option for write text in termainal write
                                animate.
      -et, --effect-time FLOAT  select spead for write.
      -v, --version             Show the version and exit.
      -h, --help                Show this message and exit.
      

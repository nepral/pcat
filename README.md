# pcat
this script like cat and more options

"""
this is pcat tutorial:

pcat <file_path> [options]

Examples:
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
   10- pcat foo.txt -et 0.07                # output write text by slow with float time default time is 0.03
"""

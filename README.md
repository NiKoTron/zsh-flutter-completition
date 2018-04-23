# It's flutter.io completitions for zsh

I love develop with flutter.io, but instead using IDE tools I prefer develop with cli tools, in this reason i created this completitions for my favorite shell, i heard about Mac guys that they like ZSH to. well, I hope you try this, bros.

This script based on output of `$flutter help` command for each flutter's subcommands.

## Installation

You can simply add path where you store the script to you `$fpath` variable in to you `~./zshrc`

        fpath=(/path/where/your/script/stored $fpath)

_* Note_ `fpath` declaration must be somewhere before these lines 
        
        plugins=(...)
        autoload -U compinit && compinit
        
## Licensing

This script under MIT License full license can be found in [`LICENSE`](./LICENSE) file

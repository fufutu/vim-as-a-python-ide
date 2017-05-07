# Vim as a Python IDE

Video: https://www.youtube.com/watch?v=YhqsjUUHj6g  
Slides: https://speakerdeck.com/u/mbrochh/p/vim-as-a-python-ide  

If you want to start using Vim for the first time, have a look at the
``.vimrc`` file in this repository and gradually uncomment everything.

Then install the plugins mentionned at the bottom of the file and you should
be good to go.

Please note that I am no longer using the [python-mode](https://github.com/klen/python-mode)
plugin. Instead I am now using the [jedi-vim](https://github.com/davidhalter/jedi-vim/)
plugin, which I find a bit easier to configure and it seems to have better
auto-completion features.
and I find if you want to use auto-completion by tab, you must install supertab

you need:
```
cd bundle
sh git.sh
```

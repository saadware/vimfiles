This is my ~/vimfiles dir and _this_, dear reader, is a horse:

                   ,
                  / \,,_  .'|
               ,{{| /}}}}/_.'
              }}}}` '{{'  '.
            {{{{{    _   ;, \
         ,}}}}}}    /o`\  ` ;)
        {{{{{{   /           (
        }}}}}}   |            \
       {{{{{{{{   \            \          ,-------------------------------.
       }}}}}}}}}   '.__      _  |        /       HI                        \
       {{{{{{{{       /`._  (_\ /       /      /   \                        |
        }}}}}}'      |    //___/   --= <   VVVI     HI-HI-HI                |
    jgs `{{{{`       |     '--'         \                   \               |
         }}}`                            \                  HIM-HIM-HIM!!!  /
                                          '--------------------------------'

Installation on a Windows environment
============

Clone the repo:
`git clone https://github.com/saadware/vimfiles.git`

Grab the plugin submodules:
`cd ~/vimfiles && git submodule init && git submodule update`

Make sure vim finds the vimrc file creating link from within your home directory.
`mklink /h _vimrc c:\users\me\vimfiles\vimrc`


Installation on *unix like environment
============

Clone the repo:
`git clone https://github.com/saadware/vimfiles.git ~/.vim`

Grab the plugin submodules:
`cd ~/.vim && git submodule init && git submodule update`

Make sure vim finds the vimrc file by symlinking it:
`ln -s ~/.vim/vimrc ~/.vimrc`

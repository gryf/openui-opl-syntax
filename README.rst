Open-UI OPL syntax
==================

This is a syntax file, which I was created back than in 2011 for a most
probably dead language for user interface called Open-UI for Windows. Interface
have to be written in Pascal-alike language called OPL. Syntax highlight is for
this specific language.

This repository is just for a proof, that it is fairly easy to prepare syntax
highlighting for an exotic language.

Installation
------------

To install it, any kind of Vim package manager can be used, like NeoBundle_,
Pathogen_, Vundle_ or vim-plug_.

For manual installation, copy subdirectories from this repository to your
``~/.vim`` directory. Your ``.opl`` files should now have proper syntax
highlighting. You can check it by opening any ``.opl`` file, and see its file
type under vim in *ex* mode:

.. code:: vim

   :set ft
   "a message should appear:
     filetype=openui-opl

License
-------

This work is licensed on 3-clause BSD license. See LICENSE file for details.

.. _Pathogen: https://github.com/tpope/vim-pathogen
.. _Vundle: https://github.com/gmarik/Vundle.vim
.. _NeoBundle: https://github.com/Shougo/neobundle.vim
.. _vim-plug: https://github.com/junegunn/vim-plug

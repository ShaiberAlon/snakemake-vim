This has been copied from here: https://bitbucket.org/snakemake/snakemake/src/d6c26a3dd6a55d4912844d1d699f258089a4e516/misc/vim/?at=master

A few changes have been added by Alon Shaiber

A vim syntax highlighting definition for Snakemake.
You can copy the `snakemake.vim` file to `$HOME/.vim/syntax` directory and add

    au BufNewFile,BufRead Snakefile set syntax=snakemake
    au BufNewFile,BufRead *.rules set syntax=snakemake
    au BufNewFile,BufRead *.snakefile set syntax=snakemake
    au BufNewFile,BufRead *.snake set syntax=snakemake

to your `$HOME/.vimrc` file. Highlighting can be forced in a vim session with `:set syntax=snakemake`.

To install via Vundle use:

    Plugin 'https://bitbucket.org/johanneskoester/snakemake.git', {'rtp': 'misc/vim/'}

Copyright (c) 2016 Johannes Köster johannes.koester@tu-dortmund.de
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# generation cv avec shading
telechargez shading.zip\
Mac:\n
$ mkdir -p ~/Library/texmf/tex/latex/\n
$ cd ~/Library/texmf/tex/latex/\n
mettez shading.zip dans tex/latex\n
$ tar -C ~/Library/texmf/tex/latex/ -xvf shading.zip\n
$ latex cvFR.tex\n
$ dvips -Ppdf -t letter cvFR.dvi\n
$ ps2pdf cvFR.ps\n

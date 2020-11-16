# generation cv avec shading
telechargez shading.zip\
Mac:\
$ mkdir -p ~/Library/texmf/tex/latex/\
$ cd ~/Library/texmf/tex/latex/\
mettez shading.zip dans tex/latex\
$ tar -C ~/Library/texmf/tex/latex/ -xvf shading.zip\
$ latex cvFR.tex\
$ dvips -Ppdf -t letter cvFR.dvi\
$ ps2pdf cvFR.ps\

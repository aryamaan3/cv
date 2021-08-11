# generation cv avec shading
telechargez shading.zip\
Mac:

```
$ mkdir -p ~/Library/texmf/tex/latex/
```
```
$ cd ~/Library/texmf/tex/latex/
```
mettez shading.zip dans tex/latex

```
$ tar -C ~/Library/texmf/tex/latex/ -xvf shading.zip
```
```
$ latex resume.tex
```
```
$ dvips -Ppdf -t letter resume.dvi
```
```
$ ps2pdf resume.ps
```

template de http://www.davidgrant.ca/latex_resume_template

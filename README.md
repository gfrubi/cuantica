# cuantica
Apuntes de Mecánica Cuántica Relativista y cuantización del campo electromagnético.

Este apunte usa el paquete FeynMF/FeynMP para crear diagramas de Feynman en LaTeX, desarrollado por Thorsten Ohl disponible en [https://ctan.org/pkg/feynmf].

Note que la primera vez que se compila el archivo principal (con 'pdflatex cuantica.tex'), el paquete FeynMF crea los archivos 'd*.mp', que luego deben ser procesados con

> mpost d1
> mpost d2
> mpost d3

etc. Esto genera los archivos 'd*.1' con las imágenes de cada diagrama. Estas imágenes son entonces incluidas en el pdf final al compilar nuevamente ('pdflatex cuantica.tex').

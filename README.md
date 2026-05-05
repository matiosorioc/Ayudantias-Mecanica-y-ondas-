# Ayudantias-Mecanica-y-ondas-

Ayudantias de Mecanica y Ondas.

## PDFs

- [Ayudantia 4](build/Ayudantia-4.pdf)
- [Ayudantia 5](build/Ayudantia-5.pdf)
- [Ayudantia 6](build/Ayudantia-6.pdf)
- [Ayudantia 7](build/Ayudantia-7.pdf)

## Como agregar un PDF al README

1. Compila el archivo .tex:

	latexmk -pdf -interaction=nonstopmode -file-line-error -outdir=build Ayudantia-X.tex

2. Si quieres tener una copia en la raiz del repo:

	Copy-Item build\Ayudantia-X.pdf Ayudantia-X.pdf -Force

3. Agrega el enlace en la seccion PDFs del README con este formato:

	- [Ayudantia X](build/Ayudantia-X.pdf)

4. Guarda, haz commit y push.

## Plantilla rapida para la proxima


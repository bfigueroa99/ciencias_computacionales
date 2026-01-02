# Proyecto de Libro de Estudio de Programación

Este repositorio contiene el código fuente LaTeX para un libro de estudio personal sobre lenguajes de programación y ciencias de la computación.

## Estructura del Proyecto

- `main.tex`: Archivo principal que compila todo el libro.
- `chapters/`: Carpeta que contiene los archivos `.tex` para cada capítulo.
  - `introduction.tex`: Introducción al libro.
  - `python.tex`: Notas y código sobre Python.
  - `javascript.tex`: Notas y código sobre JavaScript.
  - `cs_concepts.tex`: Algoritmos y estructuras de datos.
- `python/`: Carpeta para guardar scripts de Python de prueba (opcional).
- `javascript/`: Carpeta para guardar scripts de JS de prueba (opcional).

## Cómo compilar

Necesitarás una distribución de LaTeX instalada (como TeX Live o MiKTeX).

Puedes compilar el libro usando el siguiente comando en tu terminal:

```bash
pdflatex main.tex
```

Es posible que necesites ejecutar el comando dos veces para que se genere correctamente la tabla de contenidos.

## Cómo contribuir

1. Abre el archivo del capítulo que quieras editar en la carpeta `chapters/`.
2. Agrega tus notas usando sintaxis LaTeX.
3. Para agregar código, usa el entorno `lstlisting`:

```latex
\begin{lstlisting}[language=Python]
print("Tu código aquí")
\end{lstlisting}
```

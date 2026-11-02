# Machine Learning con PyTorch y scikit-learn

Repositorio de estudio basado en el libro *Machine Learning con PyTorch y scikit-learn*.

## Objetivo

Documentar y resumir los conceptos más importantes de cada capítulo mediante notebooks, para contar con una referencia práctica y reutilizable más adelante.

## Estructura

- Una notebook por capítulo del libro.
- Cada notebook reúne los apuntes y ejemplos que considere relevantes.
- El contenido se irá ampliando y refinando con el tiempo.

## Estado

En construcción.

## Abrir los capítulos en Positron

Los archivos `.qmd` son documentos Quarto. Para ejecutar los bloques de Python
de `capitulo_2.qmd`, crea un entorno en la raíz del repositorio e instala sus
dependencias:

```bash
uv venv .venv
uv pip install --python .venv/bin/python -r requirements.txt
```

En Positron, abre la **carpeta** del repositorio, abre el `.qmd` y selecciona
`.venv/bin/python` como intérprete/kernel de Python. La extensión de Quarto
puede usar el Quarto incluido con Positron; R se configura por separado.

Para comprobar la renderización desde la terminal (con `quarto` disponible en
el `PATH`):

```bash
QUARTO_PYTHON="$PWD/.venv/bin/python" quarto render capitulo_2.qmd --to html
```

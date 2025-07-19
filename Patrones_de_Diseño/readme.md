# Cómo generar la versión PDF del libro de Patrones de Diseño

## Requisitos

- [Quarto](https://quarto.org/docs/get-started/) instalado (versión 1.7 o superior)
- [LaTeX](https://quarto.org/docs/publishing/latex/) instalado para exportar a PDF

## Pasos

1. Abre una terminal y navega al directorio del libro:

    ```sh
    cd "patrones-de-diseño"
    ```

2. Ejecuta el siguiente comando para generar el PDF:

    ```sh
    quarto render --to pdf
    ```

    El archivo PDF se guardará en la carpeta `_book/` como `Investigación-sobre-Patrones-de-Diseño.pdf`.

## Notas

- Si tienes problemas con la exportación a PDF, revisa la instalación de LaTeX.
- Puedes personalizar el formato en el archivo [`_quarto.yml`](./_quarto.yml).

## Recursos

- [Documentación oficial de Quarto Books](https://quarto.org/docs/books/)
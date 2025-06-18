

<!-- README.md se genera a partir de README.qmd. Por favor, edite ese archivo -->

# Plantillas no oficiales para presentaciones en la UMNG

En este repositorio podrá encontrar plantillas no oficiales para
presentaciones en la [Universidad Militar Nueva Granada
(UMNG)](https://www.umng.edu.co/inicio) que cumplen con el [Manual de
Identidad Visual](https://www.umng.edu.co/la-universidad/identidad) de
la UMNG, utilizando [Quarto](https://quarto.org/).

## Creación de una nueva presentación

``` bash
quarto use template luifrancgom/presentation-umng 
```

Esto comando instalará la extensión y creará un archivo `template.qmd`
de ejemplo que puede utilizar como punto de partida para crear la
presentación.

## Instalación para un documento o projecto existente

También puede utilizar este formato con un proyecto o documento de
Quarto existente. Desde el directorio del proyecto o documento de
Quarto, ejecute el siguiente comando para instalar este formato:

``` bash
quarto install extension luifrancgom/presentation-umng
```

## Ejemplos

- **Revealjs**: [Demo]() ([Código]())

## Agradecimientos

### Revealjs

- Varias ideas se obtuvieron de los repositorios

  - [Monash Quarto Templates](https://github.com/quarto-monash)
  - [Coatless Quarto](https://github.com/coatless-quarto)

- De la comunidad de Quarto y en particular de [Reveal.js Presentation:
  Title slide without page number and
  logo](https://github.com/quarto-dev/quarto-cli/discussions/557)

# HTML - CSS básico

## Descripción

Este repositorio incluye tres páginas básicas de la web de [Salitre Mágico](https://www.salitremagico.com.co) siendo:

* [Básica](https://github.com/norbeydanilo/html-css-basic/tree/main/html-basic-salitre-magico): esqueleto html sin css.
* [Básica con estilos](https://github.com/norbeydanilo/html-css-basic/tree/main/html-css-basic-salitre-magico): esqueleto html con hoja de estilos css.
* [Básica con Bootstrap](https://github.com/norbeydanilo/html-css-basic/tree/main/html-css-bootstrap-salitre-magico): html con estilos y bootstrap para carrusel.

## Instalación de Bootstrap

Hay varias formas de comenzar a usar Bootstrap en tu propio sitio web. Puedes:

1. **Descargar Bootstrap**
   - Si deseas descargar y alojar Bootstrap tú mismo, ve a getbootstrap.com, y sigue las instrucciones allí.
   - También puedes clonar el repositorio: `git clone https://github.com/twbs/bootstrap.git`

2. **Incluir Bootstrap desde un CDN**
   - Si no deseas descargar y alojar Bootstrap tú mismo, puedes incluirlo desde un CDN (Content Delivery Network).
   - MaxCDN proporciona soporte CDN para CSS y JavaScript de Bootstrap. También debes incluir jQuery.

3. **Instalar con npm**: `npm install bootstrap@v5.3.2`
4. **Instalar con yarn**: `yarn add bootstrap@v5.3.2`
5. **Instalar con Composer**: `composer require twbs/bootstrap:5.3.2`
6. **Instalar con NuGet**: CSS: `Install-Package bootstrap`, Sass: `Install-Package bootstrap.sass`

## Uso de Bootstrap

Una vez que hayas instalado Bootstrap, puedes comenzar a usar sus clases y componentes en tu proyecto. Aquí tienes un ejemplo de cómo se vería una página básica con Bootstrap:

```html
<!doctype html>
<html lang="en">
<head>
  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

  <title>Hello, world!</title>
</head>
<body>
  <h1>Hello, world!</h1>

  <!-- Optional JavaScript -->
  <!-- jQuery first, then Popper.js, then Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.14.7/dist/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
</body>
</html>

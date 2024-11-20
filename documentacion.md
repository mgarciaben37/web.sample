# ARIA

ARIA. sin que tu digas nada a este elemento se le va a añadir implícitamente el rol de button. https://developer.mozilla.org/es/docs/Web/Accessibility/ARIA

Por ejemplo header permite roles de grupo, presentación o ninguno.

# Estructura

```html
<head></head>
<body>

  <header></header> <!--Contiene el encabezado principal del sitio, generalmente el logotipo y el título.-->

  <nav></nav><!--Barra de navegación con enlaces internos.-->

  <main><!--Contenedor principal del contenido del sitio.-->
    <section><!--Bloques de contenido relacionados.-->
      <article><!--Secciones dentro de una sección, usadas para contenido independiente.-->
    <aside></aside><!--Información relacionada o complementaria, como enlaces o widgets.-->
  </main>
  <footer></footer><!--Información al pie de la página, como derechos de autor o enlaces legales.-->

 </body> 
 ```
# Delicius Bites Website

Este es el código fuente del sitio web Delicius Bites, que presenta un menú de comidas, bebidas, postres y detalles de contacto.

## Funcionamiento de CSS Grid

CSS Grid es un sistema de diseño bidimensional que permite organizar y distribuir elementos en filas y columnas. En este proyecto, se ha utilizado CSS Grid para estructurar el diseño de la página principal. A continuación, se describen las áreas clave de la página:

- **header:** La sección del encabezado con el nombre del restaurante y la barra de navegación.
- **main:** Contiene las secciones de menú y contacto.
  - **menu:** Utiliza Grid para organizar las secciones de comidas, bebidas y postres.
  - **contacto:** Contiene la información de contacto.

Este diseño proporciona una estructura clara y flexible para organizar el contenido de la página de manera efectiva.

## Bonus
### Funcionamiento de las Variables en CSS

Las variables CSS, también conocidas como custom properties, permiten almacenar valores que se pueden reutilizar en todo el archivo CSS. En este proyecto, se han utilizado variables para definir colores y estilos clave de manera centralizada. Aquí están algunas variables utilizadas:

- `--primary`: Color principal utilizado en el encabezado.
- `--background-color`: Color de fondo general para las secciones.
- `--color-card`: Color de fondo de las tarjetas de menú.
- `--color-card-text`: Color del texto dentro de las tarjetas.


### Variables en CSS (Bonus)

Las variables en CSS son una característica poderosa que permite almacenar valores para su reutilización. En este proyecto, las variables han sido utilizadas para definir colores y estilos clave. Algunas consideraciones importantes:

- **Ventajas:**
  - Mantenimiento sencillo: Cambiar el valor de una variable actualiza automáticamente todos los lugares donde se utiliza.
  - Consistencia: Facilita la consistencia en el diseño al utilizar valores centralizados.

- **Cómo se utilizan:**
  - Las variables se definen en `:root` al comienzo del archivo CSS.
  - Se accede a ellas utilizando la función `var()`.

```css
:root {
    --primary: #888081;
    --background-color: #03071e;
    --color-card: #ebe8e8;
    /* ...otras variables... */
}

body {
    background-color: var(--background-color);
    color: var(--color-text);
}

```
## Documentación para repaso :
1. Documentación de CSS Grid:
    - [MDN Web Docs - CSS Grid Layout](https://developer.mozilla.org/es/docs/Web/CSS/CSS_grid_layout)
        - La documentación en MDN es una fuente completa y confiable para aprender sobre CSS Grid. Incluye tutoriales, ejemplos y descripciones detalladas de propiedades.

2. grid-template-areas:

  -  [MDN Web Docs - grid-template-areas](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas)
        - Aquí encontrarás información detallada sobre cómo utilizar grid-template-areas para definir áreas en un diseño de cuadrícula.

3. grid-template-columns:

    - [MDN Web Docs - grid-template-columns](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-columns)
        - Esta página proporciona detalles sobre el uso de grid-template-columns para especificar el tamaño y el número de columnas en una cuadrícula.


⌨️ con ❤️ por [Toffy Caluga](https://github.com/toffycaluga) 
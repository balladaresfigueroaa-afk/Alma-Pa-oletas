# ALMA — versión Bootstrap 5

Esta versión integra **Bootstrap 5.3.8** mediante CDN y conserva el diseño visual personalizado de ALMA.

## ¿Dónde se usa Bootstrap?
- `navbar`, `navbar-expand-lg`, `navbar-toggler` y `collapse`: menú responsive con botón hamburguesa.
- `container`: ancho y alineación general del contenido.
- `navbar-nav`, `nav-item`, `nav-link`: navegación.
- `form-control` y `form-select`: controles de formulario.
- `img-fluid`: imágenes adaptables.
- Utilidades como `mx-auto`, `mb-2`, `mb-lg-0`, `d-none` y `d-lg-flex`.
- `bootstrap.bundle.min.js`: comportamiento interactivo del menú móvil.

## CSS propio
El archivo `css/style.css` conserva:
- Paleta de colores de ALMA.
- Tipografías.
- Botones personalizados.
- Tarjetas de productos.
- Secciones, espaciados y composición visual.
- Ajustes responsive complementarios.

## Rúbrica
1. Diseño responsive: Bootstrap + media queries.
2. Usabilidad: navegación clara, botones, labels y estados focus.
3. Navegación: navbar responsive Bootstrap.
4. Organización: páginas y secciones semánticas.
5. Validación: HTML5 + CSS externo.
6. Hosting: pendiente de publicar.
7. Tipografías: Playfair Display + Poppins.
8. Uso del color: variables CSS coherentes.
9. Formulario HTML: formulario de contacto + newsletter.
10. Acoplamiento HTML/CSS: presentación principal en `css/style.css`.

Para ver el menú hamburguesa correctamente, abre la página con conexión a Internet porque Bootstrap se carga desde CDN.

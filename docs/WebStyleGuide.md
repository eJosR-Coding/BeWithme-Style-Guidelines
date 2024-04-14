# Web Style Guide

## Introducción
Este documento detalla las directrices específicas para el desarrollo de interfaces web en el proyecto BeWithme.

## Responsive Design
- Asegúrate de que todas las páginas web sean responsivas y se visualicen correctamente en dispositivos móviles y de escritorio.
- Utiliza media queries para ajustar los estilos según el tamaño del dispositivo.

## Componentes Comunes
### Botones
- **Color**: Utiliza el color primario `#005f73` para botones de acción principal.
- **Hover State**: Cambia el color a `#0a9396` en hover.

### Formularios
- Mantén un estilo consistente en todos los formularios utilizando el esquema de colores definido.
- Asegura que los campos de entrada tengan validaciones claras y mensajes de error accesibles.

## Estilos CSS
- Utiliza clases reutilizables definidas en `/styles/base.css`.
- Evita el uso excesivo de `!important` y estilos inline.

## Ejemplos de Código
```html
<button class="btn btn-primary">Submit</button>

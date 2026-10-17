# La Sazón de Lita — Menú digital

Menú interactivo de La Sazón de Lita, Km 42 vía Cali–Dagua. Incluye fotografías reales, selección de platos, enlaces de pedido por WhatsApp y modo de edición local.

## Publicación

El sitio es estático y se sirve desde la raíz del repositorio. En Netlify usa:

- Build command: `true`
- Publish directory: `.`

## Edición

Pulsa **Editar menú** para modificar datos y fotos. Los cambios se guardan en el almacenamiento local del navegador utilizado; cada navegador mantiene su propia copia.

## Archivos

- `index.html`: aplicación y estilos.
- `assets/`: imágenes incluidas como módulos JavaScript, sin dependencias externas.
- `netlify.toml`: configuración de publicación estática.

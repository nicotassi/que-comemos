# ¿Qué comemos?

Planificador de comidas familiar: menú de la semana, qué cocinar con lo que hay en la heladera, lista de mandados para compartir por WhatsApp y recetas.

**App:** https://nicotassi.github.io/que-comemos/

## Instalarla en el teléfono
- **Android (Chrome):** abrí el link → menú ⋮ → **Instalar app**.
- **iPhone (Safari):** abrí el link → botón Compartir → **Agregar a inicio**.
- **Computadora (Chrome o Edge):** ícono de instalar en la barra de direcciones.

Funciona sin internet. Los datos quedan guardados en cada dispositivo; desde **Más → Tus datos** se puede descargar una copia y restaurarla en otro.

## Archivos
- `index.html`: la app completa.
- `manifest.webmanifest`: nombre, colores e íconos para instalarla.
- `sw.js`: modo sin conexión. Con internet siempre carga la última versión.
- `icon.svg`, `icon-*.png`, `apple-touch-icon.png`: íconos.

## Publicación
GitHub Pages publica la rama `main` (carpeta raíz). Cada cambio que llega a `main` se publica solo en uno o dos minutos, y la app instalada toma la versión nueva la próxima vez que se abre con internet.

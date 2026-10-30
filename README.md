# Cuota — registro de apuestas

Aplicación estática para registrar apuestas a partir de capturas o mediante carga manual. La captura se procesa en el navegador con Tesseract.js; los registros se guardan en el almacenamiento local del navegador.

## Uso local

Abrí `index.html` en un navegador moderno con conexión a internet. La conexión permite cargar Tesseract.js, los datos de idioma del OCR y las fuentes visuales.

## Publicación

Se puede alojar como sitio estático desde la raíz del repositorio. No necesita servidor ni base de datos. Para que otras personas puedan entrar, el sitio debe tener una URL pública. Cada persona tendrá sus propios registros en su navegador; no hay sincronización entre dispositivos.

## Archivos

- `index.html`: estructura de la aplicación.
- `styles.css`: estilos y diseño adaptable a móviles.
- `app.js`: reconocimiento OCR, revisión y almacenamiento local.

Por favor guarda la imagen adjunta del chat con nombre `logo.png` dentro de esta carpeta `images/`.

Pasos rápidos en Windows (PowerShell):
1. Descarga la imagen desde el chat (botón derecho → Guardar imagen como...) y guárdala en:
   images\logo.png

2. Si prefieres usar PowerShell para descargar desde una URL (si la tienes), usa:

   Invoke-WebRequest -Uri "<URL_DE_LA_IMAGEN>" -OutFile "images\logo.png"

Después de guardar la imagen, abre `index.html` en el navegador para ver el logo.

# F&F Oil Solutions — Tarjeta digital (PWA + NFC)

## Publicar
1. Suba TODOS los archivos de esta carpeta a una dirección con HTTPS, por ejemplo `https://ffoilsolutions.com/card/`
   (o un repositorio de GitHub Pages).
2. Si usa otra dirección, cámbiela en `index.html` → `cardUrl`.
3. Nombre, cargo y teléfono se editan en `index.html` (bloque CONTACT) y en `contact.vcf`.

## Instalar como app
- Android (Chrome): botón "Instalar app" o menú ⋮ → Instalar app.
- iPhone (Safari): Compartir → Agregar a inicio.

## Grabar las tarjetas NFC
- Use tarjetas NTAG213/215/216 en blanco.
- Android + Chrome: abra la app publicada y toque "Grabar tarjeta NFC".
- iPhone: la web no puede grabar NFC; use la app gratuita "NFC Tools" → Escribir → Agregar registro → URL → pegue la dirección.
- Opcional: bloquee la tarjeta (solo lectura) en NFC Tools para que nadie la reescriba.

Al tocar la tarjeta, cualquier iPhone (XS o más nuevo) o Android con NFC abre la tarjeta sin instalar nada.

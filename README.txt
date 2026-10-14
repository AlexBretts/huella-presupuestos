HUELLA · ACTUALIZACIÓN DE LA APLICACIÓN

Este paquete actualiza la aplicación web progresiva de Huella.

ARCHIVOS
- index.html: aplicación, tarifas, cálculo y creación/compartición de PDF.
- manifest.webmanifest: configuración para instalarla en el iPhone.
- sw.js: caché de la aplicación; cambia la versión para que se actualice.
- icon-192.png e icon-512.png: iconos de la app.

PRECIOS CONFIGURADOS
Guardería de día (normal / especial): adulto principal 18 / 20 €, cachorro principal 20 / 22 €, adulto adicional 16 / 18 €, cachorro adicional 18 / 20 €.
Guardería de noche (normal / especial): adulto principal 26 / 32 €, cachorro principal 30 / 36 €, adulto adicional 23 / 26 €, cachorro adicional 27 / 30 €.
Recogida y entrega: +10 €. Reserva con menos de 24 horas: +10 €.

FECHAS ESPECIALES INCLUIDAS
24/12/2026–03/01/2027; 06/01/2027; 26–29/03/2027; 16/07–22/08/2027; 09–12/10/2027; 30/10–01/11/2027; 04–08/12/2027; 23/12/2027–06/01/2028.

ACTUALIZAR EN GITHUB
1. Descarga y descomprime el ZIP.
2. Abre el repositorio de GitHub y entra en la carpeta raíz (donde está el index.html actual).
3. Sube/reemplaza todos los archivos del ZIP: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png y README.txt.
4. Confirma los cambios con Commit changes.
5. Abre la URL de GitHub Pages y recarga. Si el iPhone muestra la versión antigua, cierra la app instalada y vuelve a abrirla; si persiste, elimina el acceso de pantalla de inicio y vuelve a añadirlo desde Safari.

NOTAS
- La app no almacena ni envía los datos del cliente a un servidor; el PDF se genera en el dispositivo.
- La creación del PDF usa jsPDF desde CDN y requiere conexión a internet para cargar esa librería.
- Las fechas especiales están configuradas dentro de index.html y pueden editarse en el array specialRanges.


ACTUALIZACIÓN VISUAL DE PRESUPUESTOS
- PDF A4 con cabecera de marca, número de presupuesto, fecha de emisión, datos de reserva, desglose y total destacado.
- Aviso visible: PRESUPUESTO · NO ES FACTURA. Incluye una nota indicando que no acredita el pago ni sustituye una factura.
- La caché de la aplicación se ha actualizado a huella-v3.

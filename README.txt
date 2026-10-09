HUELLA · APP DE PRESUPUESTOS

CONTENIDO
- index.html: aplicación y diseño
- manifest.webmanifest: nombre, icono y modo app
- sw.js: caché básica para que la interfaz pueda abrirse sin conexión después de visitarla
- icon-192.png e icon-512.png: iconos

PUBLICAR GRATIS CON GITHUB PAGES
1. Crea un repositorio en GitHub llamado huella-presupuestos.
2. Sube todos los archivos de esta carpeta a la raíz del repositorio.
3. En Settings > Pages, selecciona Deploy from a branch, branch main y folder /(root), y guarda.
4. Cuando GitHub termine, abre la URL que te indique.
5. En cada iPhone, abre la URL en Safari > Compartir > Añadir a pantalla de inicio. Activa «Abrir como app web» si aparece.

IMPORTANTE
- No se envían datos del cliente a ningún servidor ni se guardan presupuestos en una base de datos.
- GitHub Pages puede servir el código públicamente; no incluyas datos personales en el repositorio.
- Para generar PDF se carga jsPDF desde jsDelivr, por lo que la primera generación necesita conexión a internet.
- Compartir PDF usa el menú nativo del iPhone si el navegador admite compartir archivos. En otro caso descarga el PDF para compartirlo manualmente.
- Esta es una primera versión funcional para probar; verifica tarifas y PDF en el iPhone antes de usarla con clientes reales.

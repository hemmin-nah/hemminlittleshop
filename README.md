# Little Digital Things ✳

Mini tienda web retro con catálogo editable, ES/EN, día/noche, categorías y cursor pixelado.

## Publicación en GitHub Pages
1. Crea un repositorio público (por ejemplo `little-digital-things`).
2. Sube **los cuatro archivos de la raíz** (`index.html`, `style.css`, `app.js`, `catalog.json`) y `cursor.svg`. No subas solo el ZIP.
3. En el repositorio, entra en **Settings → Pages → Build and deployment → Deploy from a branch**. Elige `main` y `/ (root)`, y guarda.
4. Abre la URL indicada por GitHub Pages, generalmente `https://TU-USUARIO.github.io/little-digital-things/`.
5. Comparte ese único enlace en Ko-fi o donde quieras.

## Editor visual
- Pulsa el pequeño **⚙** del pie de página.
- Desde **General**, cambia el nombre, la biografía bilingüe, la foto y los enlaces sociales.
- Desde **Secciones**, crea, borra, renombra o cambia la imagen de cada categoría.
- Desde **Creaciones**, añade, edita o elimina fichas; enlaza a PWA o a ficheros descargables y selecciona el botón apropiado.
- En **Publicar**, descarga `catalog.json`. **Para hacer públicos tus cambios debes subir ese archivo actualizado al repositorio** (sobrescribe el antiguo y confirma el commit). No existe una sincronización automática con GitHub ni cuentas de usuario.
- Los cambios antes de exportar solo se guardan en el navegador actual mediante localStorage. Cambiar de navegador o limpiar datos puede borrarlos. Exporta una copia.
- También puedes importar un `catalog.json` previo desde **Publicar**.

## Imágenes y descargas
Usa URLs `https://...` o rutas de imágenes dentro del repositorio, como `images/mi-juego.png`. Primero añade dichos archivos a GitHub. Para descargas, enlaza a un ZIP, a GitHub Releases, Gumroad o Ko-fi; el navegador o servicio gestionará la descarga. Enlaces en blanco mostrarán «Próximamente».

## Notas
- El editor no está protegido por contraseña. Cualquier visitante puede abrirlo, pero sus cambios solo son locales y **no modifican tu tienda publicada**.
- El sitio no tiene backend ni analíticas. Para permitir edición remota autenticada y publicación automática haría falta integrar un CMS o autenticación de GitHub.
- Los productos de ejemplo y los enlaces a Ko-fi y GitHub son marcadores: sustituye por tus enlaces reales antes de difundir.
- Usa un servidor local para probar el catálogo (ej.: `npx serve .`) o publícalo directamente en GitHub Pages. Abrir `index.html` con `file://` puede bloquear la lectura de `catalog.json`.

# Píldoras histórico-matemáticas — cómo publicar este sitio

## Qué tenés acá
- `index.html` — página principal con la lista de píldoras
- `pildoras/pildora-01-galois.html` — primera píldora completa
- `assets/css/styles.css` — estilos de todo el sitio (un solo archivo, se reutiliza)
- `assets/videos/` — acá van tus archivos .mp4 (agregá `galois.mp4` con tu video)

## Paso 1 — Crear el repositorio en GitHub
1. Entrá a github.com y creá una cuenta si no tenés
2. Tocá "New repository"
3. Nombralo, por ejemplo: `pildoras-matematicas`
4. Marcalo como público
5. Creá el repositorio (sin agregar README todavía)

## Paso 2 — Subir los archivos
1. Dentro del repositorio recién creado, tocá "uploading an existing file"
2. Arrastrá TODA la carpeta `pildoras-site` (o su contenido: index.html, la carpeta assets, la carpeta pildoras)
3. Confirmá el commit ("Commit changes")

## Paso 3 — Activar GitHub Pages
1. En el repositorio, andá a "Settings"
2. En el menú lateral, buscá "Pages"
3. En "Branch", elegí `main` y la carpeta `/ (root)`
4. Guardá — GitHub te va a dar una URL tipo:
   `https://tu-usuario.github.io/pildoras-matematicas/`

## Paso 4 — Subir tu video
- Copiá tu archivo de video de Galois dentro de `assets/videos/` con el nombre `galois.mp4`
- Si el archivo es muy pesado (más de 25 MB), lo mejor es subirlo a YouTube como "no listado" y cambiar el `<video>` por un `<iframe>` de YouTube — avisame y te ayudo con ese cambio

## Paso 5 — Activar el formulario de suscripción
1. Entrá a formspree.io y creá una cuenta gratis
2. Creá un formulario nuevo, te va a dar una URL tipo `https://formspree.io/f/abcd1234`
3. Reemplazá `TU_ID_DE_FORMSPREE` en `index.html` y en cada píldora por ese ID
4. Los emails de suscriptores te van a llegar a tu correo y vas a poder verlos en el panel de Formspree

## Cada vez que quieras agregar una píldora nueva
Yo te genero el archivo HTML completo (como el de Galois). Vos solo tenés que:
1. Guardarlo dentro de la carpeta `pildoras/`
2. Agregar una tarjeta nueva en `index.html` (te doy el bloque de código listo para copiar y pegar)
3. Subir los cambios a GitHub (podés hacerlo desde la web, sin instalar nada)

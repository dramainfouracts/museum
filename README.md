## Español
Guía por [@nami-stuff](https://www.tumblr.com/nami-stuff), editada por [@knownyurimaxxer](https://www.tumblr.com/knownyurimaxxer). Puedes ver una *live demo* de la galería [AQUÍ](https://knownyurimaxxer.github.io/gallery/).

### ¿Cómo instalo la galería?
1. Crea una cuenta de **Github**.
2. Crea una *fork* de [ESTE](https://github.com/knownyurimaxxer/utility-gallery) repositorio. Se hace con el botón de **fork** (asegúrate que `Copy the main branch only` esté marcado). Debe ser un repositorio público.
3. Si quieres editar el *HTML* o *CSS* para darles tu estilo personal, es el momento. Los archivos a editar son `.github/workflows/resources/root-index.html`, `.github/workflows/resources/branch-index.html` y `.github/workflows/resources/style.css`.

   *¡Si vas a realizar una fork base para tu idioma, recuerda añadirte en los créditos! (y editar el enlace en este `README.md` para que apunte a tu repositorio).*
4. Ve a la configuración del repositorio en **Settings** (recomiendo deshabilitar todas las **Features** y **Comments**).
5. Selecciona **Pages** y en **Source** selecciona **Github Actions**.
6. Ahora selecciona **Environments** y, una vez dentro, haz *click* en **github-pages**. En **Deployment branches and tags** selecciona **No restriction**.

### ¿Cómo funciona la galería?
La galería funciona usando ramas para cada conjunto de imágenes, lo que genera una estructura donde cada grupo es listado con sus respectivos subgrupos debajo y cada subgrupo tiene una carpeta con sus gráficos.

### ¿Cómo añadir tus gráficos?
1. Crea una nueva rama de `main` desde **New branch** (tienes que hacer *click* donde dice `main` y luego **View all branches**) y dale un nombre con la siguiente estructura: `nombre-del-grupo\nombre-del-subgrupo` (ejemplo: `tuberculo\patata`).

   *No uses espacios ni carácteres especiales.*
3. Renombra tus gráficos con el tipo de gráfico que representan (ejemplo: *avatar.png*). Si tienes múltiples variantes del mismo tipo de gráfico, dales un número (ejemplo: *firma1.png* y *firma2.png*).

   *Se permiten espacios, pero para urls más cortas, se recomienda no usarlos.*
4. Selecciona tu rama en el repositorio y sube tus gráficos desde **Add file**.
5. Espera a que se ejecute el deploy por si solo. Si no lo hace, ve a **Actions**, selecciona **Deploy to GitHub Pages** y dale a **Run workflow**.
7. Al terminar el proceso, la página se habrá actualizado (limpia cache, `ctrl+shift+r`, si no ves cambios). Accede al subgrupo y ahí estarán los gráficos que hayas subido, con su link listo para copiar.

> **NOTA:** Una vez creada la rama de un subgrupo, puedes seguir usándola para añadir o modificar gráficos. Si cambias un archivo por otro con el mismo nombre, se reemplazará ahí dónde lo estés usando. <ins>Vigila no borrar tu rama (o ninguna otra), o perderás todo</ins>.

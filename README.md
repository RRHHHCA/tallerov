# NEXT STEP · HCA Bachillerato

## Probar sin conexión
1. Descomprimí el ZIP.
2. Abrí `index.html` en Chrome o Edge.
3. Usá el botón **Comenzar · Armar CV**.
4. Abrí **Modo RRHH** desde la barra superior; para volver, **Ver como estudiante**.

## Publicar en GitHub Pages
Subí el contenido de esta carpeta (no el ZIP) a la raíz del repositorio. En Settings > Pages elegí Deploy from a branch, main, /(root).

## Guardar cambios
Las ediciones se guardan en el navegador donde las realizás. Exportá JSON desde el editor como respaldo. Para publicar cambios a todo el mundo, reemplazá `data/contenidos.json` en GitHub **y sincronizá los datos integrados en los HTML**; el modo local incorpora una copia interna para funcionar sin servidor.

**Seguridad:** el editor no tiene autenticación. Cualquier visitante puede acceder a él y modificar una copia local, pero no puede modificar GitHub sin permisos de repositorio. No incluir información confidencial.

## Imagen de la entrevista
La escena de Interview Quest usa `assets/entrevistador.png`. Para cambiarla, reemplazá ese archivo por otra imagen apaisada (16:9) con el mismo nombre, o cargala desde **Modo RRHH > Identidad visual**. Si el archivo falta, se muestra `assets/entrevistador.svg`.

## Temas
El botón **Tema** de la barra superior permite a cada visitante elegir una paleta; la elección queda guardada solo en su navegador. El "Tema del colegio" es la paleta definida en **Modo RRHH > Identidad visual**. Al lado está el botón **Modo claro / Modo oscuro**, que funciona con cualquier tema y también se guarda por navegador. La página abre en modo oscuro.

## Puntuación de la entrevista
Cada respuesta vale de 1 a 3 con código semáforo: 3 = verde (más adecuada), 2 = amarillo (intermedia), 1 = rojo (menos adecuada). Los contenidos guardados con la escala anterior (1–4) se convierten solos al abrir la página o al importar un JSON.

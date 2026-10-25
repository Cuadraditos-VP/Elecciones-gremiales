# Elecciones Gremiales

Tablero con los resultados de las elecciones gremiales por casino: Lista FAS frente a la lista opositora de cada año (Azul en 2021, Naranja en 2024).
Se puede instalar en el celular o la computadora como una app (PWA) y funciona sin conexión.

## Qué tiene

- Una pestaña por elección, con el total y la tabla por casino (votos, porcentajes, diferencia).
- **Comparar**: el porcentaje de FAS en cada casino entre dos elecciones.
- **+ Nueva elección**: carga de votos tipo Excel (flechas, Enter, Tab, F2, pegar desde Excel).

## Publicarlo en GitHub Pages

1. En GitHub, creá un repositorio nuevo, por ejemplo `elecciones-gremiales` (público).
2. Tocá **Add file → Upload files** y arrastrá **todo el contenido** de esta carpeta
   (`index.html`, `manifest.json`, `sw.js`, `.nojekyll`, `README.md` y la carpeta `icons`). Confirmá con **Commit changes**.
   > El archivo `.nojekyll` empieza con punto y en algunas computadoras no se ve; si no se sube, no pasa nada.
3. Andá a **Settings → Pages**. En *Branch* elegí `main` y la carpeta `/ (root)`, y tocá **Save**.
4. En uno o dos minutos queda publicado en `https://TU-USUARIO.github.io/elecciones-gremiales/`.

## Instalarlo como app

- **Android (Chrome):** abrí el link → menú ⋮ → **Instalar app** (o *Agregar a la pantalla principal*).
- **iPhone (Safari):** abrí el link → botón Compartir → **Agregar a inicio**.
- **Computadora (Chrome/Edge):** ícono de instalar en la barra de direcciones.

## Cargar una elección nueva

1. Abrí la app → **+ Nueva elección** → completá año, lista opositora, color y votos → **Guardar elección**.
   Queda guardada solo en ese navegador.
2. Para que la vean todos: en la misma pestaña tocá **Descargar HTML actualizado**. Se baja un `index.html` con todas las elecciones adentro.
3. En GitHub, **Add file → Upload files**, subí ese `index.html` (reemplaza al anterior) y **Commit changes**.
4. Al abrir la app de nuevo se cargan los datos del archivo nuevo.

## Si un cambio no aparece

La app guarda una copia para funcionar sin internet. Si después de subir un cambio seguís viendo lo anterior, cerrala y volvé a abrirla (o recargá la página dos veces).

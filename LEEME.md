# Sitio web Fluidos 2027 – Colonia

Sitio de una sola página, basado en la plantilla de LANET 2025 (Bootstrap 3).

## Estructura
- `index.html` → todo el contenido. Buscá `EDITAR:` para ver lo que falta completar.
- `css/fluidos.css` → colores y estilo propios (paleta del logo en `:root`).
- `css/style.css`, `css/bootstrap.min.css`, `js/`, `fonts/`, `font-awesome/` → plantilla original, no hace falta tocarlos.
- `img/` → logos y favicon. `files/` → PDFs (circulares, plantilla de resumen, programa).

## Verlo en tu computadora
Doble clic en `index.html` (el mapa necesita conexión a internet).

## Publicarlo en GitHub Pages
1. Entrá a github.com con la cuenta del congreso.
2. **New repository**. Nombre:
   - `USUARIO.github.io` (USUARIO = nombre de la cuenta) → el sitio queda en `https://USUARIO.github.io`
   - u otro nombre, por ejemplo `fluidos2027` → queda en `https://USUARIO.github.io/fluidos2027`
   Marcalo como **Public**.
3. En el repositorio: **Add file → Upload files** y arrastrá **el contenido** de esta carpeta
   (no la carpeta en sí: `index.html` tiene que quedar en la raíz). **Commit changes**.
4. **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, carpeta `/ (root)` → **Save**.
5. Esperá 1–2 minutos y abrí la dirección que muestra esa página.

Para actualizar: editá los archivos acá, y volvé a subir los que cambiaste con *Upload files* (reemplaza los anteriores).

Opcional: si más adelante quieren un dominio propio (p. ej. fluidos2027.uy), se configura en Settings → Pages → Custom domain.

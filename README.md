# Compresor de PDF

Página web que comprime PDF escaneados directamente en el navegador (los archivos no se suben a ningún servidor).

- Elige uno o varios PDF (o arrástralos).
- Define la **resolución máxima** (dpi), la **calidad** de imagen y, opcionalmente, un **tamaño máximo en KB**.
- Si pones tamaño máximo, baja la calidad y luego la resolución hasta que el archivo quepa.
- Descarga el resultado como `nombre_comp.pdf`.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub y sube `index.html` y este `README.md`.
2. Ve a **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
4. En un minuto tendrás la página en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

Usa pdf.js desde cdnjs, por lo que necesita conexión a internet al abrirla.

## Nota

El resultado convierte cada página en imagen JPEG. Va muy bien para escaneos y fotos; un PDF con texto seleccionable perdería esa selección.

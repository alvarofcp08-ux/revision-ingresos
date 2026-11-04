# NEXOCORP · Revisión diferencias ingresos

Web estática (un solo `index.html`, sin build ni servidor). Cruza el IB Shipment, el Kardex y el WMS detalle para encontrar productos no replicados en el Kardex.

## Subir a GitHub
1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html` y `README.md` a la raíz del repositorio.

## Publicar en Vercel
1. En vercel.com elige **Add New → Project** e importa el repositorio.
2. Framework Preset: **Other**. Deja vacíos Build Command y Output Directory.
3. Pulsa **Deploy**.

La librería de lectura de Excel (SheetJS) se carga desde cdnjs; hace falta conexión a internet al abrir la web.

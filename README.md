# Saludly · Landing

Sitio estático. No necesita build.

## Publicar en Vercel

Opción A · Terminal (la más rápida)
    cd saludly-landing
    npx vercel          # primera vez: inicia sesión y acepta los valores por defecto
    npx vercel --prod   # publica en producción

Opción B · GitHub
1. Sube esta carpeta a un repositorio nuevo en GitHub.
2. En https://vercel.com/new importa el repositorio.
3. Framework Preset: "Other". Build Command: vacío. Output Directory: vacío (raíz).
4. Deploy.

## Ver en local
    python3 -m http.server 8080   # y abre http://localhost:8080
No abras index.html con doble clic: el navegador bloquea las animaciones por file://.

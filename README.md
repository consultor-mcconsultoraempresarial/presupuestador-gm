# Presupuestador · Gráficamente DPI

Aplicación web de página única (HTML/CSS/JS embebido, sin dependencias externas
salvo Google Fonts) para generar presupuestos.

## Desarrollo local

Es un único archivo estático, no requiere build. Basta con abrir `index.html`
en el navegador, o servirlo con cualquier servidor estático:

```bash
npx serve .
```

## Despliegue

Configurado para desplegar en [Vercel](https://vercel.com) como sitio
estático (ver `vercel.json`). Cada push a `main` dispara un deploy si el
repositorio está conectado a un proyecto de Vercel.

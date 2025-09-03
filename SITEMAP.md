# Documentación del Sitemap - RiverTI

## ✅ Sitemap implementado exitosamente

### Archivos generados:
- **sitemap-index.xml** - Índice principal del sitemap
- **sitemap-0.xml** - Sitemap con las URLs del sitio
- **robots.txt** - Configuración para web crawlers

### URLs incluidas en el sitemap:
- `https://riverti.cl/` (Página principal)

### Configuración:
- **Frecuencia de cambio**: weekly
- **Prioridad por defecto**: 0.7
- **Última modificación**: Se actualiza automáticamente en cada build

### Cómo funciona:
1. El sitemap se genera automáticamente al ejecutar `npm run build`
2. Se actualiza cada vez que se construye el proyecto
3. Los motores de búsqueda pueden encontrarlo en `/sitemap-index.xml`

### Para verificar el sitemap:
- Local: `http://localhost:4321/sitemap-index.xml`
- Producción: `https://riverti.cl/sitemap-index.xml`

### Robots.txt configurado:
- Permite indexación completa del sitio
- Referencia al sitemap
- Bloquea áreas administrativas
- Incluye crawl-delay de 1 segundo

### Próximos pasos:
1. Cambiar el dominio en `astro.config.mjs` cuando tengas el dominio final
2. Enviar el sitemap a Google Search Console
3. Verificar que el sitemap se actualice correctamente en producción

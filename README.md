# email-assets

Repositorio público de imágenes para campañas de email HTML.
Servido vía [jsDelivr](https://www.jsdelivr.com/) como CDN gratuito.

## Estructura

```
{cliente}/
├── logos/                          # Logos reutilizables del cliente
└── {YYYY-MM-nombre-campana}/       # Imágenes específicas de una campaña
```

## URL pattern (jsDelivr)

```
https://cdn.jsdelivr.net/gh/devhispa-byte/email-assets/{ruta-al-archivo}
```

Para fijar versión en campañas históricas:

```
https://cdn.jsdelivr.net/gh/devhispa-byte/email-assets@v1.0/{ruta-al-archivo}
```

## Assets actuales

| Cliente | Archivo | URL CDN |
|---|---|---|
| Mapfre | `mapfre/logos/mapfre-inversion-logo.png` | `https://cdn.jsdelivr.net/gh/devhispa-byte/email-assets/mapfre/logos/mapfre-inversion-logo.png` |

## Workflow para nueva campaña

1. Crear carpeta `{cliente}/{YYYY-MM-nombre}/` si hay assets específicos
2. Subir PNG/JPG (drag & drop en GitHub web o `git add`)
3. Commit + push
4. Componer la URL jsDelivr y pegarla en el HTML

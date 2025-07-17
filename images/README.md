# Images Directory

Esta carpeta contiene las imágenes de preview para el portfolio de Alberto Marturelo Lorenzo.

## Estructura:

### `/projects/`
Cada proyecto tiene su propia subcarpeta con imágenes organizadas:

- **`/farily/`** - Aplicación MVP para tareas bajo demanda
  - `preview.png` - Imagen principal del proyecto
  
- **`/senda/`** - App de transferencias para TropiPay
  - `preview.png` - Screenshot de la aplicación
  
- **`/haventos/`** - Proyecto adicional
  - `preview.png` - Imagen de preview
  
- **`/id-watchdog/`** - App de protección de identidad (Equifax)
  - `preview.png` - Screenshot de la aplicación
  
- **`/lanetalk/`** - App de estadísticas de bowling
  - `preview.png` - Imagen principal
  - `460x0w.webp` - Screenshots adicionales del App Store
  - `460x0w (1).webp` - Screenshots adicionales del App Store
  - `460x0w (2).webp` - Screenshots adicionales del App Store
  
- **`/intercaribbean/`** - Proyecto adicional
  - `preview.png` - Imagen de preview

### `/articles/`
Imágenes de vista previa para los artículos del blog:
- `0_WkhXB6iJwUW8ZOYe.webp` - Preview del artículo "From Crashes and Bad Reviews to a Stable and Secure App"
- `1_CD8UxtT6EL_Nwic5PgH9xg.webp` - Preview del artículo "How to Prevent Sensitive Data Leaks in Flutter"

## Uso:

Para usar las imágenes en el portfolio:

```html
<div class="project-image" style="background-image: url('./images/projects/farily/preview.png'); background-size: cover; background-position: center;">
</div>
```

## Recomendaciones:

- **Tamaño**: 400x200px (ratio 2:1) para preview.png
- **Formato**: PNG o JPG (WebP para optimización web)
- **Optimización**: Comprime las imágenes para web
- **Calidad**: Usa screenshots de alta resolución de las apps/artículos
- **Organización**: Mantén cada proyecto en su subcarpeta correspondiente
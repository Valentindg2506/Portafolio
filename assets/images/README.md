# Imágenes del Portafolio

Coloca aquí todas las imágenes de tu portafolio.

## Estructura Recomendada:

```
assets/images/
├── perfil.jpg          (Tu foto - 400x500px)
├── proyecto-1.jpg      (Screenshots de proyectos - 600x400px)
├── proyecto-2.jpg
├── proyecto-3.jpg
├── proyecto-4.jpg
├── proyecto-5.jpg
├── proyecto-6.jpg
└── preview.jpg         (Para redes sociales - 1200x630px)
```

## Especificaciones Técnicas:

### Foto de Perfil
- **Tamaño:** 400x500px
- **Formato:** JPG o WebP
- **Peso:** < 150KB
- **Aspecto:** Profesional, fondo neutro

### Screenshots de Proyectos
- **Tamaño:** 600x400px (ratio 3:2)
- **Formato:** JPG o WebP
- **Peso:** < 200KB cada una
- **Contenido:** Captura representativa del proyecto

### Preview Social (Open Graph)
- **Tamaño:** 1200x630px
- **Formato:** JPG o PNG
- **Peso:** < 300KB
- **Uso:** Se muestra al compartir en redes sociales

## Optimización de Imágenes:

### Herramientas Online:
- TinyPNG (https://tinypng.com)
- Squoosh (https://squoosh.app)
- ImageOptim (Mac)

### Convertir a WebP (mejor rendimiento):
```bash
# Instalar cwebp
sudo apt install webp

# Convertir imagen
cwebp -q 85 imagen.jpg -o imagen.webp
```

## Uso en HTML:

### Imagen simple:
```html
<img src="assets/images/perfil.jpg" alt="Foto de perfil">
```

### Con WebP (fallback):
```html
<picture>
  <source srcset="assets/images/perfil.webp" type="image/webp">
  <img src="assets/images/perfil.jpg" alt="Foto de perfil">
</picture>
```

## Placeholder Temporales:

Mientras no tengas tus imágenes, el portafolio usa placeholders de:
- https://via.placeholder.com

Reemplázalos por tus imágenes reales antes de desplegar.

## Tips:

- Usa nombres descriptivos: `proyecto-app-saas.jpg`
- Mantén consistencia en el estilo
- Comprime siempre antes de subir
- Considera usar un CDN para mayor velocidad
- Añade atributos `alt` para accesibilidad

# 🚀 Guía Rápida - Portafolio Valentín De Gennaro

## ⚡ Inicio en 3 Pasos

### 1️⃣ Abre el archivo
```bash
# Opción A: Doble clic en index.html
# Opción B: Arrastra index.html a tu navegador
```

### 2️⃣ ¿Quieres desarrollo local?
```bash
# Con Python
python -m http.server 8000

# Con PHP  
php -S localhost:8000

# Con VS Code
# Instala "Live Server" y haz clic derecho → "Open with Live Server"
```

Abre: `http://localhost:8000`

### 3️⃣ Personaliza
Edita `index.html` y cambia:
- Tu nombre (línea 54)
- Tu bio (líneas 57-60)
- Tus proyectos (líneas 450+)
- Tu información de contacto (líneas 795+)

---

## 📝 Datos a Actualizar

### Información Personal
```html
<!-- Línea 54 -->
<span class="gradient-text">TU NOMBRE</span>

<!-- Línea 796 -->
<a href="mailto:TU-EMAIL@ejemplo.com">TU-EMAIL@ejemplo.com</a>

<!-- Línea 810 -->
<a href="tel:+34TUNUMERO">+34 TU NÚMERO</a>

<!-- Línea 814 -->
<a href="https://wa.me/34TUNUMERO">WhatsApp</a>
```

### Imagen de Perfil
```html
<!-- Línea 127 - Reemplaza el placeholder -->
<img src="img/tu-foto.jpg" alt="Tu Nombre">
```

### Proyectos
Actualiza los 5 proyectos en las líneas 450-610:
- Cambiar imágenes
- Actualizar descripciones
- Modificar enlaces a GitHub
- Añadir enlaces a demos

---

## 🎨 Personalizar Colores

Edita `css/styles.css` líneas 1-60:

```css
:root {
    --primary-color: #4f46e5;      /* Color principal */
    --secondary-color: #ec4899;     /* Color secundario */
    --accent-color: #10b981;        /* Color de acento */
}
```

---

## 🚀 Despliegue Rápido

### GitHub Pages (Recomendado)
1. Crea repo en GitHub
2. Sube los archivos
3. Settings → Pages → Deploy from main branch
4. ¡Listo! URL: `https://usuario.github.io/repo`

### Netlify
1. Arrastra la carpeta a netlify.com/drop
2. Deploy automático
3. URL personalizada gratis

### Vercel  
1. Instala Vercel CLI: `npm i -g vercel`
2. Ejecuta: `vercel`
3. Sigue las instrucciones

---

## 📁 Estructura Simplificada

```
Portafolio-Test/
├── index.html          # TODO está aquí (página completa)
├── css/
│   └── styles.css      # Estilos + Dark mode
├── js/
│   └── main.js         # Navegación + Animaciones
└── README.md           # Documentación completa
```

---

## ✅ Checklist de Personalización

- [ ] Cambiar nombre en Hero
- [ ] Actualizar biografía
- [ ] Cambiar foto de perfil
- [ ] Actualizar email de contacto
- [ ] Actualizar número de teléfono
- [ ] Modificar enlaces de GitHub
- [ ] Añadir enlace de LinkedIn (si tienes)
- [ ] Actualizar proyectos con los tuyos
- [ ] Cambiar imágenes de proyectos
- [ ] Revisar habilidades técnicas
- [ ] Actualizar información educativa
- [ ] Revisar experiencia laboral
- [ ] Añadir tu CV en PDF (opcional)

---

## ❓ Problemas Comunes

### "Los iconos no aparecen"
✅ Asegúrate de tener conexión a internet (Font Awesome se carga desde CDN)

### "El dark mode no funciona"
✅ Revisa la consola del navegador (F12) para ver errores en JavaScript

### "Las imágenes no se ven"
✅ Verifica que las rutas sean correctas y que las imágenes existan

### "Los enlaces no funcionan"
✅ Actualiza los href con tus URLs reales

---

## 💡 Consejos

1. **Imágenes de Proyectos**: Usa 600x400px para mejor rendimiento
2. **CV PDF**: Colócalo en `assets/cv.pdf`
3. **Favicon**: Añade `<link rel="icon" href="favicon.ico">` en el `<head>`
4. **SEO**: Actualiza los meta tags en el `<head>` con tu información

---

## 📞 Necesitas Ayuda?

- 📖 Lee el [README.md](README.md) completo
- 🐛 Reporta problemas en GitHub Issues
- 💬 Contacta al autor: [Valentindg2506](https://github.com/Valentindg2506)

---

**¡Tu portafolio está listo! Solo personalízalo y despliégalo** 🎉

# 🚀 Portafolio Web - Valentín De Gennaro

Portafolio web profesional para estudiante de Desarrollo de Aplicaciones Multiplataforma en Valencia, España.

![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📋 Descripción

Portafolio web moderno y minimalista desarrollado con **HTML5, CSS3 y JavaScript puro**. Sin frameworks, sin dependencias complejas, solo código limpio y eficiente.

## ✨ Características

- 🎨 **Diseño Moderno**: Interfaz limpia y profesional con gradientes y animaciones CSS
- 📱 **100% Responsive**: Adaptado a todos los dispositivos (móvil, tablet, desktop)
- 🌓 **Modo Oscuro**: Toggle entre tema claro y oscuro con persistencia en LocalStorage
- 🎭 **Animaciones CSS**: Transiciones suaves y efectos al hacer scroll
- 📊 **Secciones Completas**:
  - Hero con presentación interactiva
  - Sobre mí con estadísticas animadas
  - Habilidades técnicas con barras de progreso
  - Proyectos reales con enlaces a GitHub y sitios en vivo
  - Educación y experiencia con timeline
  - Contacto directo (Email, WhatsApp, Teléfono)
- ⚡ **Rápido y Ligero**: Sin backend, sin base de datos, carga instantánea
- 🔍 **SEO Friendly**: Metadatos optimizados y estructura semántica
- 🚀 **Fácil de Desplegar**: Compatible con GitHub Pages, Netlify, Vercel, etc.

## 🛠️ Tecnologías

- **HTML5**: Estructura semántica
- **CSS3**: Variables CSS, Grid, Flexbox, Animaciones
- **JavaScript Vanilla**: ES6+, sin frameworks ni librerías
- **Font Awesome 6.5.1**: Iconos (única dependencia externa vía CDN)

## 📁 Estructura del Proyecto

```
Portafolio-Test/
│
├── index.html              # Página principal (portafolio completo)
│
├── css/
│   └── styles.css          # Estilos completos con modo oscuro
│
├── js/
│   └── main.js             # JavaScript: navegación, dark mode, animaciones
│
├── assets/                 # (Opcional) Imágenes y recursos
│
├── .gitignore
└── README.md
```

## 🚀 Instalación y Uso

### Opción 1: Abrir Directamente

1. **Descargar el proyecto**
2. **Abrir `index.html`** en tu navegador
   - ¡Listo! No necesitas servidor

### Opción 2: Servidor Local (Recomendado para desarrollo)

```bash
# Con Python
python -m http.server 8000

# Con PHP
php -S localhost:8000

# Con Node.js (si tienes http-server instalado)
npx http-server

# Con VS Code
# Usar extensión "Live Server"
```

Luego abre `http://localhost:8000` en tu navegador.

## 📝 Personalización

1. **Información Personal** (`index.html`):
   - Líneas 53-80: Sección Hero (nombre, título, descripción)
   - Líneas 145-195: Sección Sobre Mí
   - Líneas 795-840: Información de contacto

2. **Proyectos** (`index.html`, líneas 450-610):
   - Actualizar imágenes, títulos, descripciones y enlaces

3. **Habilidades** (`index.html`, líneas 210-445):
   - Modificar tecnologías y porcentajes

4. **Colores y Tema** (`css/styles.css`, líneas 1-70):
   - Variables CSS para personalizar toda la paleta de colores
   - Editar `index.html` con tu información personal

5. **Contactar**:
   - Email: Actualizar línea 807 con tu email real
   - WhatsApp: Ya configurado con +34 641 02 59 95
   - GitHub: Ya configurado (Valentindg2506)

## 🎨 Características Detalladas

### 1. Navegación Inteligente
- Menú fijo con efecto al hacer scroll
- Resaltado automático de sección activa
- Menú hamburguesa responsive para móvil

### 2. Hero Section
- Presentación con gradientes animados
- Código animado en ventana decorativa
- Enlaces directos a redes sociales

### 3. Habilidades
- Barras de progreso animadas basadas en tecnologías reales:
  - **Programación**: Python, JavaScript, PHP
  - **Web**: HTML5, CSS3, Responsive Design, XML/Markdown
  - **Bases de Datos**: SQL/MySQL, Diseño de BD
  - **Herramientas**: Git, GitHub, VS Code

### 4. Proyectos
- 5 proyectos reales con enlaces a GitHub
- Proyectos en producción con demos en vivo
- Tags de tecnologías utilizadas

### 5. Educación y Experiencia
- Timeline con información real:
  - **Educación**: DAM en CEACFP, Bachillerato en IADES
  - **Experiencia**: Proyectos web, Conductor VTC, Administrativo, Delivery

### 6. Modo Oscuro
- Toggle suave entre temas
- Persistencia con localStorage
- Colores optimizados para lectura

### 7. Contacto Simplificado
- Enlaces directos sin formularios complejos
- Email directo (mailto:)
- WhatsApp Web con número preconfigurado
- Llamada directa (tel:)
- Enlaces a redes sociales

## 🚀 Despliegue

### GitHub Pages (Gratis)

1. Crear repositorio en GitHub
2. Subir los archivos
3. Settings → Pages → Source: main branch
4. ¡Listo! Tu sitio estará en `https://tuusuario.github.io/repositorio`

### Netlify (Gratis)

1. Conectar con GitHub o subir carpeta
2. Deploy automático
3. Dominio personalizado gratuito

### Vercel (Gratis)

1. Importar desde GitHub
2. Deploy automático en cada push
3. Dominio personalizado

### Hosting Tradicional

Subir archivos por FTP a cualquier hosting que soporte HTML estático.

## 🌐 Navegadores Soportados

- ✅ Chrome (últimas 2 versiones)
- ✅ Firefox (últimas 2 versiones)
- ✅ Safari (últimas 2 versiones)
- ✅ Edge (últimas 2 versiones)
- ✅ Opera (últimas 2 versiones)

## 📱 Responsive Breakpoints

- 📱 Móvil: < 768px
- 📊 Tablet: 768px - 1024px
- 💻 Desktop: > 1024px

## ⚡ Rendimiento

- ⚡ **Carga rápida**: Sin backend, solo archivos estáticos
- 📦 **Ligero**: ~200KB total (sin imágenes)
- 🎯 **0 dependencias**: Solo Font Awesome vía CDN
- ♿ **Accesible**: HTML semántico y ARIA labels

## 🔧 Mejoras Futuras Sugeridas

- [ ] Añadir más proyectos conforme avances en DAM
- [ ] Blog para documentar tu aprendizaje
- [ ] Certificaciones y cursos completados
- [ ] Integración con GitHub API para mostrar repos automáticamente
- [ ] Google Analytics para métricas
- [ ] Sección de testimonios/recomendaciones

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver archivo `LICENSE` para más detalles.

## 👤 Autor

**Valentín De Gennaro**
- 🎓 Estudiante de DAM en CEACFP
- 📍 Valencia, España
- 📱 +34 641 02 59 95
- 🐙 GitHub: [@Valentindg2506](https://github.com/Valentindg2506)

## 🙏 Agradecimientos

- Font Awesome por los iconos
- Comunidad de desarrolladores DAM
- CEACFP por la formación

## 📊 Estadísticas del Código

- **HTML**: ~950 líneas
- **CSS**: ~1200 líneas
- **JavaScript**: ~480 líneas
- **Total**: ~2630 líneas de código

---

⭐ **¿Te gusta este portafolio?** 

Siéntete libre de usarlo como inspiración para el tuyo. Solo recuerda personalizarlo con tu información.

**Hecho con ❤️ por un estudiante DAM en Valencia, España**

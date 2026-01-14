# Valentina González Madariaga - Portfolio Profesional

Sitio web profesional bilingüe creado con Hugo para Valentina González Madariaga, PhD(c) en Sociología.

## 🌟 Características

- **Multiidioma**: Soporte completo para español e inglés con selector de idioma
- **Diseño Único**: Paleta de colores inspirada en Wes Anderson Soviético
- **Animaciones**: Landing page con partículas animadas usando tsParticles
- **Responsive**: Diseño completamente adaptable a dispositivos móviles y desktop
- **Secciones**:
  - Landing page con animación de fondo
  - Sobre Mí: Bio, áreas de interés, habilidades técnicas y educación
  - Proyectos: Portfolio de trabajos de investigación
  - Blog: Preparado para publicaciones futuras

## 🎨 Paleta de Colores

- **Verde Oliva** (#a7ba42): Color primario
- **Menta** (#95ccba): Color secundario
- **Amarillo Arena** (#f2cc84): Acento
- **Crema** (#fff0cb): Fondo
- **Rosa Pálido** (#ffdede): Highlight
- **Gris Oscuro** (#2c3e50): Texto

## 🚀 Desarrollo Local

### Requisitos Previos

- [Hugo Extended](https://gohugo.io/installation/) v0.121.1 o superior
- Git

### Instalación

```bash
# Clonar el repositorio
git clone https://github.com/vsgonzalezm/vsgonzalezm.github.io.git
cd vsgonzalezm.github.io

# Iniciar servidor de desarrollo
hugo server

# Construir sitio para producción
hugo --gc --minify
```

El sitio estará disponible en `http://localhost:1313/`

## 📁 Estructura del Proyecto

```
.
├── archetypes/          # Templates para nuevo contenido
├── assets/
│   └── css/
│       └── style.css    # Estilos personalizados
├── content/             # Contenido del sitio
│   ├── about/
│   │   ├── _index.es.md
│   │   └── _index.en.md
│   ├── projects/
│   │   ├── _index.es.md
│   │   └── _index.en.md
│   └── blog/
│       ├── _index.es.md
│       └── _index.en.md
├── i18n/                # Archivos de traducción
│   ├── es.toml
│   └── en.toml
├── layouts/             # Templates HTML
│   ├── _default/
│   │   ├── baseof.html
│   │   ├── list.html
│   │   └── single.html
│   └── index.html       # Landing page
├── static/              # Archivos estáticos
│   └── images/
└── hugo.toml            # Configuración de Hugo
```

## ✏️ Personalización

### Actualizar Contenido

1. **Sobre Mí**: Editar `content/about/_index.es.md` y `content/about/_index.en.md`
2. **Proyectos**: Editar `content/projects/_index.es.md` y `content/projects/_index.en.md`
3. **Blog**: Agregar posts en `content/blog/`

### Agregar Imagen de Perfil

Colocar la imagen en `static/images/` y actualizar la referencia en los archivos de About:

```markdown
<img src="/images/tu-foto.jpg" alt="Valentina González Madariaga">
```

### Crear Nuevo Post de Blog

```bash
hugo new blog/mi-nuevo-post.es.md
hugo new blog/mi-nuevo-post.en.md
```

## 🌐 Deployment

El sitio se despliega automáticamente a GitHub Pages mediante GitHub Actions cuando se hace push a la rama `main`.

### Configuración Manual

Si deseas desplegar manualmente:

```bash
# Construir el sitio
hugo --gc --minify

# Los archivos generados estarán en ./public/
```

## 📝 Tecnologías

- **[Hugo](https://gohugo.io/)**: Generador de sitios estáticos
- **[tsParticles](https://particles.js.org/)**: Animaciones de partículas
- **[Google Fonts](https://fonts.google.com/)**: Tipografías Oswald y Montserrat
- **GitHub Actions**: CI/CD automático
- **GitHub Pages**: Hosting

## 🎯 Características Técnicas

- SEO optimizado
- Performance optimizado
- CSS minificado en producción
- Fuentes con preconnect para carga rápida
- Sitemap automático
- RSS feed
- Navegación multiidioma fluida

## 📄 Licencia

© 2026 Valentina González Madariaga. Todos los derechos reservados.

---

**Desarrollado con Hugo** • [Documentación](https://gohugo.io/documentation/)

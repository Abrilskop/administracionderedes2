# Zay Shop - Plantilla Front-End para eCommerce

## Descripción General
Zay Shop es una plantilla front-end profesional y totalmente responsiva en HTML5 y CSS3, diseñada específicamente para plataformas de comercio electrónico. Desarrollada originalmente por TemplateMo, este proyecto proporciona una interfaz de usuario limpia, moderna y altamente interactiva, lista para ser integrada con cualquier arquitectura back-end (como PHP/Laravel, Node.js, Python/Django o .NET).

La plantilla utiliza un conjunto de tecnologías robusto para asegurar la compatibilidad entre navegadores modernos, un diseño centrado en dispositivos móviles (mobile-first) y transiciones fluidas, enfocándose en la correcta presentación del producto y la experiencia del usuario (UX).

---

## Características Principales

- **Diseño Totalmente Responsivo:** Se adapta perfectamente a todos los tamaños de pantalla (móviles, tabletas, monitores de escritorio) utilizando el sistema de cuadrículas (grid) de Bootstrap.  
- **Galerías de Productos Interactivas:** Deslizadores de imágenes integrados para productos destacados, exhibición de marcas corporativas y artículos relacionados.  
- **Selección Dinámica de Productos:** Lógica JavaScript personalizada para manejar la selección de cantidad y talla del producto a través de campos de formulario ocultos (hidden inputs), preparando los datos para su posterior procesamiento en el servidor.  
- **Mapas Interactivos:** Implementación de mapas de código abierto para mostrar la ubicación de la tienda física.  
- **Estructura Semántica:** Código HTML5 limpio y estructurado, optimizado para SEO y accesibilidad web.  

---

## Stack Tecnológico

- **Estructura y Estilos:** HTML5, CSS3  
- **Framework CSS:** Bootstrap v5.0.0-beta1  
- **Librería JavaScript:** jQuery v1.11.0 (junto con jQuery Migrate v1.2.1)  
- **Deslizadores y Carruseles:** Slick Carousel  
- **Mapas:** Leaflet.js (v1.7.1)  
- **Iconografía:** FontAwesome  
- **Tipografía:** Google Fonts (Roboto)  

---

## Estructura de Directorios
```bash
├── assets/
│   ├── css/
│   │   ├── bootstrap.min.css       # Framework base de Bootstrap
│   │   ├── custom.css              # Hoja de estilos para personalizaciones del desarrollador
│   │   ├── fontawesome.min.css     # Estilos de la librería de iconos
│   │   ├── slick-theme.css         # Estilos visuales del tema de Slick Carousel
│   │   ├── slick.min.css           # Estilos base estructurales de Slick Carousel
│   │   └── templatemo.css          # Estilos principales de la plantilla
│   ├── img/                        # Recursos de imagen (banners, productos, logos)
│   ├── js/
│   │   ├── bootstrap.bundle.min.js # JavaScript de Bootstrap (incluye Popper.js)
│   │   ├── custom.js               # Scripts personalizados del desarrollador
│   │   ├── jquery-1.11.0.min.js    # Librería base de jQuery
│   │   ├── jquery-migrate.min.js   # Plugin de migración para jQuery
│   │   ├── slick.min.js            # Script del motor de Slick Carousel
│   │   └── templatemo.js           # Lógica principal de interacción de la plantilla
│   └── webfonts/                   # Archivos de fuentes locales (Slick, FontAwesome)
├── about.html                      # Información corporativa y servicios
├── contact.html                    # Formulario de contacto y mapa interactivo
├── index.html                      # Página de inicio con banner principal y destacados
├── shop-single.html                # Vista detallada del producto y opciones de compra
└── shop.html                       # Catálogo principal de productos y filtros
```

---

## Arquitectura de Páginas y Flujo de Usuario

### index.html (Inicio)
Página principal con carrusel dinámico, categorías destacadas y productos promocionados.

### shop.html (Catálogo)
Interfaz de exploración con filtros por categorías y cuadrícula responsiva de productos.

### shop-single.html (Detalle del Producto)
Vista enfocada en ventas con galería de imágenes, selección de talla y cantidad, y productos relacionados.

### about.html (Sobre Nosotros)
Información corporativa, servicios y carrusel de marcas asociadas.

### contact.html (Contacto)
Formulario de contacto y mapa interactivo con Leaflet.

---

## Configuración e Instalación

### Clonar el repositorio
```bash
git clone <url-del-repositorio>
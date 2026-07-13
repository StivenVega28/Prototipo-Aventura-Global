# 🌍 Aventura Global

Sitio web de turismo y experiencias de viaje desarrollado como prototipo para la agencia de viajes Aventura Global. Ofrece una interfaz moderna y responsiva para showcasing de destinos turísticos en Colombia.

## ✨ Características

- 🎨 **Diseño Moderno**: Interfaz limpia y atractiva basada en el template Photon de HTML5 UP
- 📱 **Totalmente Responsivo**: Media queries optimizadas para desktop, tablet y móviles
- 🧭 **Navegación Fija**: Barra de navegación sticky con efecto blur
- 🎠 **Carrusel Interactivo**: Galería de destinos con navegación por puntos
- 🖼️ **Galería de Imágenes**: Grid layout con 3 columnas y efectos hover
- ⭐ **Testimonios**: Sección de reseñas de clientes con diseño atractivo
- 📧 **Formulario de Contacto**: Formulario funcional con validación
- 🎯 **Secciones Principales**:
  - Destinos populares
  - Galería de viajes
  - Experiencias de viajeros
  - Formulario de contacto
  - Footer con redes sociales

## 🚀 Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS**: Estilos y animaciones
- **JavaScript**: Funcionalidades interactivas (jQuery, scrolly, breakpoints)

## 📦 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/Prototipo-Aventura-Global.git
```

2. Navega al directorio del proyecto:
```bash
cd Prototipo-Aventura-Global
```

3. Abre el archivo `index.html` en tu navegador web preferido

No requiere instalación de dependencias ni servidor web, funciona directamente desde el sistema de archivos.

## 📁 Estructura del Proyecto

```
Prototipo-Aventura-Global/
├── assets/
│   ├── css/
│   │   ├── fontawesome-all.min.css
│   │   ├── main.css
│   │   └── noscript.css
│   ├── js/
│   │   ├── jquery.min.js
│   │   ├── jquery.scrolly.min.js
│   │   ├── browser.min.js
│   │   ├── breakpoints.min.js
│   │   ├── util.js
│   │   └── main.js
│   └── images/
│       └── (imágenes del template)
├── images/
│   ├── logo.png
│   ├── Destino1.jpg
│   ├── Destino2.jpg
│   ├── Destino3.jpg
│   ├── Destino4.jpg
│   ├── Destino5.jpg
│   ├── Destino6.jpg
│   ├── user1.jpg
│   ├── user2.jpg
│   └── user3.jpg
├── index.html
├── LICENSE.txt
├── README.md
└── README.txt
```

## 🎨 Características de Diseño

### Media Queries Implementadas
- **Desktop (>1024px)**: Layout completo con 3 columnas en galería
- **Tablet (768px-1024px)**: Ajustes de navegación y espaciado
- **Móvil (480px-768px)**: Menú vertical, 2 columnas en galería
- **Móvil Pequeño (<480px)**: Optimización de fuentes y padding

### Componentes Principales
- **Navbar**: Fija con blur, responsiva con menú hamburguesa en móvil
- **Hero Section**: Título animado con gradiente de fondo
- **Carrusel**: Navegación por radio buttons con transiciones suaves
- **Galería**: Grid system 3x2 con efectos hover
- **Testimonios**: Cards con foto de cliente y rating de estrellas
- **Formulario**: Inputs estilizados con focus states

## 🛠️ Personalización

### Colores Principales
- **Primario**: `#118888` (Turquesa oscuro)
- **Secundario**: `#6bd4c8` (Turquesa claro)
- **Acento**: `#FFC107` (Amarillo para ratings)
- **Fondo**: `#f8f9fa` (Gris claro para secciones alternas)

### Modificar Estilos
Los estilos principales se encuentran en `assets/css/main.css`. Las secciones personalizadas están etiquetadas con comentarios:
```css
/*=========================
    Barra de navegación
=========================*/
/*=========================
    GALERÍA DE IMÁGENES
=========================*/
/*=========================
    TESTIMONIOS
==========================*/
/*=========================
    FORMULARIO DE CONTACTO
==========================*/
```

## 📝 Secciones del Sitio

1. **Header/Hero**: Presentación principal con navegación
2. **Destinos**: Carrusel de destinos populares en Colombia
3. **Galería**: Grid de 6 imágenes de viajes
4. **Reseñas**: Testimonios de 3 clientes con experiencias
5. **Contacto**: Formulario para consultas y cotizaciones
6. **Footer**: Redes sociales y copyright

## 🤝 Contribución

Las contribuciones son bienvenidas. Si deseas mejorar este proyecto:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Agrega nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

**Nota**: Este es un prototipo educativo desarrollado como parte del programa SENA.


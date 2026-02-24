# CAEPA Concerts 🎟️

> **Nota:** El sitio se encuentra actualmente en fase de **Construcción y Preparación**. 🚧

Sitio web oficial para la venta de boletos de **CAEPA Concerts**. Ofrecemos acceso a las mejores obras de teatro interactivo, conciertos en vivo y shows teatrales de la temporada.

## 🎭 Características

- **Diseño Moderno & Elegante**: Interfaz premium en alto contraste (Blanco y Negro) diseñada para proyectar el ambiente íntimo y sofisticado del teatro.
- **Responsive Design**: Accesibilidad y fluidez total desde dispositivos móviles, tabletas y ordenadores de escritorio.
- **Micro-Animaciones**: Experiencia de usuario (UX) interactiva impulsada por suaves animaciones de scroll y un menú inteligente en móviles.
- **Tipografía**: Implementación de fuentes modernas como _Outfit_ (limpieza y lectura) y _Playfair Display_ (sofisticación clásica).

## 🗂️ Estructura del Proyecto

El proyecto está diseñado bajo una arquitectura limpia y directa basada en HTML5, CSS3 y JavaScript Vainilla, sin depender de *frameworks* de interfaz pesados.

```text
caepatickets/
├── index.html          # Página principal y estructura base
├── README.md           # Documentación del proyecto
└── assets/
    ├── css/
    │   └── style.css   # Estilos globales y paleta de colores
    ├── js/
    │   └── main.js     # Lógica de Interfaz, Scroll e inicialización de Iconos (Lucide)
    └── img/            # Recursos de imagen logotipos (Blanco y Negro)
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica.
- **CSS3**: Estilos personalizados (`var(--colors)`), Grid, Flexbox y Media Queries.
- **Vanilla JavaScript**: Gestión de clases (menú móvil, Intersection Observer).
- **[Lucide Icons](https://lucide.dev/)**: Librería de íconos minimalista vía CDN.

## 🚀 Instalación y Uso Local

Este proyecto no requiere de procesos de *build* extensivos ni dependencias de Node.js en su fase visual actual.

1. Clona este repositorio o descárgalo en tu entorno local (ej. en la carpeta `www` o `htdocs` de Laragon/XAMPP).
```bash
git clone https://github.com/AlfredoMarenco/caepatickets.git
```
2. Abre el archivo `index.html` en cualquier navegador web moderno (Chrome, Firefox, Safari, Edge).
3. **Opcional**: Para una mejor experiencia de desarrollo, utiliza una extensión como *Live Server* en VS Code.

## 🚧 Estado del Desarrollo

El sitio se ha configurado bajo un estado de "Próximamente", simulando enlaces deshabilitados y *placeholders* preventivos temporalmente mientras la cartelera se define y la pasarela de pagos / APIs se integra.

---
*© 2026 CAEPA Concerts. Diseñado y construido con orientación al arte.*

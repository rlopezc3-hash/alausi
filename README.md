# Alausí Vive

Propuesta web para agencia de turismo ficticia en Alausí, Chimborazo, Ecuador. Estética oscura en capas con profundidad 3D real hecha **solo con CSS** (perspective, transform-style, translateZ, rotateX/Y) — **cero líneas de JavaScript**.

## Tecnologías usadas

- **HTML5** — Estructura semántica (header, main, section, article, footer, form)
- **CSS3** — Custom properties, Grid, Flexbox, 3D Transforms, Animaciones, Media Queries
- **Sin JavaScript** — Interacciones puras con CSS (:hover, :focus, :active, checkbox hack)

## Instalación

No requiere instalación ni dependencias. Solo abre `index.html` en tu navegador:

```bash
# Clona el repositorio
git clone https://github.com/tu-usuario/alausi-3d.git

# Entra al directorio
cd alausi-3d

# Abre en tu navegador (ejemplo en Linux/macOS)
open index.html

# En Windows
start index.html
```

## Estructura del proyecto

```
alausi-3d/
├── index.html          # Inicio: hero 3D, pilares, estadísticas, atractivos, CTA
├── destinos.html       # 6 atractivos con tarjetas 3D
├── servicios.html      # 6 tours/paquetes con enlace directo a registro
├── nosotros.html       # Historia, misión, visión, valores, equipo
├── contacto.html       # Formulario de reserva HTML5 completo
├── css/
│   └── styles.css      # Hoja de estilos única (tema oscuro + 3D CSS)
├── images/             # 9 imágenes locales (tren, destinos, equipo, oficina)
├── entrada/            # Animación de entrada CSS-only (opcional)
│   ├── index.html
│   └── styles.css
├── AGENTS.md           # Instrucciones para agentes de código
└── README.md           # Este archivo
```

## Características principales

- **3D CSS puro** — Hero collage con 3 capas rotadas, tarjetas con rotación 3D en hover
- **Responsive** — Breakpoints en 1024px y 768px (mobile-first)
- **Accesible** — Semántica HTML5, focus-visible, alt text, labels, ARIA labels
- **Prefers-reduced-motion** — Respeta preferencia de movimiento reducido
- **Cero dependencias** — Sin build, sin npm, sin frameworks

## Licencia

Proyecto académico — Diseño de Sitios Web. Imágenes de Wikimedia Commons (CC BY-SA 3.0) y repositorio local.
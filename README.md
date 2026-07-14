# Diego Reyes Pallacan — Landing Page

Portafolio profesional. Página única con diseño responsivo, tema oscuro, cero dependencias externas.

## Demo

[https://diegoreyesdev.github.io/landing/](https://diegoreyesdev.github.io/landing/)

## Stack

| Capa | Tecnología | Notas |
|---|---|---|
| Estructura | HTML5 semántico | Single Page, secciones ancladas |
| Estilos | CSS3 + Custom Properties | Tema oscuro, responsive, sin frameworks |
| Interacción | Vanilla JavaScript (ES5 estricto) | Scroll suave, nav toggle, IntersectionObserver |
| Hosting | GitHub Pages | Despliegue automático desde `main` |
| Fuentes | System font stack | Sin CDNs externos |

## Estructura del proyecto

```
landing/
├── index.html              # Página única (SPA)
├── README.md               # Este archivo
├── .gitignore
└── assets/
    ├── css/
    │   └── estilos.css     # Estilos completos
    ├── js/
    │   └── script.js       # Lógica de navegación
    ├── img/
    │   └── ejemplopagina.png
    └── icons/
        └── favicon.ico
```

## Secciones

1. **Hero** — Nombre, rol, enlaces a GitHub, LinkedIn, Email
2. **Acerca de mí** — Resumen profesional, stack técnico
3. **Proyectos** — Cards con capturas, descripciones, tags tecnológicos y enlaces
4. **Contacto** — Canales directos (email, GitHub, LinkedIn)

## Principios de diseño

- **Cero dependencias externas**: sin CDNs, sin frameworks, sin trackers
- **Carga mínima**: CSS + JS combinados < 8 KB sin comprimir
- **Tema oscuro nativo**: respeta `prefers-color-scheme` en retina
- **Accesibilidad**: ARIA labels, focus visible, `prefers-reduced-motion`
- **Responsive**: mobile-first con breakpoints en 768px y 480px

## Despliegue

El proyecto se despliega automáticamente en GitHub Pages desde la rama `main`.

### Desarrollo local

```bash
git clone https://github.com/diegoreyesDev/landing.git
cd landing
python3 -m http.server 8080
# Abrir http://localhost:8080
```

No requiere `npm install` ni build step.

## Autor

Diego Aron Reyes Pallacan

- GitHub: [diegoreyesDev](https://github.com/diegoreyesDev)
- LinkedIn: [diegoreyes-dev](https://www.linkedin.com/in/diegoreyes-dev/)
- Email: diegoreyes.dev@gmail.com

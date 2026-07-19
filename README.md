<img width="1600" height="800" alt="Creator Trading Desk banner" src="https://github.com/user-attachments/assets/605640c3-f4a2-44ce-9541-8742bde3c7f4" />

# Creator Trading Desk | Tailwind CSS v4

Dashboard responsive creado como proyecto front-end para 4Geeks Academy. La interfaz simula una mesa de analisis tipo TradingView para social commerce, con metricas de comisiones, ventas, CTR, engagement, ROI, rendimiento por plataforma y oportunidades de optimizacion.

## Vista General

El proyecto esta disenado como una experiencia visual de dashboard profesional: oscuro, compacto, orientado a datos y preparado para verse bien en escritorio, tablet y movil. Utiliza HTML semantico, Tailwind CSS v4 desde CDN y una pequena hoja CSS de apoyo para detalles visuales.

## Tecnologias

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive_UI-0F172A?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Analytics-Dashboard-22C55E?style=for-the-badge)

## Caracteristicas

- Layout responsive con sidebar, area principal y panel lateral.
- KPIs de negocio: comisiones, ventas, CTR, engagement y ROI.
- Watchlist por plataforma/producto con senales de rendimiento.
- Grafico SVG integrado para rendimiento acumulado.
- Tabla de productos, alertas y oportunidades accionables.
- Estetica dark, inspirada en terminales financieras y TradingView.

## Estructura Del Proyecto

```text
.
├── index.html
├── css/
│   └── styles.css
├── assets/
│   └── images/
└── docs/
    └── checks/
```

## Como Ejecutarlo

Puedes abrir `index.html` directamente en el navegador o levantar un servidor local:

```bash
python3 -m http.server 8000
```

Despues entra en:

```text
http://localhost:8000
```

## Objetivo Del Proyecto

Construir un dashboard simple, visualmente solido y responsive usando Tailwind CSS, demostrando capacidad para crear interfaces analiticas modernas sin depender de frameworks JavaScript.

## Notas

- El proyecto no usa React, Vue ni JavaScript propio.
- Tailwind CSS se carga mediante `https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4`.
- `docs/checks/` conserva capturas usadas para revisar el diseno.
- El material temporal o privado debe quedarse fuera del repositorio.

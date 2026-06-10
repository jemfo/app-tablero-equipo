# Orden Equipo — Gestión de Tareas

App web de gestión de tareas para el equipo de **Análisis Comercial de VITOLEN SA**.

Es una app de **una sola página** (HTML/CSS/JS puro, sin servidor ni build) con backend en **Supabase** (datos compartidos en tiempo real entre usuarios).

## Uso

Abrir `index.html` en el navegador, o acceder a la versión publicada en GitHub Pages.

## Módulos

- **Tablero Equipo** — Kanban compartido (Supabase realtime), drag & drop entre estados.
- **Mi Orden** — Tabla priorizada con sistema de scoring (solo admin).
- **Análisis** — KPIs y gráficos por operador, estado y área (solo admin).

## Tecnología

- Frontend: HTML/CSS/JS, archivo único, sin framework
- Backend: Supabase (PostgreSQL + Realtime)
- Librerías por CDN: `@supabase/supabase-js`, `xlsx`, `Chart.js`, `chartjs-chart-treemap`

## Desarrollo

El historial de cambios se maneja con Git. Editar `index.html` y hacer commit por cada mejora.

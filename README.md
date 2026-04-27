# Evergreen Finance OS

Dashboard financiero personal y de negocio para Evergreen Ecosystem.

## Funcionalidades

- Panel de control consolidado con sueldos, gastos fijos, cajas y proyecciones
- Conversión multimoneda automática (USD / ARS / UYU) con tipo de cambio configurable
- Casa Chacra (UY) y Casa BA (ARS) con gastos detallados
- Caja Grande Grow y movimientos diarios
- Reportes y análisis de transferencias
- Gráficos y visualizaciones (Chart.js)

## Cómo usar

Abrí `index.html` en cualquier navegador moderno (Chrome, Safari, Firefox) en PC, tablet o celular.

Toda la información se guarda en el navegador (localStorage) — los datos quedan en el dispositivo donde la abrís.

## Deploy en Render

Esta app es 100% estática (HTML + JS + CSS en un solo archivo). Para servirla en internet:

1. Subí este repo a GitHub
2. En [Render](https://render.com) → **New** → **Static Site**
3. Conectá el repo `evergreengrower/Evergreen-finance-os`
4. **Build Command:** (vacío)
5. **Publish Directory:** `.`
6. Deploy → en menos de 1 minuto tenés una URL pública

## Próximos pasos (Supabase)

Para que los datos se sincronicen entre dispositivos (PC + tablet + celular):

1. Crear proyecto en [Supabase](https://supabase.com)
2. Crear tablas: `gastos`, `cajas`, `movimientos`, `tipo_cambio`
3. Reemplazar las llamadas a `localStorage` por llamadas a Supabase REST API
4. Agregar autenticación (opcional)

## Licencia

Privado — uso personal Evergreen.

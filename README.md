# 🎯 Centro de Mando — Misión Millonario 24/7

Live dashboard: **https://carlosreyesafk.github.io/mision-dashboard/**

Un panel de control en tiempo real que centraliza visualmente todos los frentes activos de una operación de ingresos 24/7: negocios corriendo, outreach, lanzamientos en cola y métricas clave.

## Qué muestra

- **Hero stats** — negocios corriendo, outreach enviados, respuestas humanas, ingresos (US$), productos en tienda
- **Meta del día** — barra de progreso con cuenta regresiva
- **Grid de negocios** — cada negocio con su modelo, precio, estado LIVE y link, con filtros por categoría
- **En lanzamiento** — cola de lo que está por encenderse
- **Otros frentes** — SaaS, freelance e inversiones

Los datos viven en `data.json` y el dashboard los recarga automáticamente cada 60 segundos, mostrando "actualizado hace X".

## Stack

HTML + CSS + JS vanilla. Cero dependencias de build, cero frameworks. `data.json` generado por script desde el ledger de la operación.

## Estructura

```
index.html   # dashboard (lee data.json)
data.json    # datos en vivo (regenerado cada hora por el control de la misión)
```

---
*Operado por Chachi · Misión Millonario 24/7*

# Graphite

**ES** — Tema grafito minimalista para Kino, en teléfono y Android TV, inspirado en Apple TV: negro profundo y grises neutros, acento y foco en blanco con texto negro, esquinas amplias, zoom generoso al enfocar, héroe enmarcado, riel flotante y un logo propio. Proyecto independiente y no oficial, sin relación con Apple.

**EN** — A minimal graphite Kino theme for phone and Android TV, Apple TV-inspired: deep black and neutral grays, white accent and focus with black text, generous corners, a bigger zoom on focus, a framed hero, a floating rail and its own logo. Independent, unofficial project, not affiliated with Apple.

## Instalar / Install

En Kino: **Plugins ▸ Agregar**, escribe / type: `ElCompitaDanny/kino-plugin-theme-graphite`.
Luego activa el tema en **Ajustes ▸ App ▸ Apariencia**.

Requiere Kino 0.9.87 o posterior (`apiVersion` 26); recomendado 0.9.93.
Requires Kino 0.9.87 or later (`apiVersion` 26); 0.9.93 recommended.

## Personalizable / Adjustable

Acento (blanco, plata, celeste o naranja), redondeo de tarjetas, escala tipográfica y fondo.

> **Nota sobre el color de acento.** Kino descarta el tema si el acento no tiene contraste suficiente con el texto blanco y vuelve al tema por defecto. Usa colores claros: este tema pone texto negro sobre el acento.
> *Kino falls back to its default theme when the accent has too little contrast with white text. Use light accents: this theme puts black text on the accent.*

## Archivos / Files

- `kino-plugin.json`: el tema, como datos (no ejecuta código) / the theme, as data.
- `plugin.js`: entrada mínima que no hace nada / minimal no-op entry.
- `icon.png`: icono del plugin / plugin icon.

## Validación / Validation

Con Node 18+ y el [SDK oficial](https://github.com/kinotvapp/kino-plugin-sdk): `node sdk/validate.mjs .`
Aún pendiente: ejecutar el validador oficial y probar este tema en dispositivo.

## Límite del tema / Scope

Un tema cambia los tokens y capas que Kino expone; no altera el catálogo ni el orden o contenido de las filas.

## Créditos / Credits

Estructura basada en el tema de ejemplo [Crimson](https://github.com/kinotvapp/kino-plugin-theme-crimson), de kinotvapp. El logo vectorial es propio.

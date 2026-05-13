---
title: Guía de ejemplo
description: Una guía en mi nuevo sitio de documentación de Starlight.
---

Guía de ejemplo para mostrar cómo se ve una guía en Starlight.

```css
/* Custom styles for the Midnight theme */
@custom-variant theme-midnight (&:where([data-theme="midnight"] *));
```

## Variantes personalizados

```css
/* Simple custom variant */
@custom-variant theme-midnight (&:where([data-theme="midnight"] *));
/* Variant with media query */
@custom-variant any-hover {
 @media (any-hover: hover) {
 &:hover {
 @slot;
 }
 }
}
```

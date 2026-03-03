# Menesescitas Design System

> **Minimal · Modern · Disruptive** — Sistema de diseño completo para Menesescitas Agency v1.0

![Version](https://img.shields.io/badge/version-1.0.0-0AFF6C?style=flat-square&labelColor=000)
![WCAG](https://img.shields.io/badge/WCAG-AA%20compliant-0AFF6C?style=flat-square&labelColor=000)
![Grid](https://img.shields.io/badge/grid-8px%20base-0AFF6C?style=flat-square&labelColor=000)
![License](https://img.shields.io/badge/license-MIT-0AFF6C?style=flat-square&labelColor=000)

---

## Vista previa

🔗 **[Ver guía interactiva →](https://menesescitas.github.io/Menesescitas-Design-System/menesescitas-design-guide.html)**

---

## ¿Qué incluye?

| Archivo | Descripción |
|---|---|
| `menesescitas-design-guide.html` | Guía interactiva con dark/light mode |
| `menesescitas-tokens.json` | Design tokens (colores, tipografía, spacing, motion) |
| `menesescitas-design-system.css` | Variables CSS + 30 componentes listos |

---

## Colores

| Token | Valor | Uso |
|---|---|---|
| `--c-electric` | `#0AFF6C` | Acento principal — botones, focus, highlights |
| `--c-crimson` | `#FF2D55` | Error / Destructivo |
| `--c-azure` | `#007AFF` | Info / Links |
| `--c-warning` | `#FFD60A` | Advertencias |

---

## Tipografía

| Nivel | Fuente | Tamaño | Uso |
|---|---|---|---|
| Hero | Bebas Neue | 96px | Mega headlines |
| Display | Bebas Neue | 72px | Secciones hero |
| H1–H4 | DM Sans 700 | 48–20px | Títulos |
| Body | DM Sans 400 | 17–15px | Texto general |
| Caption | DM Sans 500 | 12px | Labels, metadata |
| Mono | JetBrains Mono | 13px | Código |

---

## Uso rápido

### En HTML
```html
<link rel="stylesheet" href="menesescitas-design-system.css">

<!-- Botón primario -->
<button class="btn btn-primary">Contactar</button>

<!-- Card -->
<div class="card">
  <h3 class="text-h4">Proyecto</h3>
  <p class="text-body">Descripción del proyecto.</p>
</div>
```

### Variables CSS
```css
.mi-componente {
  background: var(--c-electric);
  color: var(--bg-base);
  padding: var(--space-4) var(--space-6);
  border-radius: var(--radius-md);
  transition: all var(--dur-normal) var(--ease-spring);
}
```

### Dark / Light mode
```html
<!-- Dark (default) -->
<html data-theme="dark">

<!-- Light -->
<html data-theme="light">
```

---

## Tokens en Figma

1. Instala el plugin **[Tokens Studio for Figma](https://tokens.studio/)**
2. Crea nuevo token set → Import JSON
3. Sube `menesescitas-tokens.json`
4. Activa sync con este repositorio para mantener tokens actualizados

---

## Espaciado (8px grid)

```
4px   → --space-1   micro
8px   → --space-2   XS
16px  → --space-4   SM
24px  → --space-6   MD
32px  → --space-8   LG
48px  → --space-12  XL
64px  → --space-16  2XL
96px  → --space-24  3XL
```

---

## Componentes (30)

Buttons · Inputs · Badges · Tags · Cards · Modal · Toast · Toggle · Checkbox · Select · Tabs · Avatar · Progress · Skeleton · Divider · Alert · Tooltip · Breadcrumb · Navbar · Dropdown · Slider · Accordion · Table · Stat Card · Empty State · y más.

---

## Accesibilidad

- ✅ WCAG 2.1 AA en todos los colores de texto
- ✅ Focus ring visible — `2px solid #0AFF6C`
- ✅ Touch targets mínimo `44×44px`
- ✅ `prefers-reduced-motion` respetado
- ✅ ARIA attributes en todos los componentes interactivos

---

## Stack recomendado

- **Figma** — Diseño + tokens sincronizados
- **Tokens Studio** — Sync design ↔ código
- **Style Dictionary** — Compilar tokens a múltiples formatos
- **GitHub Pages** — Hosting de la guía

---

*Creado con IA · Menesescitas Agency · 2026*

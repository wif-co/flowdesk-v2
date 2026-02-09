# FlowDesk v2 Theme

Dashboard-specific design tokens. Overrides global DESIGN_TOKENS.md for FlowDesk only.

**Aesthetic:** Dark mode tech dashboard — command center vibe

---

## Color Palette

| Token | Value | Usage |
|-------|-------|-------|
| `--color-background` | `#0F0F1A` | Page background, deep dark navy |
| `--color-surface` | `#1A1A2E` | Card backgrounds |
| `--color-surface-alt` | `#252542` | Elevated surfaces, hover states |
| `--color-border` | `#2A2A45` | Card borders, dividers |
| `--color-text` | `#E8E8F0` | Primary text |
| `--color-text-muted` | `#8888A0` | Secondary/label text |
| `--color-primary` | `#4ECDC4` | Cyan/teal — main accent |
| `--color-accent` | `#9D4EDD` | Purple — secondary accent |

## Semantic Colors

| Token | Value | Usage |
|-------|-------|-------|
| `--color-success` | `#4ECDC4` | Online, healthy, good |
| `--color-warning` | `#FFD93D` | Degraded, caution |
| `--color-error` | `#FF6B9D` | Down, blocked, error |
| `--color-info` | `#7B68EE` | Informational |

## Typography

| Element | Font | Weight |
|---------|------|--------|
| Headings | Source Sans 3 | 600 |
| Body | Source Sans 3 | 400 |

*Sans-serif throughout for tech aesthetic.*

## Component Patterns

### Cards
```css
background: var(--color-surface);
border: 1px solid var(--color-border);
border-radius: 12px;
box-shadow: 0 4px 20px rgba(0, 0, 0, 0.25);
```

### Status Badges
```css
/* Success/Online */
background: rgba(78, 205, 196, 0.15);
color: #4ECDC4;

/* Warning/Active */
background: rgba(255, 217, 61, 0.15);
color: #FFD93D;

/* Error/Blocked */
background: rgba(255, 107, 157, 0.15);
color: #FF6B9D;

/* Info/Idle */
background: rgba(123, 104, 238, 0.15);
color: #7B68EE;
```

### Progress Bars
```css
background: var(--color-surface-alt);
/* Fill uses semantic colors based on threshold */
```

---

*This theme applies to FlowDesk v2 only. Global DESIGN_TOKENS.md remains unchanged.*

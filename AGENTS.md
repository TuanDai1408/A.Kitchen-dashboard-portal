# Project & Workspace Guidelines

## Web & Dashboard UI Typography
- **Primary Font**: `Be Vietnam Pro`, sans-serif
- **Monospace Font**: `JetBrains Mono`, 'SF Pro Text', Menlo, Consolas, monospace
- **Tabular Figures**: `font-feature-settings: 'tnum' 1;` cho `.font-mono`, `.pos-mono`, `.font-receipt`

```css
@theme {
  --font-sans: 'Be Vietnam Pro', sans-serif;
}
:root {
  font-family: 'Be Vietnam Pro', sans-serif;
  --font-sans: 'Be Vietnam Pro', sans-serif;
}
body {
  font-family: 'Be Vietnam Pro', sans-serif;
}
.font-mono,
.pos-mono,
.font-receipt {
  font-family: 'JetBrains Mono', 'SF Pro Text', Menlo, Consolas, monospace !important;
  font-feature-settings: 'tnum' 1;
}
```

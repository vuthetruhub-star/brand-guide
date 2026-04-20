# [COMPANY_NAME] — Layout System

## Spacing Scale

```
4px   (xs)    — icon gaps, inline elements
8px   (sm)    — tight padding, tag spacing  
12px  (md-sm) — form element internal padding
16px  (md)    — default padding, list gaps
24px  (lg)    — card padding, component spacing
32px  (xl)    — section internal spacing
48px  (2xl)   — between components
64px  (3xl)   — between sections
96px  (4xl)   — major page-level breaks
128px (5xl)   — hero section padding
```

## Grid System

- **Max content width:** [1200px / 1440px / ____px]
- **Columns:** [12]
- **Column gap (gutter):** [24px desktop / 16px mobile]
- **Page margin:** [auto-center / 48px / 80px desktop, 16px mobile]

## Common Layouts

### Hero Section
- **Height:** [100vh / 80vh / auto with generous padding]
- **Content alignment:** [center / left-aligned / split]
- **Background:** [solid / gradient / image / video / animation]

### Content Section
- **Max text width:** [65ch / 720px] for readability
- **Vertical padding:** [64-96px desktop / 48px mobile]

### Feature Grid
- **Columns:** [2 / 3 / 4 on desktop, 1 on mobile]
- **Card gap:** [24px / 32px]

### Footer
- **Style:** [minimal / multi-column / mega footer]
- **Background:** [same as page / contrasting]

## Responsive Rules

| Breakpoint | Width      | Behavior                              |
|------------|------------|---------------------------------------|
| Mobile     | < 640px    | [Stack everything, single column]     |
| Tablet     | 640-1024px | [2-column grid, reduced spacing]      |
| Desktop    | > 1024px   | [Full layout, max-width container]    |

## Z-Index Scale

```
0     — base content
10    — sticky elements
20    — dropdowns
30    — fixed nav
40    — modals/drawers
50    — toasts/notifications
100   — tooltips
```

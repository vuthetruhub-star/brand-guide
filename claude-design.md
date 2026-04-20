# Claude Design System Instructions

## Company Overview

- **Company Name:** [COMPANY_NAME]
- **Industry:** [e.g., Digital Agency, SaaS, E-commerce, Education, etc.]
- **Tagline:** [Your tagline or slogan]
- **Website:** [https://your-website.com]
- **Description:** [2-3 sentences about what your company does]

## Brand Personality

- **Voice:** [e.g., Bold and direct / Warm and approachable / Technical and precise]
- **Tone:** [e.g., Professional but playful / Minimal and serious / High-energy and fun]
- **Keywords:** [3-5 words that define your brand feel, e.g., "innovative, bold, authentic"]

## Visual Identity

### Style Direction
<!-- Describe your overall visual aesthetic -->
- **Aesthetic:** [e.g., High-contrast retro, Clean minimal, Maximalist, Brutalist, etc.]
- **Mood:** [e.g., Dark and edgy, Light and airy, Futuristic, Organic]
- **Era/Inspiration:** [e.g., 90s hacker culture, Swiss design, Art Deco, Bauhaus]

### Color Palette

| Role            | Color Name   | Hex       | Usage                          |
|-----------------|-------------|-----------|--------------------------------|
| Primary         | [Name]      | #______   | Main brand color, CTAs         |
| Secondary       | [Name]      | #______   | Supporting elements            |
| Accent          | [Name]      | #______   | Highlights, hover states       |
| Background      | [Name]      | #______   | Page/section backgrounds       |
| Surface         | [Name]      | #______   | Cards, containers              |
| Text Primary    | [Name]      | #______   | Headings, body text            |
| Text Secondary  | [Name]      | #______   | Captions, labels               |
| Border          | [Name]      | #______   | Dividers, outlines             |
| Success         | [Name]      | #______   | Positive states                |
| Warning         | [Name]      | #______   | Caution states                 |
| Error           | [Name]      | #______   | Error states                   |

### Typography

| Role          | Font Family   | Weight     | Size      | Line Height | Letter Spacing |
|---------------|--------------|------------|-----------|-------------|----------------|
| Display/Hero  | [Font Name]  | [700/Bold] | [48-72px] | [1.1]       | [-0.02em]      |
| Heading H1    | [Font Name]  | [700/Bold] | [36-48px] | [1.2]       | [-0.01em]      |
| Heading H2    | [Font Name]  | [600/Semi] | [28-36px] | [1.2]       | [0]            |
| Heading H3    | [Font Name]  | [600/Semi] | [20-24px] | [1.3]       | [0]            |
| Body Large    | [Font Name]  | [400/Reg]  | [18px]    | [1.6]       | [0]            |
| Body Regular  | [Font Name]  | [400/Reg]  | [16px]    | [1.5]       | [0]            |
| Body Small    | [Font Name]  | [400/Reg]  | [14px]    | [1.5]       | [0]            |
| Caption       | [Font Name]  | [400/Reg]  | [12px]    | [1.4]       | [0.02em]       |
| Code/Mono     | [Font Name]  | [400/Reg]  | [14px]    | [1.5]       | [0]            |
| Button/Label  | [Font Name]  | [600/Semi] | [14px]    | [1]         | [0.05em]       |

**Font Sources:**
- [Font Name]: [Google Fonts / Adobe Fonts / Self-hosted / CDN URL]
- [Font Name]: [Google Fonts / Adobe Fonts / Self-hosted / CDN URL]

### Spacing System

| Token   | Value   | Usage                        |
|---------|---------|------------------------------|
| xs      | [4px]   | Inline element gaps          |
| sm      | [8px]   | Tight spacing                |
| md      | [16px]  | Default padding/margin       |
| lg      | [24px]  | Section internal spacing     |
| xl      | [32px]  | Component gaps               |
| 2xl     | [48px]  | Section spacing              |
| 3xl     | [64px]  | Major section breaks         |
| 4xl     | [96px]  | Page-level spacing           |

### Border & Radius

| Element        | Radius   | Border                              |
|----------------|----------|--------------------------------------|
| Buttons        | [0/4/8px]| [none / 1px solid var(--border)]     |
| Cards          | [0/8/12px]| [none / 1px solid var(--border)]    |
| Inputs         | [0/4/8px]| [1px solid var(--border)]            |
| Modals         | [0/8/16px]| [none / 1px solid var(--border)]    |
| Avatars        | [50%]    | [none / 2px solid var(--primary)]    |
| Tags/Badges    | [0/4/999px]| [none / 1px solid var(--border)]   |

### Effects & Textures

- **Shadows:** [none / subtle / dramatic] — [e.g., "0 2px 8px rgba(0,0,0,0.1)"]
- **Blur/Glass:** [yes/no] — [e.g., "backdrop-filter: blur(12px)"]  
- **Gradients:** [yes/no] — [describe gradient style]
- **Noise/Grain:** [yes/no] — [e.g., "subtle noise overlay at 5% opacity"]
- **Animations:** [minimal / moderate / rich] — [describe motion style]
- **Hover effects:** [describe preferred hover behavior]

### Iconography

- **Style:** [outline / filled / duotone / custom]
- **Size:** [16/20/24px default]
- **Stroke width:** [1.5/2px]
- **Icon library:** [Lucide / Heroicons / Phosphor / Custom / None]

## Layout Principles

### Grid
- **Max width:** [1200px / 1440px / full-width]
- **Columns:** [12-column / custom]
- **Gutter:** [16px / 24px / 32px]
- **Margin (mobile):** [16px / 20px]
- **Margin (desktop):** [auto-centered / 48px / 80px]

### Responsive Breakpoints
| Name     | Width     |
|----------|-----------|
| Mobile   | < 640px   |
| Tablet   | 640-1024px|
| Desktop  | > 1024px  |

## Component Guidelines

### Buttons
- **Primary:** [describe look — e.g., "solid green background, black text, uppercase, no radius"]
- **Secondary:** [describe look]
- **Ghost/Outline:** [describe look]
- **Sizes:** [sm: 32px / md: 40px / lg: 48px height]
- **Text style:** [uppercase / capitalize / normal]

### Cards
- **Background:** [surface color / transparent / glass]
- **Border:** [describe]
- **Padding:** [16px / 24px]
- **Hover:** [describe hover behavior]

### Navigation
- **Style:** [top bar / sidebar / minimal / mega menu]
- **Mobile:** [hamburger / bottom tab / drawer]
- **Active state:** [describe how active links look]

### Forms & Inputs
- **Style:** [outlined / filled / underlined]
- **Focus state:** [describe focus ring or highlight]
- **Error state:** [describe error styling]
- **Label position:** [above / floating / inline]

## Do's and Don'ts

### ✅ Do
- [e.g., "Always use monospace font for headings"]
- [e.g., "Maintain high contrast ratios"]
- [e.g., "Use generous whitespace"]
- [e.g., "Keep CTAs bold and prominent"]
- [Add more...]

### ❌ Don't
- [e.g., "Don't use rounded corners larger than 4px"]
- [e.g., "Don't use pastel or muted colors"]
- [e.g., "Don't mix more than 2 font families"]
- [e.g., "Don't use generic stock photography"]
- [Add more...]

## Asset Types This System Applies To

- [ ] Landing pages
- [ ] Pitch decks / Presentations
- [ ] Social media graphics
- [ ] Email templates
- [ ] App UI / Prototypes
- [ ] One-pagers / Flyers
- [ ] Blog post headers
- [ ] Dashboard interfaces
- [ ] Marketing materials

# EXAMPLE: D1AGENCY — Filled Template

> This is an example of how to fill in the template based on
> the info from your screenshot. Copy values from here into
> the actual template files.

## claude-design.md (filled)

## Company Overview
- **Company Name:** D1AGENCY
- **Industry:** Digital Agency
- **Tagline:** Digital systems for bold brand growth
- **Website:** https://d1agency.com
- **Description:** D1AGENCY is a digital agency with a technology-first visual language built around structured layouts, hacker-inspired green, strong typography, and restrained digital effects. The brand should feel sharp, modern, system-driven, and highly usable across both dark and light interfaces.

## Visual Identity

### Style Direction
- **Aesthetic:** High-contrast, technology-first, hacker-inspired, clean and modern
- **Mood:** Dark, digital, confident, precise, user-friendly
- **Era/Inspiration:** Contemporary system dashboards, terminal UI, advanced digital product environments
- **Design Goal:** Preserve the terminal / hacker DNA while making the interface more readable, modular, and practical for real-world use

### Theme Modes

#### Dark Mode
| Role | Hex | Usage |
|---|---|---|
| Primary | #00FF41 | CTAs, highlights, active text |
| Secondary | #0D7A2E | Secondary elements, labels |
| Accent | #33FF66 | Hover, focus, micro-highlights |
| Background | #000000 | Main background |
| Surface | #0A0A0A | Cards, panels |
| Surface Alt | #111111 | Elevated panels, modals |
| Text Primary | #00FF41 | Headings, hero text, key UI text |
| Text Secondary | #00CC33 | Paragraphs, support copy |
| Border | #003300 | Dividers, outlines |
| Glow | rgba(0,255,65,0.14) | Controlled local glow |

#### Light Mode
| Role | Hex | Usage |
|---|---|---|
| Primary | #0D7A2E | CTAs, links, active UI |
| Secondary | #2F5E4D | Secondary UI, labels |
| Accent | #00FF41 | Small highlights only |
| Background | #F5F5F2 | Main background |
| Surface | #FFFFFF | Cards, panels |
| Surface Alt | #ECEDE8 | Secondary panels |
| Text Primary | #0F3D2E | Main headings, body text |
| Text Secondary | #2F5E4D | Descriptions, secondary copy |
| Border | #C9D4CC | Dividers, outlines |
| Glow | rgba(13,122,46,0.08) | Focus and hover glow |

### Typography
| Role | Font Family | Weight | Usage |
|---|---|---|---|
| Display / Hero | Orbitron | 700 | Hero, high-impact headings |
| Heading | Orbitron | 600–700 | H1, H2, key section titles |
| Body | Source Sans 3 | 400 | Main content, descriptions, longer reading |
| UI Text | Source Sans 3 | 400–600 | Navigation, forms, buttons |
| Code / Label | JetBrains Mono | 400 | Labels, tags, system text, metadata |

### Shapes & Layout
- **Corner Style:** Controlled technical rounding
- **Default Radius:** 8px
- **Shape Language:** Slightly softened rectangles with restrained, system-like corners
- **Layout Style:** Clean, modular, structured, dashboard-like
- **Visual Intent:** The interface should feel engineered and usable, not playful, pill-heavy, or overly soft

### Spacing

#### Glow / Elevation
- **Elevation Style:** Green glow replaces traditional drop shadow
- **Glow Usage:** Use subtle local glow for active states, selected panels, primary CTAs, and important interface moments
- **Rule:** Depth should come from glow, border contrast, and panel layering, not heavy blur shadows

#### Motion
- **Motion Style:** Technical, responsive
- **Easing:** 
  - Ease-out: `cubic-bezier(0.2, 0.8, 0.2, 1)`
  - Snap: `cubic-bezier(0.5, 0, 0.1, 1)`
- **Durations:** 120ms / 200ms / 320ms / 2400ms
- **Usage:** Short feedback for hover and transitions, slower timing for scan or ambient terminal effects
- **Cursor Blink:** Around 1000–1060ms
- **Glitch Rule:** Only for key identity moments, never ambient

#### Radius System
- **Default:** 8px for buttons, inputs, cards, panels
- **Sharp State:** 0px only for intentional terminal accents or hard-edged framing
- **Pill Rule:** Reserved for rare chips or status badges, never as the default system shape

#### Spacing Scale
- **System:** stepped scale
- **Tokens:** XS 4px, SM 8px, MD 16px, LG 24px, XL 32px, 2XL 48px, 3XL 64px, 4XL 96px, 5XL 128px
- **Rule:** Use stepped spacing consistently; avoid arbitrary values unless needed for precise alignment

### Effects & Textures
- **Shadows:** None, low or very subtle green ambient glow
- **Gradients:** No
- **Noise / Grain:** Moderate CRT scanline effect with restrained soft noise
- **Animations:** Terminal typing, slower cursor blink, minimal glitch on key interactions
- **Hover Effects:** Green glow, brightness lift, subtle flicker
- **CRT Treatment:** Visible but controlled; atmospheric, not distracting

### UI Principles
- Keep green as the core brand identity in both dark and light mode
- In light mode, use darker green text for readability instead of neon green body copy
- Prioritize readability, modularity, and interaction clarity over visual aggression
- Keep motion short, deliberate, and system-like
- Keep glow local and controlled
- Maintain a technical interface feel without becoming harsh or visually noisy

### Do
- Use Orbitron for high-impact display moments
- Use Source Sans 3 for readable UI and body content
- Use JetBrains Mono for labels, tags, and system accents
- Use 8px controlled rounding as the default UI radius
- Use green glow instead of conventional shadow
- Use the stepped 4px–128px spacing system consistently
- Keep layouts modular, spacious, and structured

### Don’t
- Don’t use pure white as the main light background
- Don’t use neon green for long-form light-mode body text
- Don’t overuse glitch, flicker, scanlines, or glow
- Don’t use overly soft, playful, or pill-heavy shapes as the default UI language
- Don’t use arbitrary spacing values that break the system
- Don’t let visual effects reduce readability or usability
```

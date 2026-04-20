# 🎨 [COMPANY_NAME] Design System

> This repository contains the design system and brand guidelines for **[COMPANY_NAME]**.  
> It is intended to be linked with **Claude Design** so that all generated assets automatically follow our brand identity.

## Quick Start

1. Replace all `[PLACEHOLDER]` values with your actual brand info
2. Push to GitHub
3. Link this repo in Claude Design → "Link code on GitHub"

## Structure

```
├── design-system/
│   ├── brand.md          # Brand voice, personality, do's and don'ts
│   ├── colors.css        # Color tokens as CSS variables
│   ├── typography.css    # Font definitions and type scale
│   └── layout.md         # Spacing, grid, and layout rules
├── tokens/
│   └── tokens.json       # Design tokens in JSON format
├── components/
│   ├── buttons.html      # Button component examples
│   ├── cards.html        # Card component examples
│   └── navigation.html   # Navigation component examples
├── assets/
│   └── (logos, icons, fonts go here)
└── claude-design.md      # Instructions for Claude Design
```

## Notes for Claude Design

See `claude-design.md` for the complete prompt context that Claude Design will use when generating assets.

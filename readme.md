# Cursor Landing Page – UI Recreation

This repository contains a **static UI recreation** of the Cursor landing page, built using **HTML and CSS only**.  
The project focuses on accurately replicating the **layout, typography, color system, and visual hierarchy** of the original website, without adding application logic or interactivity beyond basic hover effects.

> ⚠️ This is a UI recreation for educational purposes and is not affiliated with or endorsed by Cursor.

---

## Recreated Sections

### Navigation Bar
- Fixed header layout
- Cursor brand logo
- Navigation links (Features, Enterprise, Pricing, Resources)
- Call-to-action buttons (Sign in, Download)
- Dark theme styling consistent with the original site

### Hero Section
- Primary headline and sub-headline
- Download CTA button
- Editor background image
- Custom IDE mockup built entirely using HTML and CSS, including:
  - Window controls
  - Multi-column layout (review, build, output)
  - Hover-based “Get Cursor” interaction

### Trusted Partners
- Logos of companies using Cursor
- Center-aligned layout
- Monochrome logo treatment for visual consistency

### Features Section
Three feature blocks were recreated:
- Agent-based development
- AI-powered autocomplete
- Multi-surface integration (GitHub, Slack, Terminal)

Each feature includes:
- Descriptive copy
- CTA links
- Visual previews / screenshots

### Testimonials
- Grid-based testimonial layout
- Quote cards with avatars
- Author name and designation
- Dark card styling matching the site’s design language

---

## Fonts

### Primary Typeface
**CursorGothic**

Loaded locally using `@font-face` with the following variants:
- Regular (400)
- Italic (400)
- Bold (700)
- Bold Italic (700)

Fallback stack:
```css
"CursorGothic", "CursorGothic Fallback", system-ui,
"Helvetica Neue", Helvetica, Arial, sans-serif
```
## Fonts
```
--primary: #13120a;              /* Main background */
--buttonBg: #edecec;             /* Primary buttons */
--text-color: #edecec;           /* Primary text */
--text-color-secondary: #acaba7; /* Secondary text */
--text-color-tertiary: #72706c;  /* Muted text */
--border-color: #292821;         /* Borders & dividers */
```
## Tech Stack
- HTML5 (semantic markup)
- CSS3
- Flexbox & Grid
- CSS variables
- Custom fonts via @font-face
- No JavaScript
- No external libraries or frameworks

## DISCLAIMER
This project is intended solely for educational and learning purposes.
All product names, logos, and assets belong to their respective owners.
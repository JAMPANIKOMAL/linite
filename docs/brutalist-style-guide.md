# [SYSTEM ZWEI] - Brutalist Design System

## 1.0 Philosophy

Brutalist web design prioritizes raw functionality, visible structure, and bold presence. Inspired by command-line interfaces and technical schematics, it focuses on clarity and utility.

**Core Principles:**
- **Honesty:** Expose grids and containers with hard borders.
- **Functionality First:** Every element has a clear purpose; no unnecessary decoration.
- **Clarity:** Direct, efficient information with clear hierarchy.
- **Boldness:** Strong, unapologetic visual statements.

## 2.0 Colors

Strictly monochromatic for high contrast.

- **Primary Background:** `#000000` (Black)
- **Primary Text & Borders:** `#FFFFFF` (White)
- **Button Hover:** Background `#000000`, Text `#FFFFFF`

## 3.0 Typography

Single monospace font for technical feel.

- **Font Family:** Space Mono
- **Body:** Regular 400, 16px (`1rem`), `#FFFFFF`
- **Headings:** Bold 700, Uppercase
    - **H1:** 20px (`1.25rem`)
    - **H2:** 48–72px (`3–4.5rem`), tight leading
    - **H3/H4:** 12–14px (`0.75–0.875rem`)
- **Links:** Hover underline; navigation links in brackets (e.g., `[01_INFO]`)

## 4.0 Layout & Structure

Rigid, grid-based, emphasizing structure.

- **Borders:** 2px solid `#FFFFFF`
- **Corners:** Sharp, 0px border-radius
- **Spacing:** Consistent, multiples of 8px
- **Wrapper:** Main container with visible border for "screen-within-a-screen" effect

## 5.0 Components

### 5.1 Buttons

Functional, high-contrast, clearly interactive.

- **Class:** `.btn-primary`
- **Border:** 2px solid `#FFFFFF`
- **Background:** `#FFFFFF`
- **Text:** `#000000`, Bold 700, Uppercase
- **Padding:** 12px 24px (`0.75rem 1.5rem`)
- **Hover:** Background `#000000`, Text `#FFFFFF`

**Example:**
```html
<a href="#" class="btn-primary">INITIATE CONTACT</a>
```

### 5.2 Containers

Group content and define layout.

- **Class:** `.bordered-box`
- **Border:** 2px solid `#FFFFFF`
- **Padding:** 16–32px (`1–2rem`)

### 5.3 Footer Grid

Structured metadata or secondary info.

- **Layout:** 2 or 4-column grid
- **Content:** Bold, uppercase title + plain text

## 6.0 Tone of Voice

- **Direct & Technical:** Clear, concise, technical language
- **Imperative:** Action-oriented verbs (e.g., "Initiate," "Execute," "View Files")
- **Uppercase:** Headings and buttons for emphasis and importance

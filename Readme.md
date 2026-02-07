# Mintlify-Inspired Documentation Layout (Desktop-First)

This project is a **desktop-first documentation-style website** inspired by the layout and visual style of the Mintlify documentation interface.  
It focuses on clean structure, readable typography, and a modern sidebar-driven documentation layout using **pure HTML and CSS**.

---

## Sections Recreated

The following major sections of the documentation layout were recreated:

1. **Top Navigation Bar**
   - Logo
   - Search or utility area
   - Clean, minimal layout
   - Sticky behavior

2. **Sidebar Navigation**
   - Vertical navigation menu
   - Section grouping
   - Active link styling

3. **Main Documentation Content Area**
   - Page title
   - Section headings
   - Paragraph content
   - Lists and structured content blocks

4. **On-This-Page (Right Sidebar)**
   - Table of contents
   - Quick navigation links to sections

5. **Background Visual Layer**
   - Decorative gradient or illustration
   - Soft fade into content area
   - Documentation-style readable layout

6. **Footer (if included)**
   - Basic links
   - Copyright or brand text

---

## Fonts Used

### Primary Font

- **Inter** (or system sans-serif stack)
- Used for:
  - Body text
  - Navigation
  - Headings

Example font stack:

```css
font-family:
  Inter,
  system-ui,
  -apple-system,
  sans-serif;
```

| Purpose            | Color           | Hex       |
| ------------------ | --------------- | --------- |
| Main background    | White           | `#ffffff` |
| Sidebar background | Light gray      | `#f8f9fb` |
| Primary text       | Dark gray       | `#111827` |
| Secondary text     | Muted gray      | `#6b7280` |
| Border color       | Soft gray       | `#e5e7eb` |
| Accent color       | Blue            | `#2563eb` |
| Hover background   | Very light gray | `#f3f4f6` |

## Project structure

```
docs-site/
│
├── index.html
├── style.css
│
├── images/
│   └── background assets
│
└── README.md
```

## Project setup

```bash
git clone <repository-url>

```

```bash
cd docs-site
```

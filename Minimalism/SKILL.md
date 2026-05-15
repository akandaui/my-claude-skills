---
name: white-space-design
description: >
  Apply white space and minimalism principles to UI/UX design work — based on the UXPin "Zen of White Space" framework. Use this skill whenever the user asks about spacing, negative space, layout breathing room, visual hierarchy through space, minimalism in web design, padding/margin decisions, or when reviewing/critiquing a UI for spacing issues. Also trigger when the user says things like "too cluttered", "needs more breathing room", "feels cramped", "spacing feels off", "should I use more white space", "minimalist design", or asks to audit/review a layout for spacing quality. This skill teaches, reviews, and generates spacing-aware designs grounded in proven principles.
---

# White Space Design Skill

Based on the UXPin "Zen of White Space in Web UI Design" (Cao, Rocheleau, Zieba, Ellis).

Reference PDF is bundled at `references/zen-of-white-space.pdf` — load it when you need to cite or quote specific sections.

---

## Core Framework

### What Is White Space?
White space (negative space) = any screen space between existing elements. It does NOT need to be white or blank. Patterned, colored, or textured backgrounds all count. The key: it is intentional emptiness that shapes how the user perceives and navigates content.

### Four Things White Space Controls
1. **Eye-scanning** — Macro space between big elements guides where users look
2. **Legibility** — Micro space around letters/lines/paragraphs controls readability
3. **Aesthetics** — Overall visual organization and perceived quality
4. **Luxury perception** — More space = more premium; less space = more cluttered/cheap

---

## The Two Types: Macro vs Micro

### Macro White Space
Space between large elements:
- General page composition
- Separation between sections
- Text columns
- Margins and padding
- Space within graphics/images

**Rule**: Larger distances push harder. Too much space violates Gestalt Principles and weakens element relationships.

### Micro White Space
Space between small elements:
- Letters (tracking/kerning)
- Lines of text (line-height)
- Paragraphs
- List items
- Buttons and icons

**Rule**: Line height should be ~1.5× the type size. Close proximity suggests functional similarity — use micro spacing to imply relationships between interactive elements.

---

## The Two Modes: Passive vs Active

### Passive Space
The **bare minimum** — enough space to make the interface comprehensible without drawing attention to itself.
- Goes unnoticed by the user
- Prevents clutter and illegibility
- Separates navigation elements, sections, and content blocks

> "The main purpose of passive white space is that it goes unnoticed."

### Active Space
**Intentional** space used to guide visual flow and draw attention.
- Surrounding an element with large space makes it the focus
- Minimizing space "hides" elements (e.g., legal text, copyright)
- Used to create hierarchy and lead users to primary interactions

> Macro white space is often used actively to draw attention to the page's single main focus.

---

## Minimalism Principles

Minimalism = removing noise so users focus on content. It is a **philosophy**, not just an aesthetic.

### Amount of Elements
- Fewer elements = each element is more powerful
- Too many elements → choice paralysis → users abandon
- Easiest way to gain white space: remove elements
- Subtract interface objects until the design almost fails, then test

### Perception of Luxury
| Space Level | Perception |
|---|---|
| Heavy white space | Luxurious, high-end, expensive |
| Balanced white space | Affordable but quality |
| Little white space | Cheap, low-quality, cluttered |

### When NOT to Use Minimalism
Minimalism does **not** work well for:
- Ad-heavy sites (ads break the aesthetic)
- Sites with many features or user options
- Content designed for children
- General eCommerce with complex information architecture
- Blogs or content-heavy publications

---

## The Perils: Too Little vs Too Much

### Too Little Space
- Elements feel cramped
- Text becomes intimidating → users bounce
- Visual hierarchy collapses — headings and paragraphs blur together
- Content areas blend into "a large amorphous blob"

### Too Much Space
- Low information density
- Content feels fragmented
- Excessive scrolling required
- Page hierarchy becomes unclear
- Especially damaging on mobile

---

## White Space Mastery: Practice Method

1. **Study live websites** — Train your eye by analyzing what works vs what doesn't
2. **Wireframe and prototype** — Work from structure before visual detail
3. **Clone existing layouts** — Rebuild a site from scratch to feel the spacing
4. **High-fidelity mockup** — Refine details: line height, section spacing, icon padding
5. **Never forget your users** — Spacing must match audience expectations and mental model

> "Aim to clearly recognize white space in different websites because training your eye improves your imagination."

---

## Visual Balance in Minimalist Layouts

Four forms of balance:
- **Horizontal symmetry** — Equal visual weight on both sides
- **Approximate symmetry** — Different elements, same visual weight (large + small groupings)
- **Radial symmetry** — Focal point in center, elements radiate outward
- **Asymmetry** — Purposeful contrast of shapes, colors, sizes (hardest to execute)

Use contrast (color, size, shape, location, scale) to create direction and hierarchy.

---

## How to Apply This Skill

### When Reviewing a Design
1. Identify macro issues first — section spacing, margins, composition
2. Then check micro — line height, letter spacing, button padding
3. Classify each problem: passive (illegibility) or active (wrong focus)
4. Ask: does the amount of space match the brand's perceived value tier?
5. Ask: does minimalism suit this content type and audience?

### When Designing from Scratch
1. Start from content requirements — list only what is necessary
2. Define sections (aim for 5 or fewer)
3. Strip elements: logo, nav, body content, CTA — remove everything else
4. Apply passive spacing first (legibility baseline)
5. Apply active spacing to guide the user's eye to the primary action
6. Determine minimalism level based on content density and audience

### When Generating CSS/Code Spacing Values
Use these as starting points:
- Line height: `1.5em` (body text)
- Paragraph margin: `1–1.5em`
- Section gap: `4–8rem` depending on macro hierarchy
- Golden ratio between two related elements: `1:1.618`
- Button padding: `0.75em 1.5em` minimum; more for luxury feel

---

## Key Principles Summary

| Principle | Application |
|---|---|
| Macro before micro | Fix section spacing before tweaking letter spacing |
| Active before passive | Decide what to highlight, then set baseline spacing |
| Match space to brand tier | Premium = generous space; mass market = denser |
| Subtract, don't add | Remove elements to gain space rather than compressing |
| Test the tipping point | Remove until it almost breaks, then stop |
| Know your user | Children, bargain shoppers, luxury buyers all need different spacing |
| Minimalism ≠ white | Negative space can be any color; texture excluded |

---

## Tools Referenced in the Book

- **Modularscale** — Font size ratio calculator
- **Type Scale** — Visual typography scale with Google Fonts
- **Typetester** — Paragraph style comparison tool
- **Gridpak / Responsify** — Grid and column generators
- **siteInspire / awwwards** — Inspiration galleries for white space study
- **Golden ratio calculator** — For spacing two related elements at 1:1.618

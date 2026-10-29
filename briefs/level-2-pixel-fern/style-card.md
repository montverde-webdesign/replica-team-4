# Style Card: Pixel Fern Games (Level 2)

Match `mockup-desktop.png` and `mockup-phone.png`. `parts-map.png` shows who builds what.

## Fonts

Paste this in `css/base.css`, right below the comment:

```css
@import url("https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500;700&family=Inter:wght@400;600&display=swap");
```

| Used for | Font |
| --- | --- |
| Headings and the logo | `"Space Grotesk", sans-serif` |
| Everything else | `"Inter", sans-serif`, 17px |

## Colors

| Color | Hex | Where |
| --- | --- | --- |
| Fern green (dark) | `#1f3d2b` | Header, footer, main text, borders, dark button |
| Mint white | `#f3f7f2` | Page background |
| Lime | `#9be15d` | "Play Free" button, footer headings |
| Pink | `#ff6b9a` | "Indie game studio" tag, "Play now" links |
| Pale green | `#e3f4d7` | Team background, genre tags |
| White | `#ffffff` | Cards, nav links, footer text |
| Gray green | `#4f6b58` | Team roles |

## Measurements

| Thing | Size |
| --- | --- |
| Big heading (h1) | 54px |
| Section headings (h2) | 38px |
| Page width | max 1100px, centered |
| Hero image | 480px wide, 6px border, 16px corners |
| Cards | 3px border, 16px corners, 24px gap |
| Team photos | 140px wide, perfect circles |

## CSS you might need

- The hero is a flex row: text on the left (`flex: 1;`), image on the right
- `border-radius: 50%;` turns a square image into a circle
- `text-transform: uppercase;` for "INDIE GAME STUDIO"
- `background-color: transparent;` for the outline button
- `display: inline-block;` lets a `<span>` or `<a>` have padding like a box

## Phone size (required)

At `@media (max-width: 760px)`: the nav, hero, cards, team, and footer columns all stack.

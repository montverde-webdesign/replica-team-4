# Style Card: Neon Tide Festival (Level 3)

Match `mockup-desktop.png` and `mockup-phone.png`. `parts-map.png` shows who builds what. This level uses a few CSS properties we haven't covered in class. Look them up on MDN.

## Fonts

Paste this in `css/base.css`, right below the comment:

```css
@import url("https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Poppins:wght@400;600&display=swap");
```

| Used for | Font |
| --- | --- |
| Headings, the logo, big numbers, prices | `"Bebas Neue", sans-serif` (only comes in one weight: use `font-weight: 400;`) |
| Everything else | `"Poppins", sans-serif`, 17px |

## Colors

| Color | Hex | Where |
| --- | --- | --- |
| Night | `#0d0b26` | Page background, ticket cards |
| Deep purple | `#1a1745` | Stats strip, lineup cards, ticket section |
| Line purple | `#2c2866` | Borders, artist pills |
| Neon pink | `#ff3d9a` | Buttons, heading glow, featured ticket |
| Neon cyan | `#2de2e6` | "Festival", headliners, nav button, footer links |
| Sun yellow | `#f9f871` | Date badge, big numbers, prices, day names |
| Soft white | `#f2f0ff` | Main text |
| Lavender | `#c9c5f5` | Tagline, stats labels, ticket lists |

## Measurements

| Thing | Size |
| --- | --- |
| Big heading (h1) | 140px (72px on phones) |
| Section headings (h2) | 64px, centered |
| Big numbers and prices | 72px |
| Page width | max 1100px, centered |
| Cards | 20px corners; buttons and pills use 999px |

## CSS you might need (look these up on MDN)

- `background: linear-gradient(#0d0b26, #1a1745);` fades the hero from one color to another
- `text-shadow: 0 0 24px #ff3d9a;` makes the heading glow
- `box-shadow: 0 0 20px #2de2e655;` makes the cards glow (the extra `55` at the end makes the color see-through)
- `flex-wrap: wrap;` lets the artist pills wrap onto new lines
- `letter-spacing: 2px;` and `text-transform: uppercase;`
- `:hover` to change a button's color when the mouse is over it
- `align-items: center;` on the ticket row lets the featured card stand taller than the others

## Phone size (required)

At `@media (max-width: 760px)`: the nav, hero buttons, lineup cards, and ticket cards all stack. The heading shrinks to 72px.

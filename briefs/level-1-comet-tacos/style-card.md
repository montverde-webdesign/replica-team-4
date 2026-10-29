# Style Card: Comet Tacos (Level 1)

Match `mockup-desktop.png` as closely as you can. `parts-map.png` shows who builds what.

## Fonts

Paste this in `css/base.css`, right below the comment:

```css
@import url("https://fonts.googleapis.com/css2?family=Fredoka:wght@500;700&family=Nunito:wght@400;700&display=swap");
```

| Used for | Font |
| --- | --- |
| Headings and the logo | `"Fredoka", sans-serif` |
| Everything else | `"Nunito", sans-serif`, 18px |

## Colors

| Color | Hex | Where |
| --- | --- | --- |
| Space purple | `#2b2160` | Header, hero, footer, and main text |
| Cream | `#fff8e7` | Page background, Find Us boxes |
| Comet yellow | `#ffb703` | Logo, big heading, prices, Find Us background |
| Orange | `#fb8500` | Button, day names |
| Soft purple | `#5b5490` | Menu descriptions |
| White | `#ffffff` | Menu box, nav links, hero text |

## Measurements

| Thing | Size |
| --- | --- |
| Big heading (h1) | 56px |
| Section headings (h2) | 40px, centered |
| Hero taco image | 320px wide |
| Nav and Find Us width | max 1000px, centered |
| Menu width | max 760px, centered |
| Rounded corners | 20px on boxes; 999px makes a pill shape (button, prices) |

## CSS you might need

- `display: flex;` with `justify-content: space-between;` for the nav and for each menu item's name and price
- `flex: 1;` makes the three Find Us boxes the same width
- `border: 4px solid #2b2160;` and `border-bottom: 2px dashed #ffb703;`
- `margin: 0 auto;` centers a box that has a `max-width`

## Phone size (bonus at Level 1)

See `mockup-phone.png`. The nav stacks, and the three Find Us boxes stack.

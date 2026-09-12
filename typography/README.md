# Typography

## Web fonts

Load only these, from Google Fonts, before any page CSS:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bree+Serif&family=Nunito:ital,wght@0,400;0,500;0,600;0,700;1,400;1,600&display=swap" rel="stylesheet">
```

| Role | Font | Weight | Notes |
|------|------|--------|-------|
| Headings h1, h2, h3 | Bree Serif | 400 | Titles and section headings |
| Italic word in a heading | Bree Serif italic | 400 | Color with rose `#DDA3A0` |
| Body | Nunito | 400 | Default on the root |
| Buttons | Nunito | 700 | Uppercase, letter-spaced |
| Labels and overlines | Nunito | 700 | Uppercase, wide letter-spacing |
| Nav links | Nunito | 600 | Uppercase |

Bree Serif is Google Fonts-only at weight 400. Do not request 300 or 700. Nunito carries body, UI, and italics.

The "Ladybird Ever After" wordmark is a script lockup in the logo files. Do not retype it. Do not load that script as a live web font.

## Do not use

- Recoleta Alt
- Playfair Display
- Alice
- Georgia, Times, or any other stand-in serif
- A second script next to the wordmark

## Scale

Use `clamp()` on the web so type holds across viewports.

| Role | Size |
|------|------|
| Homepage hero h1 | `clamp(2.8rem, 7vw, 5.2rem)` |
| Interior photo hero h1 | `clamp(2.2rem, 5.5vw, 4rem)` |
| Utility / cream hero h1 | `clamp(2.2rem, 4.5vw, 3.2rem)` |
| Section heading h2 | `clamp(1.5rem, 2.6vw, 2rem)` |
| CTA heading | `clamp(1.4rem, 2.5vw, 2rem)` |
| Body | `0.95rem` |
| Buttons | `0.74rem` to `0.8rem` |
| Overlines | `0.6rem` to `0.65rem` |
| Nav | `0.68rem` |

## Line height

- Headings: 1.18 to 1.2
- Body: 1.5 on the root, 1.7 to 1.85 in longer answers
- UI: 1

## Punctuation

No em dashes or en dashes. Use a hyphen or rewrite the sentence.

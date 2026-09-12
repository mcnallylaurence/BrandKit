# Layout

## Spacing

```css
--pad-x: clamp(1.2rem, 5vw, 5rem);
--pad-y: clamp(3.5rem, 7vw, 6rem);
```

Sections use `padding: var(--pad-y) var(--pad-x)`. Default content width is 820px. Wider grids are fine for venues, packages, and regions.

## Corners

| Element | Radius |
|---------|--------|
| Photos, cards, image frames | 16px |
| Buttons | 12px |
| Full-bleed heroes | 0 (flush to the screen) |
| Circular icons and the shamrock disc | 50% |

## Section rhythm

Most sections sit on cream. Use sage when a page needs a softer band. Green is for CTAs and dark moments, not for every other section.

## Buttons

- Nunito 700, uppercase, letter-spacing about `.12em`
- Padding about `.95rem 2.2rem`
- 12px corners
- Green fill with cream text for the primary action
- Rose fill with charcoal text for the secondary / legacy gold button name
- Do not use brass as a fill

## Overlines

Nunito 700, about `.6rem`, wide letter-spacing, uppercase, rose. A short rose rule can follow. Do not add a brass rule next to rose type.

## Links

Rose, underlined, 3px underline offset. Hover goes to green.

## Borders

`1px solid rgba(91, 98, 57, 0.1)`. Never a cold gray.

## Heroes

1. Homepage: full viewport photo or film, dark overlay, cream type
2. Interior photo pages: same height on every page, no CTAs in the hero
3. Utility pages: cream or sage, charcoal type, no image

One `h1` per page. A rose italic on one word is enough.

## Motion

Interactive states: 0.3s. Reveals can ease up 18px. Keep it quiet.

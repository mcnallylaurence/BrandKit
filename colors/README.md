# Colors

Green leads. Cream is the default background. Charcoal is text. Dusty rose is the only accent. Brass is a hairline only.

Never use raw hex in component styles if tokens are available. Use the CSS variables in [`tokens.css`](tokens.css) or the values in [`tokens.json`](tokens.json).

## Palette

| Token | Hex | RGB | Role |
|-------|-----|-----|------|
| `--green` | `#5B6239` | 91, 98, 57 | Lead color. Buttons, active states, the largest brand presence |
| `--green-dk` | `#3A3F25` | 58, 63, 37 | Deep green for rare dark fills |
| `--green-hv` | `#4A5130` | 74, 81, 48 | Green hover |
| `--sage` | `#E4E7DA` | 228, 231, 218 | Tint. Soft surfaces, hover, occasional section |
| `--cream` | `#F5F0EC` | 245, 240, 236 | Default background |
| `--warm` | `#F5F0EC` | 245, 240, 236 | Alias of cream |
| `--txt` | `#2B2B24` | 43, 43, 36 | Charcoal. Headings and short text |
| `--txt-mid` | `#5C5A52` | 92, 90, 82 | Warm gray. Long-form body |
| `--stone` | `#5C5A52` | 92, 90, 82 | Alias of warm gray for labels |
| `--rose` | `#DDA3A0` | 221, 163, 160 | Accent. Links, overlines, italic emphasis, badges |
| `--blush` | `#F5E3E0` | 245, 227, 224 | Soft rose surface. Use this behind long text, not full rose |
| `--brass` | `#B08D5C` | 176, 141, 92 | Hairlines, icon strokes, 1px dividers. Never a fill |

Legacy aliases, for older CSS only:

| Token | Hex | Note |
|-------|-----|------|
| `--gold` | `#DDA3A0` | Same as rose. Do not treat this as gold |
| `--gold-lt` | `#DDA3A0` | Same as rose |

## How to use them

**Do**

- Lead with green.
- Put cream behind most layouts.
- Use charcoal for type.
- Allow one dusty-rose moment per composition.
- Use sage for a softer band when cream needs a rest.
- Use brass only as a 1px rule or icon stroke.

**Don't**

- Do not use the retired gold `#B8964E`.
- Do not use dusty blue or lavender.
- Do not use more than four colors in one composition: green + cream + charcoal + one accent.
- Do not put full-strength rose behind long text. Use blush.
- Do not use brass as a button fill or a large shape.
- Do not pair rose and brass in the same tight cluster.

## Typical pairings

| Surface | Text | Accent |
|---------|------|--------|
| Cream page | Charcoal | Green button, one rose overline |
| Green band or CTA | Cream | Rose button if needed |
| Sage band | Charcoal | Green link or rose overline |
| Photo hero | Cream type | Rose italic on one word |

## Retired

These are not Brand Kit 2.0. Do not bring them back.

- Gold `#B8964E`
- Light gold `#D4AF71`
- Old cream `#F5F0E8`
- Old warm `#FDFAF4`
- Old stone `#8C8070`
- Old text `#1A1A18`

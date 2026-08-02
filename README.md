# Re-Accessorize — interactive style-tribe cards

**A hypothetical campaign, created as postgraduate coursework.**
MDes 004, Boosting the Brand · Birmingham City University · Sarah-Jane Crowson.

Not affiliated with, commissioned by, or endorsed by Accessorize or Monsoon
Accessorize Ltd. Accessorize is their trademark, referenced here for academic
critique and commentary only. Nothing on this page is a real product, service or
offer; no workshop exists. The page makes no claims about the brand's actual
practices, products or sustainability performance.

**All imagery is AI-generated (Adobe Firefly).** The pieces shown do not exist and
have not been repaired. The repair descriptions illustrate what the campaign would
document, and are not records of work done.

## What this is

Four cards, each in a different style culture. The front hides the product behind a
question mark; turning the card reveals the piece, what was done to it, and the
workshop invitation. Turn all four and a fifth card appears.

## Publishing on GitHub Pages

1. Create a public repository (e.g. `re-accessorize`).
2. Upload `index.html` and the `images` folder, keeping the folder structure.
3. Settings → Pages → Source: **Deploy from a branch** → `main` / `/ (root)`.
4. Live at `https://<username>.github.io/<repo>/` within a couple of minutes.

## The four pieces

| File | Card | Piece | Action word |
|---|---|---|---|
| `images/piece-01.jpg` | 01 art school | velvet choker, moonstone drop | restrung |
| `images/piece-02.jpg` | 02 in the band | safety-pin hearts | re-made |
| `images/piece-03.jpg` | 03 glued to MTV | butterfly hair clips | re-set |
| `images/piece-04.jpg` | 04 up till 6am | smiley pendant on collar | re-polished |

Replace a file keeping its name and the page picks it up with no code change.
Square images work best. If one is missing the card shows a caption rather than a
broken icon.

## Editing the copy

Card text lives in the `CARDS` array near the foot of `index.html` — headline,
action word, provenance line and image alt text.

## Notes

- No build step, no dependencies. One HTML file plus four images, about 360KB total.
- Fonts (Poppins, Inclusive Sans) load from Google Fonts, with system fallbacks.
- Keyboard operable, screen-reader labelled, honours reduced-motion preferences.
- `noindex` is set, so search engines are asked not to list the page.

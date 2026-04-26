# assets/

Brand assets for the site.

## Files

- `headshot.svg` — placeholder monogram (TF in gold on navy). Used in the hero portrait.
- `favicon.svg` — small "T" favicon used in the browser tab.

## Swapping in your real headshot

When you're ready to put a real photo on the site:

1. Save your headshot as `assets/headshot.jpg` (square, ~600×600 minimum, centered on your face).
2. In `index.html`, change the hero portrait `<img>` `src` from `assets/headshot.svg` to `assets/headshot.jpg`.
3. Update the `og:image` meta tag in `index.html` to point at the same file.

The site keeps working fine until then — you'll just see the gold "TF" monogram in the hero circle.

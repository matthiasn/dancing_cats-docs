# dancing_cats-docs

Render and review imagery for the [dancing_cats](https://github.com/matthiasn/dancing_cats)
character-animation work.

These images (frame-grid contact sheets, onion-skins, before/after comparisons
from the expert-panel review loop) are kept **out of the code repo** so it stays
lean. Pull requests in `dancing_cats` reference them by raw URL, e.g.:

```
https://raw.githubusercontent.com/matthiasn/dancing_cats-docs/main/images/reviews/<name>.png
```

Because they live on `main` here (not on feature branches of the code repo), the
URLs are permanent and survive branch deletion.

## Layout

- `images/reviews/` — per-move before/after grids and onion-skins from the
  5-lens motion-review panel (PNG).

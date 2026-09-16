# flowstate-assets

Public home for the Flowstate Consulting brand assets referenced by live email signatures. Do not delete or rename any file under `assets/`; a live signature points at each one by URL.

## Serving

Files are served through jsDelivr:

```
https://cdn.jsdelivr.net/gh/flowstate-cons/flowstate-assets@main/assets/<filename>
```

## Updating an asset

jsDelivr caches aggressively. A file overwritten in place can keep serving the old version for up to seven days on a `@main` pin. Never replace an asset at the same path. Use a new filename (`flowstate-mark-v2.png`) or pin to a version tag.

## Contents

- `assets/flowstate-mark.png` — the badge mark, 128 x 128
- `assets/icon-web.png` — website icon, 18 x 18
- `assets/icon-linkedin.png` — LinkedIn icon, 18 x 18

Files are committed as supplied: already cropped, resampled and optimized. Do not re-encode, resize or recolor them. The mark's off-white tile is deliberate; a transparent mark disappears in dark mode.
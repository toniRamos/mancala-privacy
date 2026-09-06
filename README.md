# Mancala – Privacy Policy

Static privacy policy page for the **Mancala** mobile game,
published with GitHub Pages.

## Public URL

https://toniramos.github.io/mancala-privacy/

This is the URL to paste in the Google Play Console
(*App content → Privacy policy*) and in the app's store listing.

## Files

| File         | Purpose                                                        |
| ------------ | -------------------------------------------------------------- |
| `index.html` | The privacy policy itself (self-contained HTML + inline CSS).   |
| `.nojekyll`  | Tells GitHub Pages to serve files as-is, skipping Jekyll build. |

## Enabling GitHub Pages (one-time setup)

1. Go to `Settings → Pages` in the GitHub repository.
2. **Source**: *Deploy from a branch*.
3. **Branch**: `main`, folder `/ (root)`.
4. Save. The site is live in ~1 minute at the URL above.

## Updating the policy

Edit `index.html`, bump the `Effective Date`, then:

```bash
git add index.html
git commit -m "Update privacy policy"
git push
```

GitHub Pages redeploys automatically on every push to `main`.

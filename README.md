Copia share-link host. Deployed from `web/` in the app repo — edit there, not here.

- `/.well-known/apple-app-site-association` routes `/i/*` to the Copia app (Universal Links).
- `/i/<token>` has no file; GitHub Pages serves `404.html`, a copy of the landing page, which reads the token from the path.
- `.nojekyll` makes GitHub Pages serve the `.well-known` folder.

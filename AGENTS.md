# calcolo_codice_fiscale

## Stack
- Single `index.html` (HTML + inline CSS + inline JS). Zero dependencies, no build step, no package.json.
- Vanilla ES6+, CSS custom properties, system font stack.

## Commands
- **No** test, lint, typecheck, or format commands exist. Edit `index.html` directly.
- **Deploy**: push to `main` → GitHub Actions auto-deploys to GitHub Pages.

## Project site on GitHub Pages
- Served at `https://francescomammana.github.io/calcolo_codice_fiscale/` (subpath, not root).
- **Asset paths must be relative** — `href="favicon.svg"`, not `/favicon.svg`.
- Remote is SSH: `git@github.com:FrancescoMammana/calcolo_codice_fiscale.git`.

## Git
- **Commit messages**: scrivere messaggi dettagliati in italiano, con corpo che spiega cosa è stato fatto e perché. Non commit monoriga.

## Code conventions
- UI text is **Italian**.
- Colors use `rgba()` notation. Primary: `#21808D` / `rgba(33, 128, 141, 1)`.
- Prefer appending new features as additional tabs/forms rather than modifying existing ones.
- **Minimal changes**: never alter existing working logic to accommodate a new feature. Add code, don't rewrite it.

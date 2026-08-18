# UWin·Japan — CCU·XPO Marketing Kit

Website + print DM for UWin·Japan, built for multi-market deployment.

## Demo Links

| | Link |
|---|---|
| 🌐 **Website** | [projectyak.github.io/uwin-japan-dm-/](https://projectyak.github.io/uwin-japan-dm-/) |
| 📄 **DM (Print)** | [projectyak.github.io/uwin-japan-dm-/Airwin%20Japan%20DM.html](https://projectyak.github.io/uwin-japan-dm-/Airwin%20Japan%20DM.html) |

## Files

| File | Description |
|---|---|
| `index.html` | Full single-page website (CCU·XPO) |
| `Airwin Japan DM.html` | A4 landscape print DM |
| `gate.html` | Visitor registration gate page |
| `colors_and_type.css` | Base design tokens (shared across all markets) |
| `i18n.js` | EN / 中 / 日 translations |
| `themes/theme-japan.css` | Japan market colours & logo overrides |

## Adding a New Market

1. Duplicate `themes/theme-japan.css` → e.g. `themes/theme-taiwan.css`
2. Change `--theme-primary` and accent colours
3. Update `--theme-logo` / `--theme-logo-mono` to new logo paths
4. Add `<link rel="stylesheet" href="themes/theme-taiwan.css">` in the HTML `<head>`

## Tech

Vanilla HTML/CSS · [Lucide Icons](https://lucide.dev) · No build step required.

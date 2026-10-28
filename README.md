# MacCare — mises à jour

Ce dépôt sert uniquement à distribuer les mises à jour de **MacCare**, une app macOS libre et gratuite
pour garder son Mac léger. Il est publié par GitHub Pages à l'adresse
https://diewalk.github.io/MacCare-updates/ et lu par le mécanisme de mise à jour intégré (Sparkle).

- `appcast.xml` : liste des versions, chaque archive signée EdDSA (MacCare refuse toute archive à la signature invalide).
- `MacCare-<version>.zip` : l'app, signée ad hoc, universelle (Apple Silicon et Intel).
- `MacCare-<version>.html` : notes de version.

Ne modifiez pas ces fichiers à la main : ils sont produits par `Tools/release.sh`.

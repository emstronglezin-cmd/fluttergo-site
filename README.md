# fluttergo-site

Site public officiel de **Flutter Go** — installateur Windows officiel, sommes
de contrôle SHA-256 et manuel PDF.

- Site : <https://emstronglezin-cmd.github.io/fluttergo-site/>
- `downloads/` : `FlutterGo-Setup-0.8.1.exe`, `FlutterGo-Portable-0.8.1.zip`,
  `SHA256SUMS.txt`, `FlutterGo-Manuel-v0.8.1.pdf`
- Le code source du CLI Flutter Go est dans un dépôt séparé (privé en
  pré-lancement). Ce dépôt-ci contient **uniquement** le site et les binaires
  de distribution.

## Vérifier le téléchargement

```powershell
certutil -hashfile FlutterGo-Setup-0.8.1.exe SHA256
# Comparer avec SHA256SUMS.txt
```

## Licence

MIT — voir `LICENSE`.

# SpotWave — Privacy Policy (site public)

Dépôt **autonome** contenant uniquement la politique de confidentialité de l'app SpotWave,
à publier via **GitHub Pages** sur un repo **public** (séparé du repo de l'app, qui reste privé).

## Contenu
- `index.html` — politique de confidentialité bilingue FR/EN (page statique, aucune dépendance).

## ⚠️ Avant de publier
Dans `index.html`, remplace `CHANGE_ME@exemple.com` par ton **e-mail réel** (2 occurrences : section FR + EN).

## Déploiement GitHub Pages

```bash
cd spotwave-privacy
git init
git add .
git commit -m "SpotWave privacy policy"
git branch -M main
git remote add origin https://github.com/<ton-user>/spotwave-privacy.git
git push -u origin main
```

Puis sur GitHub : **Settings → Pages → Build and deployment**
- Source : *Deploy from a branch*
- Branch : `main` / dossier `/ (root)`
- Save

L'URL publique sera :

```
https://<ton-user>.github.io/spotwave-privacy/
```

C'est cette URL à coller dans **Play Console** :
- Fiche store → *Politique de confidentialité*
- Contenu de l'app → *Sécurité des données* (le cas échéant)

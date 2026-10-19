# Site ritchy-lab

Ce dossier contient le site (GitHub Pages) qui présente les applications :
Vox-Pack, USB-Floss et USB-Floss Magic.

## Publier

1. Crée un dépôt **public** nommé exactement `ritchy-lab.github.io`.
2. Copie le **contenu** de ce dossier à la racine du dépôt (pas le dossier
   lui-même) : `index.html`, `style.css`, `favicon.png`, `404.html`,
   `.nojekyll`, `assets/` (dont `ritchy-lab-mark.png`), `vox-pack/`, `usb-floss/`, `usb-floss-magic/`.
3. Commit et push (GitHub Desktop).
4. Dans le dépôt : **Settings → Pages → Deploy from a branch → main → / (root) → Save**.
5. Attends une minute, puis ouvre https://ritchy-lab.github.io/.

## Mettre à jour

- **Vox-Pack** : les boutons pointent vers
  `releases/latest/download/Vox-Pack.zip` et `.../Vox-Pack.exe`.
  Rien à changer à chaque version.
- **USB-Floss** et **USB-Floss Magic** : les boutons pointent vers leur page
  `releases/latest`. Rien à changer non plus.
- Les textes et les captures sont dans les pages : à modifier si nécessaire.

## Images d'aperçu

- `assets/hub-social.png` (accueil) ;
- `assets/vox-pack-social.png` ;
- `assets/usb-floss-social.png` ;
- `assets/usb-floss-magic-social.png`.

Les balises `og:image` utilisent `https://ritchy-lab.github.io/...`.
Si tu utilises un domaine personnalisé, remplace cette base dans les pages.

## Note

Le dossier a été préparé dans `site-perso/` du dépôt Vox-Pack, et il est
exclu **localement** de Git (`.git/info/exclude`) pour ne pas être commité
dans Vox-Pack. Copie-le dans le nouveau dépôt.

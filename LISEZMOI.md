# BetoB

## Mettre le site en ligne
1. Sur GitHub (compte Belindaca), crée un repo public nommé exactement `Belindaca.github.io`.
2. Dépose tout le contenu de ce dossier (index.html et le dossier captures).
3. Settings → Pages → Branch : `main`, dossier `/ (root)` → Save.
4. Après une ou deux minutes, le site est en ligne sur https://belindaca.github.io

## Changer une image
Remplace le fichier dans `captures/` en gardant exactement le même nom.
- `adele-1.jpg` : page de l'album 21
- `adele-2.mp4` : animation de la carte « Liste des titres »
- `adele-3.jpg` : « Écouter sur Spotify »
- `adele-4.jpg` : page Discographie
- `portrait.jpg` : ta photo

Les vidéos `.mp4` se lisent en boucle et sans son dans le carrousel, comme un GIF.

## Changer un texte
Tout est dans `index.html` : `const P = [...]` (projets), `const T = {...}` (textes, fr et en), `const AUTO = {...}` (automatisations).

## Ajouter un article au Journal
Dans `index.html`, remplis `const JOURNAL = [];` en suivant le modèle écrit juste au-dessus.

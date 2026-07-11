# 📸 Où mettre tes captures d'écran / GIFs

Dépose simplement une image dans ce dossier (`assets/projects/`) avec **exactement** le nom indiqué ci-dessous — elle apparaîtra automatiquement sur le portfolio, sans toucher au code. Tant qu'un fichier n'existe pas, la carte affiche un joli placeholder "Capture à venir".

Format recommandé : **.png** ou **.jpg**, ratio 16:10, environ 1200×750px, poids < 500 Ko (compresse avec [squoosh.app](https://squoosh.app) si besoin).

| Fichier attendu | Projet |
|---|---|
| `citation-du-jour-rj.png` | Citation du jour RJ |
| `cv.png` | CV |
| `restaurant-pro.png` | restaurant-pro |
| `basique.png` | basique |
| `faveur-divin.png` | Faveur-Divin |
| `deesse-bb.png` | déesse-BB |
| `campus-intelligent.png` | Système de gestion de campus intelligent |
| `lecons-cpp.png` | LeçonsC- |
| `pro-py.png` | Pro_py |
| `plateforme-vote.png` | SRC-Plateforme-de-vote-réelle (privé) |
| `restaurant-faveur-divine.png` | restaurant-Faveur-Divine (privé) |
| `boutique-sherina.png` | boutique Sherina (privé) |
| `amour.png` | amour (privé) |
| `reve-denfants.png` | Rêve d'enfants (privé) |
| `projet-ventes.png` | projet_ventes (privé) |

## Astuce pour un GIF au lieu d'une image statique

Si tu veux un **GIF animé** pour un projet (ex: une interaction, un scan qui défile) :
1. Enregistre-le avec **ScreenToGif** (Windows) — gratuit, simple, exporte directement en `.gif`.
2. Nomme le fichier **exactement pareil mais en `.gif`** (ex: `restaurant-pro.gif`).
3. Dans `index.html`, cherche la ligne du projet concerné et remplace juste l'extension `.png` par `.gif` à **deux endroits** : `data-lightbox="assets/projects/xxx.gif"` et `src="assets/projects/xxx.gif"`.

## Pour les captures de labs cyber (Nmap, SQLMap...)

Même principe — ajoute simplement les fichiers, dis-moi les noms des labs concernés et je fais pareil (vignette + lightbox) pour la section **Cyber Labs**.

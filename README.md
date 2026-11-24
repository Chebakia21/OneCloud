# OneCloud

**Un seul programme à installer : OneCloud.** Il installe OneClip, OneFile, OneMirror et OneStream, les ouvre, et les tient à jour tout seul.

## ⬇️ [Télécharger OneCloud](https://raw.githubusercontent.com/Chebakia21/OneCloud/main/installer/OneCloud-Setup.exe)

Pour Windows 10 et 11 (64 bits).

1. Clique sur le lien ci-dessus : le fichier **OneCloud-Setup.exe** se télécharge.
2. Ouvre-le. Si Windows affiche « Windows a protégé votre ordinateur », clique sur **Informations complémentaires**, puis sur **Exécuter quand même** (OneCloud n'est pas signé par un éditeur connu, c'est normal).
3. OneCloud s'ouvre tout seul. Clique sur **Installer** à côté du logiciel que tu veux.

Ensuite, plus rien à faire : chaque nouvelle version arrive toute seule dans OneCloud.

## Ce que contient OneCloud

| Logiciel | À quoi il sert | Version | Mise à jour |
|---|---|---|---|
| **OneClip** | Montage vidéo et clips : timeline multipiste, moments forts, cadrage, sous-titres, export. | 0.10.0 | 24/11/2026 |
| **OneFile** | Convertisseur de fichiers : images, vidéos, sons, PDF et archives, par lots, 100 % en local. | 1.6.0 | 24/11/2026 |
| **OneMirror** | L’écran de ton téléphone Android sur le PC, en USB ou en Wi-Fi, avec le son : prêt pour OBS. | 1.5.0 | 24/11/2026 |
| **OneStream** | ChebakiaBot dans le chat Twitch : commandes, rappels et heures de prière à la minute. | 1.1.0 | 24/11/2026 |
| **OneCloud** | Installe et met à jour les logiciels One. | 1.7.2 | 23/11/2026 |

## Nouveautés

### OneClip 0.10.0

- Nouvelle interface : fond anthracite, cartes en verre et police Geist, la même famille que OneFile, OneMirror et OneStream.
- Nouvel accueil : trois grandes cartes (Nouveau montage, Créer des clips, Importer une VOD Twitch) et tes projets récents en vignettes, qui s’adaptent à la taille de la fenêtre.
- Le bouton principal, les curseurs et les interrupteurs passent en blanc ; le corail de OneClip marque ce qui est choisi.

### OneFile 1.6.0

- Nouvelle interface : fond anthracite, barre latérale avec « Convertir », « Depuis un lien » et « Paramètres », page arrondie et cartes en verre.
- Les onglets (Images, Vidéos, Sons…) deviennent des pastilles, et le menu s’adapte quand tu rétrécis la fenêtre.
- Changer d’onglet est plus doux : la page apparaît en fondu, sans à-coup.

### OneMirror 1.5.0

- Nouvelle interface : fond anthracite, barre latérale avec Téléphones et « Ajouter en Wi-Fi », page arrondie et cartes en verre.
- Les interrupteurs et les curseurs passent en blanc ; le bleu ciel de OneMirror marque ce qui est choisi.

### OneStream 1.1.0

- Nouvelle interface : fond anthracite, barre latérale à icônes (Accueil, Commandes, Prières, Rappels), page arrondie et cartes en verre.
- Changer de page est plus doux : la page apparaît en fondu, sans à-coup.

### OneCloud 1.7.2

- Correction : la fenêtre de OneCloud se déplace de nouveau à la souris, en l'attrapant par la barre du haut ou par la barre latérale.
- Un double-clic sur la barre du haut agrandit la fenêtre ou la remet à sa taille.

## Comment ce dépôt est rangé

Pas besoin de télécharger quoi que ce soit ici à la main : OneCloud s'en occupe.

| Élément | Rôle |
|---|---|
| `installer/OneCloud-Setup.exe` | L'installateur de OneCloud (le lien « Télécharger OneCloud »). |
| `catalog.json` | La liste des logiciels et de leurs versions, lue par OneCloud. |
| `applications/oneclip` | Les fichiers de OneClip. |
| `applications/onefile` | Les fichiers de OneFile. |
| `applications/onemirror` | Les fichiers de OneMirror. |
| `applications/onestream` | Les fichiers de OneStream. |
| `applications/onecloud` | Les mises à jour de OneCloud lui-même. |

Le code des logiciels n'est pas ici : ce dépôt ne contient que les versions prêtes à installer.

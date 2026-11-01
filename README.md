# OneCloud

**Un seul programme à installer : OneCloud.** Il installe OneClip, OneFile et OneMirror, les ouvre, et les tient à jour tout seul.

## ⬇️ [Télécharger OneCloud](https://raw.githubusercontent.com/Chebakia21/Cadreur-Release/main/installer/OneCloud-Setup.exe)

Pour Windows 10 et 11 (64 bits).

1. Clique sur le lien ci-dessus : le fichier **OneCloud-Setup.exe** se télécharge.
2. Ouvre-le. Si Windows affiche « Windows a protégé votre ordinateur », clique sur **Informations complémentaires**, puis sur **Exécuter quand même** (OneCloud n'est pas signé par un éditeur connu, c'est normal).
3. OneCloud s'ouvre tout seul. Clique sur **Installer** à côté du logiciel que tu veux.

Ensuite, plus rien à faire : chaque nouvelle version arrive toute seule dans OneCloud.

## Ce que contient OneCloud

| Logiciel | À quoi il sert | Version | Mise à jour |
|---|---|---|---|
| **OneClip** | Montage vidéo et clips : timeline multipiste, moments forts, cadrage, sous-titres, export. | 0.7.1 | 01/11/2026 |
| **OneFile** | Convertisseur de fichiers : images, vidéos, sons, PDF et archives, par lots, 100 % en local. | 1.4.1 | 01/11/2026 |
| **OneMirror** | L’écran de ton téléphone Android sur le PC, en USB ou en Wi-Fi, avec le son : prêt pour OBS. | 1.2.1 | 01/11/2026 |
| **OneCloud** | Installe et met à jour les trois logiciels. | 1.5.7 | 01/11/2026 |

## Nouveautés

### OneClip 0.7.1

- Nouvelle icône : le clap de la série One, sur fond orange, sur le bureau, dans la barre des tâches et en haut de la fenêtre.
- OneClip a maintenant sa couleur à lui, un orange corail doux : l’onglet ouvert, l’outil choisi et l’élément sélectionné (plan, préréglage, mise en page) s’affichent dans cette couleur. Le bleu reste celui des actions et des réglages.
- La fenêtre « À propos » parle maintenant de OneCloud.

### OneFile 1.4.1

- Nouvelle icône : la page de la série One, sur fond vert, sur le bureau, dans la barre des tâches et en haut de la fenêtre.
- OneFile a maintenant sa couleur à lui, un vert menthe doux : l’onglet ouvert, le choix « Que veux-tu faire ? » et le format choisi s’affichent dans cette couleur. Le bleu reste celui du bouton Convertir et des réglages.

### OneMirror 1.2.1

- Nouvelle icône : le téléphone de la série One, sur fond bleu, sur le bureau, dans la barre des tâches, en haut de la fenêtre et sur la carte de ton téléphone.
- OneMirror a maintenant sa couleur à lui, un bleu ciel doux, pour les choix sélectionnés. Le bleu foncé reste celui des actions et des réglages.

### OneCloud 1.5.7

- Logo de OneCloud : un fond arc-en-ciel plus vif, dans l’esprit de Creative Cloud.

## Comment ce dépôt est rangé

Pas besoin de télécharger quoi que ce soit ici à la main : OneCloud s'en occupe.

| Élément | Rôle |
|---|---|
| `installer/OneCloud-Setup.exe` | L'installateur de OneCloud (le lien « Télécharger OneCloud »). |
| `catalog.json` | La liste des logiciels et de leurs versions, lue par OneCloud. |
| `applications/oneclip` | Les fichiers de OneClip. |
| `applications/onefile` | Les fichiers de OneFile. |
| `applications/onemirror` | Les fichiers de OneMirror. |
| `applications/onecloud` | Les mises à jour de OneCloud lui-même. |

Le code des logiciels n'est pas ici : ce dépôt ne contient que les versions prêtes à installer.

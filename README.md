# OneCloud

**Un seul programme à installer : OneCloud.** Il installe OneClip, OneFile et OneMirror, les ouvre, et les tient à jour tout seul.

## ⬇️ [Télécharger OneCloud](https://raw.githubusercontent.com/Chebakia21/OneCloud/main/installer/OneCloud-Setup.exe)

Pour Windows 10 et 11 (64 bits).

1. Clique sur le lien ci-dessus : le fichier **OneCloud-Setup.exe** se télécharge.
2. Ouvre-le. Si Windows affiche « Windows a protégé votre ordinateur », clique sur **Informations complémentaires**, puis sur **Exécuter quand même** (OneCloud n'est pas signé par un éditeur connu, c'est normal).
3. OneCloud s'ouvre tout seul. Clique sur **Installer** à côté du logiciel que tu veux.

Ensuite, plus rien à faire : chaque nouvelle version arrive toute seule dans OneCloud.

## Ce que contient OneCloud

| Logiciel | À quoi il sert | Version | Mise à jour |
|---|---|---|---|
| **OneClip** | Montage vidéo et clips : timeline multipiste, moments forts, cadrage, sous-titres, export. | 0.7.2 | 01/11/2026 |
| **OneFile** | Convertisseur de fichiers : images, vidéos, sons, PDF et archives, par lots, 100 % en local. | 1.4.1 | 01/11/2026 |
| **OneMirror** | L’écran de ton téléphone Android sur le PC, en USB ou en Wi-Fi, avec le son : prêt pour OBS. | 1.3.6 | 04/11/2026 |
| **OneCloud** | Installe et met à jour les trois logiciels. | 1.6.0 | 01/11/2026 |

## Nouveautés

### OneClip 0.7.2

- Fini le nom provisoire « Cadreur » : le programme s'appelle maintenant OneClip.exe, et ton dossier de projets est rangé sous le nom OneClip. Tes projets, réglages et projets récents sont gardés tels quels.

### OneFile 1.4.1

- Nouvelle icône : la page de la série One, sur fond vert, sur le bureau, dans la barre des tâches et en haut de la fenêtre.
- OneFile a maintenant sa couleur à lui, un vert menthe doux : l’onglet ouvert, le choix « Que veux-tu faire ? » et le format choisi s’affichent dans cette couleur. Le bleu reste celui du bouton Convertir et des réglages.

### OneMirror 1.3.6

- Caméra virtuelle : Discord montre maintenant l’image du téléphone (caméra ou selfie), et plus la fenêtre de OneMirror qui porte le même nom.
- L’image n’est plus la tête en bas. Dans ton propre aperçu, Discord la montre en miroir, comme toute webcam ; les autres la voient à l’endroit.

### OneCloud 1.6.0

- Fini le nom provisoire « Cadreur » : OneCloud déménage tout seul dans son propre dossier (OneCloud.exe), avec son nom et son logo jusque dans le Gestionnaire des tâches.
- Ses réglages, les logiciels installés et les fichiers reçus suivent ; raccourcis, menu Démarrer, barre des tâches et « Applications installées » pointent vers le nouveau dossier, puis l'ancien est effacé.
- OneClip est rangé dans un dossier « oneclip » et son programme devient OneClip.exe.
- Les fichiers de mise à jour s'appellent maintenant « .onecloud » (les anciens « .cadreur » s'ouvrent toujours).

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

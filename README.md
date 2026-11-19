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
| **OneClip** | Montage vidéo et clips : timeline multipiste, moments forts, cadrage, sous-titres, export. | 0.9.1 | 19/11/2026 |
| **OneFile** | Convertisseur de fichiers : images, vidéos, sons, PDF et archives, par lots, 100 % en local. | 1.5.1 | 10/11/2026 |
| **OneMirror** | L’écran de ton téléphone Android sur le PC, en USB ou en Wi-Fi, avec le son : prêt pour OBS. | 1.4.5 | 19/11/2026 |
| **OneStream** | ChebakiaBot dans le chat Twitch : commandes, rappels et heures de prière à la minute. | 1.0.0 | 11/11/2026 |
| **OneCloud** | Installe et met à jour les logiciels One. | 1.6.3 | 19/11/2026 |

## Nouveautés

### OneClip 0.9.1

- Montage : « Générer les sous-titres » transcrit maintenant tes vidéos sur n’importe quelle piste (avant, seulement la piste A1).
- Montage : dans le panneau d’un plan, la section « Sous-titres » a un vrai bouton « Générer les sous-titres de ce plan » (l’ancien message qui renvoyait vers Clips est retiré).

### OneFile 1.5.1

- Correction : la conversion en Word s’arrêtait sur les PDF qui contiennent une page scannée (« Conversion en Word interrompue »). Les pages scannées sont de nouveau lues.

### OneMirror 1.4.5

- La caméra virtuelle est beaucoup plus fluide : chaque nouvelle image du téléphone part dès qu’elle arrive, au lieu d’être envoyée au hasard d’une minuterie (certaines partaient deux fois, d’autres jamais).
- Moins de travail pour le PC : l’image est préparée par la carte graphique, et OneMirror n’attend plus jamais la caméra virtuelle plus de quelques millisecondes.

### OneStream 1.0.0

- Nouveau logiciel : OneStream fait parler ChebakiaBot dans ton chat Twitch.
- Les heures de prière de la mosquée As-Sabirin (Uccle) sont annoncées dans le chat à la minute exacte, pendant le live.
- 23 commandes prêtes (!so, !uptime, !followage, !lurk, !clip, !love, !8ball, !mort…), modifiables, avec qui peut les utiliser et le délai entre deux utilisations.
- Rappels automatiques pendant le live : follow, Discord et clips, seulement quand le chat est actif.
- Fermer la fenêtre garde ChebakiaBot actif : il reste près de l’horloge de Windows.

### OneCloud 1.6.3

- Les mises à jour arrivent beaucoup plus vite : OneCloud vérifie le cloud toutes les 5 minutes (au lieu de 30) et dès que tu ramènes sa fenêtre devant.
- OneCloud lit toujours la dernière version du catalogue, sans attendre la copie que GitHub garde quelques minutes.
- « Rechercher des mises à jour » installe directement ce qui est nouveau.

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

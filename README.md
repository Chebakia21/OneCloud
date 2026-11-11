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
| **OneClip** | Montage vidéo et clips : timeline multipiste, moments forts, cadrage, sous-titres, export. | 0.7.2 | 01/11/2026 |
| **OneFile** | Convertisseur de fichiers : images, vidéos, sons, PDF et archives, par lots, 100 % en local. | 1.5.1 | 10/11/2026 |
| **OneMirror** | L’écran de ton téléphone Android sur le PC, en USB ou en Wi-Fi, avec le son : prêt pour OBS. | 1.4.4 | 07/11/2026 |
| **OneStream** | ChebakiaBot dans le chat Twitch : commandes, rappels et heures de prière à la minute. | 1.0.0 | 11/11/2026 |
| **OneCloud** | Installe et met à jour les logiciels One. | 1.6.2 | 11/11/2026 |

## Nouveautés

### OneClip 0.7.2

- Fini le nom provisoire « Cadreur » : le programme s'appelle maintenant OneClip.exe, et ton dossier de projets est rangé sous le nom OneClip. Tes projets, réglages et projets récents sont gardés tels quels.

### OneFile 1.5.1

- Correction : la conversion en Word s’arrêtait sur les PDF qui contiennent une page scannée (« Conversion en Word interrompue »). Les pages scannées sont de nouveau lues.

### OneMirror 1.4.4

- Correction : la fenêtre du téléphone pouvait devenir plus grande que l’écran et couper l’image (par exemple en paysage ou collée en haut de l’écran). Après chaque redimensionnement, elle reprend les bonnes proportions et revient entièrement dans l’écran.

### OneStream 1.0.0

- Nouveau logiciel : OneStream fait parler ChebakiaBot dans ton chat Twitch.
- Les heures de prière de la mosquée As-Sabirin (Uccle) sont annoncées dans le chat à la minute exacte, pendant le live.
- 23 commandes prêtes (!so, !uptime, !followage, !lurk, !clip, !love, !8ball, !mort…), modifiables, avec qui peut les utiliser et le délai entre deux utilisations.
- Rappels automatiques pendant le live : follow, Discord et clips, seulement quand le chat est actif.
- Fermer la fenêtre garde ChebakiaBot actif : il reste près de l’horloge de Windows.

### OneCloud 1.6.2

- OneCloud peut installer OneStream, le nouveau logiciel de la série One (ChebakiaBot dans le chat Twitch).

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

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
| **OneClip** | Montage vidéo et clips : timeline multipiste, moments forts, cadrage, sous-titres, export. | 0.12.0 | 25/11/2026 |
| **OneFile** | Convertisseur de fichiers : images, vidéos, sons, PDF et archives, par lots, 100 % en local. | 1.6.0 | 24/11/2026 |
| **OneMirror** | L’écran de ton téléphone Android sur le PC, en USB ou en Wi-Fi, avec le son : prêt pour OBS. | 1.5.0 | 24/11/2026 |
| **OneStream** | ChebakiaBot dans le chat Twitch : commandes, rappels et heures de prière à la minute. | 1.1.0 | 24/11/2026 |
| **OneCloud** | Installe et met à jour les logiciels One. | 1.7.2 | 23/11/2026 |

## Nouveautés

### OneClip 0.12.0

- Vitesse : ralenti, accéléré (de 5 à 1600 %), marche arrière, rampes de vitesse et arrêt sur image, avec le son qui suit.
- Nouveau moteur d’image sur la carte graphique : les effets sont identiques dans l’aperçu et dans la vidéo exportée.
- 55 effets vidéo : glow, grain de film, light leaks, lens flare, bandes cinéma, glitch, VHS, RGB split, flous de mouvement, tilt shift, netteté, duotone, Technicolor, miroir, kaléidoscope…
- Particules et matières par-dessus l’image : neige, pluie, étincelles, fumée, feu.
- 30 transitions : zoom, whip pan, rotation, retournement 3D, cercle, losange, horloge, glitch, pixelisation, brûlure de film, luma wipe…
- Étalonnage complet : exposition, hautes lumières, ombres, température, vibrance, roues lift/gamma/gain, courbes, et 9 looks prêts (Teal & Orange, Ciné chaud…).
- Import de LUT .cube et bouton « avant / après » sur le moniteur pour comparer l’image avec et sans effets.
- Fond vert (ou bleu) avec anti-débordement, luma key et 17 modes de fusion (écran, produit, incrustation…).
- Perspective 3D : incliner une image en 3D, animable avec des images clés.
- 18 effets audio entendus dès l’aperçu : égaliseur, compresseur, limiteur, réduction du bruit, noise gate, de-esser, de-hummer, reverb, écho, chorus, voix de téléphone…
- Ducking : la musique baisse toute seule pendant la voix, puis remonte.
- 9 nouvelles animations toutes prêtes (push in, rebond, speed zoom, incrustation dans un coin…) et 4 courbes avancées (rebond, élastique…).
- Mes préréglages : enregistre une pile d’effets et réapplique-la en un clic sur d’autres plans.
- Export de plusieurs formats d’un coup (YouTube, Shorts, archive…) dans un dossier, et historique des exports.
- Modèles YouTube : intro de chaîne, abonne-toi, like, écran de fin.
- Pour les curieux : un effet GLSL personnalisé, à écrire soi-même.

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

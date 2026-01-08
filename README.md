# Test de pré-diagnostic du TDAH (ASRS v1.1)

Une page web simple et légère pour passer le test de dépistage du TDAH chez l'adulte (échelle officielle ASRS v1.1 de l'OMS).

Le projet est né d'un constat simple : la plupart des tests en ligne sont remplis de publicités, mal traduits ou demandent une adresse email pour voir les résultats. Ici, c'est juste le test, propre et direct.

## Ce que ça fait

* **Test officiel :** Les 18 questions de l'OMS avec le calcul automatique du score.
* **Contexte centré sur la France 🇫🇷 :** Si la langue est réglée sur Français, le site affiche des infos spécifiques sur le parcours de soin (Généraliste -> Psychiatre) et les médicaments autorisés.
* **Multilingue :** Disponible en français, anglais et italien.
* **Privé :** 100% anonyme. Aucune donnée n'est envoyée à un serveur, tout le calcul se fait en local dans votre navigateur.
* **Impression :** Possibilité de générer un PDF propre du résultat pour l'amener chez le médecin.

## Comment l'utiliser

C'est une "Single Page Application" qui tient en un seul fichier. Pas besoin de serveur complexe.

### En ligne
Le site est hébergeable gratuitement sur n'importe quel service de pages statiques (Vercel, Netlify, GitHub Pages).

### En local
1.  Téléchargez simplement le fichier `index.html`.
2.  Ouvrez-le avec n'importe quel navigateur (Chrome, Firefox, Safari...).

## Technique

* HTML / JS Vanilla (pas de framework lourd type React/Vue).
* Tailwind CSS (via CDN) pour le design.
* Google Fonts & Material Icons.

## Avertissement

Ce site est un outil d'information et de pré-dépistage. **Ce n'est pas un diagnostic médical.** Seul un médecin psychiatre ou neurologue est habilité à poser un diagnostic officiel de TDAH.

## Crédits

* **Échelle :** ASRS v1.1 (Organisation Mondiale de la Santé).
* **Reddit :** Inspiré par le travail de la communauté r/TDAHFrance et u/BersteinMilza.

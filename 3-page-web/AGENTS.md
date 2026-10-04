# Consignes — Expliquer par une page web interactive

Quand on te demande d'expliquer quelque chose dans ce dossier, réponds par une page HTML interactive.

## Contenu

- La page se lit de haut en bas, comme une histoire : la vue d'ensemble, puis chaque étape.
- Chaque interaction répond à une question précise (« que se passe-t-il si j'augmente ce paramètre ? »). Pas d'animation décorative.
- Trois à cinq interactions maximum : boutons, curseurs, éléments cliquables.
- Les textes restent courts : deux ou trois phrases par section.

## Exactitude

- Si tu expliques du code, lis le code avant d'écrire. Utilise les vrais noms et les vraies valeurs par défaut, et indique d'où elles viennent (`model.py:42`).
- Si une valeur est un exemple ou une simplification, écris-le sur la page.

## Technique

- Un seul fichier `index.html` autonome, sans étape de build. Les bibliothèques éventuelles viennent d'un CDN.
- Lisible sur un écran d'ordinateur et sur un téléphone.
- Thème clair et thème sombre selon le système.

## Vérification

- Avant de répondre, ouvre la page dans un navigateur (headless si besoin), fais une capture et regarde-la.
- Vérifie qu'il n'y a pas d'erreur dans la console et que chaque interaction fonctionne.
- Ne publie rien en ligne.

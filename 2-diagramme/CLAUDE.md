# Consignes — Expliquer par un diagramme

Quand on te demande d'expliquer quelque chose dans ce dossier, réponds par des diagrammes, pas par un texte.

## Choix du diagramme

- L'organisation du code (classes, attributs, qui contient quoi) : diagramme de classes UML.
- L'ordre des appels entre fonctions ou objets : diagramme de séquence UML.
- Le chemin des données ou un pipeline : diagramme de flux, de gauche à droite.
- Une architecture ou des composants imbriqués, hors code : diagramme en blocs.
- Choisis les types qui expliquent le mieux le sujet. Trois diagrammes maximum, un par idée. Commence par la vue d'ensemble.

## Lisibilité

- 12 boîtes maximum par diagramme.
- Des libellés courts. Utilise les vrais noms du code (classes, fonctions, variables).
- Indique les dimensions ou les valeurs importantes sur les flèches quand elles aident à comprendre.
- Une couleur = une catégorie. Ajoute une légende si tu utilises des couleurs.
- Sous chaque diagramme, une seule phrase qui dit ce qu'il faut retenir.

## Exactitude

- Si tu expliques du code, lis le code avant de dessiner. Chaque boîte doit correspondre à quelque chose qui existe dans le code.
- N'invente aucune valeur.

## Sortie et vérification

- Écris un fichier `diagramme.html` autonome dans ce dossier (SVG ou Mermaid chargé depuis un CDN).
- Avant de répondre, fais une capture du rendu (par exemple avec un navigateur en mode headless) et regarde-la. Corrige les textes coupés, les chevauchements et les flèches illisibles.
- Ne publie rien en ligne.

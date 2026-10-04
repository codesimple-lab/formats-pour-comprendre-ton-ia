# Consignes — Expliquer par une vidéo

Quand on te demande d'expliquer quelque chose dans ce dossier, réponds par une courte vidéo explicative animée, dans le style de 3Blue1Brown.

## Outils

- Animation : Manim Community Edition, installé dans un environnement virtuel local (`python3 -m venv .venv`). N'installe rien en global.
- Voix : ElevenLabs par défaut, avec la variable `ELEVENLABS_API_KEY` et le modèle `eleven_multilingual_v2`. Choisis une voix de la langue de la demande parmi celles du compte. Génère l'audio phrase par phrase pour pouvoir caler les animations. Seulement si la clé n'existe pas, utilise la synthèse vocale locale (sur macOS : `say -v Thomas` pour le français), et signale que la voix sera moins naturelle.
- Montage final : ffmpeg.

## Étapes

1. Lis le sujet (et le code si c'est du code).
2. Écris le texte de la narration dans `narration.md` : 2 à 3 minutes, phrases courtes, langue de la demande.
3. Découpe en scènes : une idée par scène.
4. Génère l'audio de chaque scène, puis mesure sa durée.
5. Anime chaque scène pour qu'elle dure exactement comme son audio.
6. Assemble le tout en `video.mp4` : 1920×1080, 30 images par seconde.

## Style

- Fond sombre, peu de texte à l'écran, des formes qui bougent pour montrer l'idée.
- Remplis l'écran : l'élément principal occupe au moins la moitié de la largeur. Aucun texte en dessous de 28 px en 1080p, pour rester lisible sur téléphone.
- Jamais plus de 2 secondes d'écran vide ou presque vide, y compris pendant les transitions.
- Ce qui est dit doit être visible à l'écran au même moment.
- Pas de bloc de code long : au maximum quelques lignes, mises en évidence.

## Exactitude

- Si tu expliques du code, chaque affirmation de la narration doit correspondre au code. Cite les fichiers dans `narration.md`.
- N'invente aucune valeur.

## Vérification

- Extrais une image toutes les 2 secondes de `video.mp4` et regarde-les. Corrige les textes coupés, les chevauchements et les écrans vides.
- Vérifie que l'audio et l'image restent synchronisés jusqu'à la fin.
- À la fin, indique le temps total passé et les erreurs rencontrées.
- Ne publie rien en ligne.

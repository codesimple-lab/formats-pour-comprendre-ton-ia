# Formats pour comprendre ton IA

Les fichiers de consignes utilisés dans la vidéo Bradypus « Markdown, diagramme, HTML ou vidéo : quel format pour comprendre ton IA ? ».

L'idée vient d'un post d'Andrej Karpathy : au lieu de lire de longues réponses en Markdown, demande à ton IA un autre format.

| Dossier | Format | Ce que fait l'IA |
|---|---|---|
| `1-ecrit/` | Texte simplifié | Répond avec les règles de l'ASD-STE100, adaptées à ta langue : phrases courtes, une idée par phrase, chaque terme technique expliqué. |
| `2-diagramme/` | Diagramme | Choisit le bon type de schéma (classes UML, séquence, flux), puis vérifie le rendu avant de répondre. |
| `3-page-web/` | Page HTML | Fait une page interactive (boutons, curseurs) et la teste dans un navigateur. |
| `4-video/` | Vidéo explicative | Écrit la narration, anime avec Manim, génère la voix avec ElevenLabs (ou la voix de ton ordinateur) et vérifie la vidéo. |

## Utilisation

1. Copie le dossier du format que tu veux.
2. Mets dedans le projet ou le sujet à expliquer.
3. Lance ton agent dans ce dossier et demande, par exemple : « Explique-moi comment fonctionne ce projet. »

Chaque dossier contient le même texte sous deux noms :
- `CLAUDE.md`, lu automatiquement par Claude Code ;
- `AGENTS.md`, lu par Codex et d'autres agents.

Tu peux aussi copier les quatre consignes dans un seul `CLAUDE.md` de ton projet, et dire à chaque fois quel format tu veux.

## Pour le format vidéo

- Python 3 et ffmpeg installés. Manim s'installe dans un environnement local.
- Voix : la variable `ELEVENLABS_API_KEY` si tu as un compte ElevenLabs. Sinon, la voix de synthèse de ton ordinateur est utilisée.

## Liens

- Le post de Karpathy : https://x.com/karpathy/status/2105819303471976479
- nanoGPT, le projet testé dans la vidéo : https://github.com/karpathy/nanoGPT

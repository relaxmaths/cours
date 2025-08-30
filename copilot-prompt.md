# copilot-prompt.md

Ce projet contient des cours de mathématiques pour le primaire (1ère à 6ème année), structurés en fichiers Markdown au format lia-script. Il respecte le programme scolaire de la Fédération Wallonie-Bruxelles (WBE).

## Structure du projet
- Chaque cours est organisé dans un dossier spécifique (ex : `maths/numeration-9999`).
- Le fichier principal de chaque cours est `_definition.md`, qui sert de point d’entrée et inclut les autres parties du cours via des directives `!import`.
- Les fichiers de liaison dans le dossier `liaisons` permettent à l’extension Markdown Include de fusionner les différentes parties du cours pour la publication ou l’impression.
- Les images utilisées sont principalement au format SVG et se trouvent dans le dossier `images`. Privilégier ce format pour toute création ou adaptation d’illustration.

## Consignes pour la génération de contenu
- Utiliser le style, le ton et la présentation des exemples existants (voir `numeration-999`).
- Le contenu doit être rédigé en français de Belgique (utiliser "septante", "nonante", etc.).
- Les exercices, explications et consignes doivent être adaptés au niveau primaire, en respectant la progressivité et la clarté pédagogique.
- Les vidéos, QR codes, tableaux et images doivent être intégrés comme dans les exemples, en respectant la structure lia-script.
- Les nouveaux exercices ou contenus doivent respecter le programme officiel WBE.
- Les imports et exports pour Markdown Include doivent être proposés automatiquement lors de la création ou de la modification d’un cours.
- Les fichiers de liaison doivent être générés ou adaptés pour chaque nouveau cours.

## Exemples de tâches à demander à Copilot
- Copier et adapter un cours existant pour un autre niveau ou une autre thématique.
- Générer de nouveaux exercices, exemples ou illustrations au format SVG.
- Créer ou mettre à jour les fichiers de liaison pour Markdown Include.
- Vérifier la conformité du contenu avec le programme WBE.
- Adapter le ton et le style à celui des cours déjà présents dans le projet.

## Points d’attention
- Toujours vérifier la cohérence des imports/exports et la structure des dossiers.
- Respecter la terminologie et les usages propres au français de Belgique.
- Privilégier la clarté, la progressivité et l’interactivité dans les contenus.
- S’assurer que les images et illustrations sont libres de droits ou créées spécifiquement pour le projet.

---
Ce prompt sert de guide pour l’assistant Copilot afin de garantir la cohérence, la qualité et la conformité des contenus générés ou adaptés dans ce projet de cours de mathématiques pour le primaire.
Si Copilot détecte des nouvelles choses qui pourraient être intéressantes d'intégrer à ce fichier, il le propose spontanément et pose les questions nécessaires.

# Contexte du projet — diapo

Ce dépôt contient une présentation web basée sur **Slidev** (Vite + Vue + Markdown).
Cette présentation est constituée de deux parties, la première partie est faite par Mounir MEKOUI et la seconde par Tahar OTHMANE.
Elle se fera devant un jury de professeurs de l'universié de Reims Champagne-Ardenn dans le cadre d'une soutenance de fin de stage bibliographique.
Le sujet est : "La production d'énergie par l'éolien. Principe physique, évolution, problématiques, statistiques, recherche actuelle."
Elle se base sur 2 rapports bibliographiques que vous pouvez trouver dans les fichiers ./Rapport_stage_eolien_en_mer_OTMANE.md et ./rapport_stage_eolien_terrestre_MEKOUI.md.
Les figures de ces rapports se trouvent dans les dossiers ./figures_OTMHANE/ et ./figures_MEKOUI/.
La présentation doit durer 20 min. (10 min par personne).
Mounir couvre la partie éolien terrestre et Tahar couvre la partie éolien en mer (off-shore/far-shore).

## Skills disponibles

Pour toute tâche liée à la création ou la modification de slides, utilise le skill Slidev :

- **Skill Slidev** : `.agents/skills/slidev/SKILL.md`

Ce skill couvre :
- La syntaxe Markdown Slidev (séparateurs `---`, frontmatter, notes présentateur)
- Les animations (`v-click`, `v-clicks`, `v-motion`)
- Les layouts intégrés (`cover`, `two-cols`, `image-left`, etc.)
- Le CSS scopé et les composants Vue personnalisés
- L'export PDF/PPTX et le déploiement

## Structure du projet

```
slides.md          # Point d'entrée principal de la présentation
pages/             # Slides secondaires importées via `src:`
components/        # Composants Vue personnalisés
snippets/          # Extraits de code importables dans les slides
style.css          # CSS global
figures_OTHMANE/   # Figures/images pour la présentation Othmane
figures_MEKOUI/    # Figures/images pour la présentation Mekoui
```

## Commandes utiles

```bash
pnpm run dev       # Lancer le serveur de développement (http://localhost:3030)
pnpm run build     # Build SPA statique
pnpm run export    # Exporter en PDF (nécessite playwright-chromium)
```

## Conventions

- Les slides sont séparées par `---`
- Les animations se font avec `v-click` / `v-motion` pour les entrées progressives
- Préférer les grilles CSS manuelles (`display: grid`) aux layouts Slidev pour un contrôle fin
- Les images sont intégrées avec `<img>` standard plutôt que des composants Slidev
- Les notes présentateur sont dans les commentaires HTML `<!-- ... -->`

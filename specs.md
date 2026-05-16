# Spécifications — Illustrations IA pour la présentation Slidev

## Contexte

Présentation de soutenance de stage bibliographique L3 Physique — "La production d'énergie par l'éolien".
Jury : enseignants-chercheurs de l'URCA / ITheMM.
Outil : Slidev (Vite + Vue + Markdown).
Budget : ~10 $ de crédit fal.ai (GPT-Image-2).

---

## Stratégie de sélection (4 images)

| # | Slide | Titre | Rôle de l'illustration | Priorité |
|---|-------|-------|------------------------|----------|
| 1 | **17.md** | Fondations posées et flottantes | Schéma comparatif technique des 7 types de fondations en coupe d'eau | Cruciale — slide entièrement textuelle |
| 2 | **06.md** | Limite de Betz | Schéma de fluide : vent entrant V₁, ralentissement au rotor (a=1/3), sillage V₂, tube de courant | Très pédagogique — concept abstrait |
| 3 | **22.md** | Innovations | Triptyque conceptuel : supraconducteur, Maglev, H₂ offshore | Refonte visuelle — contenu futuriste sans image |
| 4 | **13.md** | Avantages et inconvénients | Infographie équilibrée : bilatéral avantages vs défis | Humanise la liste à puces |
| 5 | **08.md** | Chaîne de conversion | Schéma complet : vent → rotor → multiplicateur → génératrice → convertisseur → réseau / STEP | Nouvelle demande utilisateur |

> **Images existantes conservées** — tous les schémas et graphiques issus des rapports de stage (`figures_MEKOUI/` et `figures_OTHMANE/`) restent inchangés, à l'exception de la substitution volontaire sur la slide 08 par l'image IA plus complète.

---

## Style artistique retenu

**"Technical scientific illustration"** — schéma éditorial scientifique académique.

- Inspiré des revues scientifiques (*Nature*, *Physics Today*, manuels d'ingénierie énergétique)
- Lignes propres et nettes, palette restreinte
- Coupes techniques avec annotations claires
- **Ni cartoon, ni photoréalisme pur**
- Cohérence avec le thème Slidev `apple-basic` (tons bleus profonds `#003d7c` et blancs)

---

## Prompts (prêts à exécuter sur fal.ai — GPT-Image-2)

### Image 1 — Fondations posées et flottantes (slide 17)

```text
Illustration scientifique technique propre montrant une coupe transversale de l'océan avec 7 types de fondations d'éoliennes offshore comparées côte à côte. De gauche à droite : monopieu (tube d'acier unique), jacket (structure treillis sur pieux), gravitaire (base béton), semi-submersible (plateforme flottante), SPAR (bouée cylindrique longue lestée), TLP (lignes tendues ancrées), et barge (base flottante plate). Chaque fondation supporte une éolienne blanche identique au-dessus de l'eau. Lignes de flottaison et annotations de profondeur en mètres (0m, 30m, 60m, 100m). Texte des labels en français : "Monopieu", "Jacket", "Gravitaire", "Semi-submersible", "SPAR", "TLP", "Barge". Style : diagramme de manuel d'ingénierie énergétique, dessin technique éditorial scientifique, palette bleu marine et blanc (#003d7c), lignes nettes et propres, sans photoréalisme, pédagogique et académique. Fond blanc.
```

**Dimensions** : 1792×1024 px (16:9)
**Fichier cible** : `figures_IA/fondations_offshore.png`

---

### Image 2 — Limite de Betz / Tube de courant (slide 06)

```text
Schéma physique propre de type manuel de mécanique des fluides illustrant la limite de Betz. Un tube de lignes de courant se rétrécit horizontalement en passant à travers un disque de rotor au centre. Côté gauche : vent entrant avec vitesse V1 et tubes de courant larges. Centre : disque de rotor avec le facteur d'induction axiale a = 1/3 et vitesse V. Côté droit : sillage avec vitesse réduite V2 et tubes de courant élargis. Annotations clés en français : "Énergie disponible P = ½ρAV³", "Coefficient de puissance Cp", "Cp max = 16/27 ≈ 0,593", "a = 1/3". Dégradé subtil bleu-gris pour visualiser la densité de l'air. Style : illustration éditoriale scientifique, lignes vectorielles nettes, annotations en français, précis et minimal. Fond blanc.
```

**Dimensions** : 1792×1024 px (16:9)
**Fichier cible** : `figures_IA/limite_betz.png`

---

### Image 3 — Innovations éoliennes (slide 22)

```text
Illustration scientifique divisée en trois panneaux verticaux montrant des innovations futures dans l'éolien. Panneau gauche : coupe d'une génératrice supraconductrice à l'intérieur d'une nacelle d'éolienne, bobines avec refroidissement cryogénique标注. Panneau central : palier magnétique (maglev) supportant un arbre de turbine, lignes de champ magnétique visibles et zéro friction. Panneau droit : plateforme éolienne flottante offshore avec un électrolyseur intégré produisant de l'hydrogène vert, bulles d'H2 remontant, sans câble sous-marin. Style : illustration éditoriale technique unifiée, palette bleu-blanc, labels en français clairs, esthétique moderne de diagramme d'ingénierie. Fond blanc.
```

**Dimensions** : 1792×1024 px (16:9)
**Fichier cible** : `figures_IA/innovations_eoliennes.png`

---

### Image 4 — Avantages vs Inconvénients (slide 13)

```text
Infographie scientifique équilibrée en deux moitiés. Moitié gauche ("Avantages") : collines verdoyantes avec éoliennes modernes, soleil, petites silhouettes d'ouvriers, ligne électrique, molécules de CO2 s'effaçant. Moitié droite ("Défis") : ciel plus sombre nuageux au-dessus d'éoliennes, silhouettes de chauve-souris et d'oiseau avec symboles d'avertissement, fragment de pale usée, icône de batterie/stockage, sablier symbolisant l'intermittence. La composition est divisée par un axe central subtil comme une balance. Style : infographie éditoriale scientifique, illustration vectorielle plate, ton académique sérieux, pas cartoon, palette bleu-vert-gris. Fond blanc. Texte en français : "Avantages" et "Inconvénients".
```

**Dimensions** : 1792×1024 px (16:9)
**Fichier cible** : `figures_IA/avantages_inconvenients.png`

---

## Contraintes technique Slidev

| Paramètre | Valeur |
|-----------|--------|
| Dimensions | 1792×1024 px (format paysage 16:9) |
| Format | PNG |
| Fond | Blanc opaque |
| Dossier cible | `/figures_IA/` |
| Intégration | `<img src="/figures_IA/fichier.png" class="h-80 mx-auto" />` |

---

## Budget estimé (fal.ai)

- GPT-Image-2 : ~0.02–0.08 $ par image (selon résolution)
- **Total 4 images** : < 0.50 $ (très largement dans les 10 $ de crédit)
- Marge de sécurité : on peut générer des variantes si un rendu ne convient pas.

---

## Plan d'intégration dans les slides

### Slide 17 (fondations)
Actuellement : grille texte 2 colonnes sans image.
Modification : colonne gauche texte, colonne droite `<img src="/figures_IA/fondations_offshore.png" class="h-96 mx-auto" />`.

### Slide 06 (Betz)
Actuellement : formules + tableau à droite.
Modification : colonne gauche texte + équations, colonne droite `<img src="/figures_IA/limite_betz.png" class="mx-auto" />`.

### Slide 22 (innovations)
Actuellement : 3 boîtes de texte colorées sans image.
Modification : image triptyque en haut ou en bas, ou remplacement des 3 boîtes par une image centrée avec légende.

### Slide 13 (avantages/inconvénients)
Actuellement : deux colonnes de listes à puces.
Modification : remplacer ou accompagner par `<img src="/figures_IA/avantages_inconvenients.png" class="h-80 mx-auto" />`.

---

## Checklist d'exécution

- [ ] Générer image 1 (fondations) — test validé
- [ ] Générer image 2 (Betz)
- [ ] Générer image 3 (innovations)
- [ ] Générer image 4 (avantages/inconvénients)
- [ ] Télécharger les images dans `/figures_IA/`
- [ ] Modifier `pages/17.md` pour intégrer image 1
- [ ] Modifier `pages/06.md` pour intégrer image 2
- [ ] Modifier `pages/22.md` pour intégrer image 3
- [ ] Modifier `pages/13.md` pour intégrer image 4
- [ ] Tester le rendu avec `pnpm run dev`
- [ ] Exporter en PDF (`pnpm run export`) pour vérifier la netteté

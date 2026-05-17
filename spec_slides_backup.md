# Specs Slides backup pour le Q/R

Contexte : on a un deck Slidev (thème apple-basic, durée 20 min) sur l'éolien terrestre + offshore. Les slides 1–26 sont terminées. Il faut ajouter **5 slides backup** après le slide 26 (merci/questions). Elles ne seront pas présentées mais serviront de support visuel si le jury pose une question pointue.

## Conventions du projet (à respecter strictement)

- Chaque slide = un fichier dans `pages/` (ici : `27.md`, `28.md`, `29.md`, `30.md`, `31.md`)
- Ajouter les `src:` correspondants dans `slides.md` après le bloc du slide 26
- Utiliser les mêmes composants et patterns que les slides existantes :
  - `<Box type="info">`, `<Box type="key">`, `<Box type="alert">` pour les encadrés
  - `v-click`, `v-motion` avec les mêmes paramètres d'animation (`:initial="{ x: -30, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { duration: 400 } }"`)
  - Grilles Tailwind (`grid grid-cols-2 gap-8`)
  - KaTeX pour les maths (`$$...$$` et `$...$`)
  - Tableaux en Markdown (le CSS global gère déjà le style académique)
- Pas d'images IA pour les backups (pas besoin de fal.ai) — que du texte, des équations et des tableaux
- Chaque slide commence par un titre `#` dans un div v-after v-motion
- Commentaire HTML en bas de chaque slide pour les speaker notes
- Police, couleurs et style : identiques au reste du deck (bleu `#1a3358` / `#2c5f9e`)
- Ajouter un séparateur visuel avant les backups : un slide section "Slides de secours"

## Contenu des 6 slides à créer

### Slide 27 — Séparateur "Slides de secours"

Layout section, fond `bg-[#003d7c] text-white` (même style que les slides 04 et 15).
Titre : "Slides de secours"
Sous-titre : "Support pour les questions du jury"

### Slide 28 — Démonstration complète de la limite de Betz

Titre : "Backup : Démonstration de la limite de Betz"

Contenu en deux colonnes :

Colonne gauche — les étapes de la démonstration :

1. Tube de courant : conservation de la masse → ρ A₁ V₁ = ρ A V = ρ A₂ V₂
2. Théorème de quantité de mouvement (force sur le rotor) : F = ρ A V (V₁ - V₂)
3. Puissance extraite : P_extraite = F × V = ρ A V² (V₁ - V₂)
4. On pose a = 1 - V/V₁ (facteur d'induction axiale), et on montre que V = V₁(1-a), V₂ = V₁(1-2a)
5. Coefficient de puissance : C_p = P_extraite / P_dispo = 4a(1-a)²
6. dC_p/da = 0 → a = 1/3 → C_p,max = 16/27 ≈ 0,593

Colonne droite — les hypothèses et limites :

- Flux 1D, fluide incompressible, sans rotation du sillage
- Pas de frottement visqueux, nombre infini de pales
- En pratique : pertes en bout de pale, traînée, rotation du sillage → C_p réel ≈ 0,45–0,50
- Formule encadrée (Box type="key") : C_p,max = 16/27 ≈ 0,593

Speaker notes : "Si on me demande de redémontrer Betz au tableau, je peux m'appuyer sur ce slide."

### Slide 29 — Décomposition du LCOE et sensibilité aux hypothèses

Titre : "Backup : LCOE — Pourquoi les chiffres divergent"

Contenu :

Formule du LCOE (en display math) :

$$
\text{LCOE} = \frac{\sum_{t=0}^{N} \frac{I_t + M_t + F_t}{(1+r)^t}}{\sum_{t=0}^{N} \frac{E_t}{(1+r)^t}}
$$

avec I_t = investissement, M_t = maintenance, F_t = combustible, E_t = énergie produite, r = taux d'actualisation, N = durée de vie.

Tableau de sensibilité (3 colonnes) :

| Paramètre            | Hypothèse basse | Hypothèse haute | Impact sur LCOE |
| -------------------- | --------------- | --------------- | --------------- |
| Taux d'actualisation | 4 %             | 8 %             | +30 à +50 %     |
| Durée de vie         | 30 ans          | 20 ans          | +15 à +25 %     |
| Raccordement         | Exclu           | Inclus          | +5 à +15 %      |
| Facteur de charge    | 26 %            | 20 %            | +20 à +30 %     |

Box type="alert" : "C'est pourquoi l'Observatoire (82 €/MWh), TI (96 €/MWh) et la Cour des Comptes (42–50 €/MWh pour le nucléaire existant) ne se contredisent pas : ils ne calculent pas la même chose."

Speaker notes : "Ce slide répond à la question : pourquoi vos sources donnent des chiffres différents ?"

### Slide 30 — Détails sur les terres rares

Titre : "Backup : Terres rares — De quoi parle-t-on ?"

Contenu en deux colonnes :

Colonne gauche — composition d'un aimant NdFeB :

Tableau :
| Élément | Rôle | % masse aimant |
|---|---|---|
| Néodyme (Nd) | Base magnétique | ~25–30 % |
| Praséodyme (Pr) | Substitut partiel Nd | ~5 % |
| Dysprosium (Dy) | Coercitivité thermique | ~3–6 % |
| Terbium (Tb) | Coercitivité (alternative) | ~0–2 % |
| Fer (Fe) + Bore (B) | Matrice | ~60–65 % |

Chiffres clés : ~200 kg d'aimants par MW → ~70 kg de terres rares par MW. Pour 3 MW (machine type) : ~200 kg de terres rares.

Colonne droite — enjeux géopolitiques et alternatives :

- Chine : 80–90 % de l'extraction ET du raffinage
- Impact écologique de l'extraction : effluents radioactifs (thorium), rejets acides, pollution des eaux
- Alternative 1 : rotor bobiné (ENERCON) → 0 kg de terres rares, rendement légèrement moindre
- Alternative 2 : génératrices supraconductrices (ÉcoSwing, SUPRAPOWER) → prototype
- Alternative 3 : recyclage des aimants en fin de vie (filière naissante)

Box type="info" : "La dépendance n'est pas une fatalité technique (ENERCON s'en passe), mais un choix industriel motivé par la performance et le coût."

Speaker notes : "Si on me demande pourquoi on ne se passe pas tout simplement des terres rares."

### Slide 31 — Repowering : les chiffres détaillés

Titre : "Backup : Repowering — Gains physiques"

Contenu en deux colonnes :

Colonne gauche — tableau comparatif (reprendre les données de l'annexe C.2 du rapport Mounir) :

|                   | Ancienne  | Repowerée   |
| ----------------- | --------- | ----------- |
| Hauteur mât       | 80 m      | 120 m       |
| Puissance         | 1,5–3 MW  | 4,2–4,5 MW  |
| Diamètre rotor    | X-80 à 82 | X-160 à 163 |
| Facteur charge    | 23 %      | 31 %        |
| Productible/an    | 4 533 MWh | 11 800 MWh  |
| Foyers alimentés  | 2 266     | 5 906       |
| Vitesse démarrage | 4 m/s     | 3 m/s       |

Colonne droite — pourquoi ça marche (explication physique) :

Deux effets combinés :

1. Altitude → V plus élevé (loi en puissance V(H) = V₀(H/H₀)^α)
2. Surface balayée → A = π R² : doubler R = ×4 en surface

Calcul rapide (Box type="key") :

- V passe de ~6,5 m/s (80 m) à ~7,5 m/s (120 m) en terrain agricole (α = 0,22)
- Ratio en V³ : (7,5/6,5)³ ≈ 1,54 → +54 % de puissance disponible par m² de surface balayée
- Surface : (80/41)² ≈ 3,8 → ×3,8 en surface
- Combiné : ×5,8 en puissance disponible → ×2,6 en production réelle (pertes, pitch, etc.)

Fait marquant (Box type="alert") : "Seulement 124 MW repowerés en France. Frein : procédures complètes même sur site existant."

Speaker notes : "Ce slide répond à la question : d'où vient le facteur ×3,5 en production ?"

### Slide 32 — Cartes des parcs offshore français

Titre : "Backup : Parcs offshore français — posés et flottants"

Contenu : deux images côte à côte sur une grille grid-cols-2 :

Colonne gauche :

- Image : `/figures_OTHMANE/annexeA_fig3.png`
- Légende : "Parcs posés — opérationnels et en projet"

Colonne droite :

- Image : `/figures_OTHMANE/annexeA_fig4.png`
- Légende : "Parcs flottants — démonstrateurs et projets commerciaux"

En dessous, un résumé en une ligne :
"Manche/Atlantique = posé (fonds < 60 m) · Méditerranée = flottant exclusivement (fonds rapidement profonds)"

Box type="info" : "Potentiel technique : 169 GW posé + 454 GW flottant = 623 GW exploitables (vs 1,5 GW installés fin 2024)."

Speaker notes : "Si on me demande où sont les parcs et pourquoi le flottant en Méditerranée."

## Modifications dans slides.md

Ajouter après le dernier bloc `src: ./pages/26.md` :

```
---
src: ./pages/27.md
---
src: ./pages/28.md
---
src: ./pages/29.md
---
src: ./pages/30.md
---
src: ./pages/31.md
---
src: ./pages/32.md
```

## Modifications dans global-bottom.vue

Ajouter les slides 27–32 dans le Set `HIDE_ON` pour masquer la barre de navigation sur les slides backup (elles ne font pas partie de la présentation principale) :

```js
const HIDE_ON = new Set([1, 3, 14, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32]);
```

C'est tout. Génère les 6 fichiers et les modifications.

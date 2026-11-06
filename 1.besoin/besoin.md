# Expression du Besoin Final : Veille Technologique & Automatisation Agentique

---

## 1. Définition & Fondamentaux pour le Développeur Informatique

### 1.1 Qu'est-ce que la Veille Technologique ?
La **veille technologique** est une activité continue, proactive et structurée par laquelle un développeur ou une équipe d'ingénierie surveille, collecte, analyse et exploite les informations relatives aux innovations techniques, aux évolutions d'écosystèmes, aux bonnes pratiques et aux failles de sécurité.

Elle ne se résume pas à faire défiler des réseaux sociaux ; elle s'organise rigoureusement selon un **cycle en 5 étapes** :
1. **Cibler :** Délimiter les thématiques stratégiques prioritaires (ex: évolutions de Laravel, patterns Alpine.js, agents autonomes) pour éviter de subir l'infobésité.
2. **Collecter :** Automatiser et centraliser l'écoute sur des sources fiables et primaires (rapports de référence, dépôts GitHub officiels, release notes, flux RSS spécialisés).
3. **Filtrer :** Distinguer le signal technique utile du bruit médiatique et du marketing (*hype* éphémère).
4. **Analyser :** Tester, mesurer la maturité d'une brique et évaluer son adéquation avec l'architecture logicielle de notre projet.
5. **Diffuser & Agir :** Restituer les enseignements à l'équipe (ADR, documentation) et intégrer les technologies retenues dans le prototype ou dans les compétences d'**`AgentDev`**.

### 1.2 Pourquoi la Veille est Indispensable pour un Développeur ?
- **Protection contre l'obsolescence :** Les technologies web et IA évoluent à un rythme annuel soutenu. Sans veille, les compétences d'un développeur se dégradent en 18 à 24 mois.
- **Efficience et qualité de conception :** Découvrir des briques éprouvées évite de « réinventer la roue » et assure un gain de vélocité tout en diminuant la dette technique.
- **Sécurité et robustesse :** Identifier proactivement les vulnérabilités (CVE) et les ruptures de compatibilité (*breaking changes*) au sein des dépendances open-source.
- **Décisions d'architecture objectives :** Permet d'arbitrer les choix d'implémentation sur la base de métriques et d'analyses documentées plutôt que sur des intuitions ou des effets de mode.

---

## 2. Problématique Technique du Lab

- **L'infobésité et le bruit informationnel :** L'explosion des outils autour de l'IA et du web submerge le développeur sous des milliers de publications non filtrées.
- **Risques de dérive sans cadre méthodologique :**
  - Perte de temps sur des solutions expérimentales abandonnées au bout de quelques semaines.
  - Pollution de notre stack technique (Laravel 12, Alpine.js, Tailwind CSS) par des dépendances superflues.
  - Dérive cognitive de l'agent **`AgentDev`** qui risque de proposer du code obsolète ou hors-conventions s'il n'est pas guidé par un outillage de veille strict.

---

## 3. Pistes d'Exploration & Découvertes Initiales

1. **Observatoires globaux d'état de l'art :**
   - Étude approfondie de la plateforme **`stateofai.dev`** (enquête mondiale Devographics mesurant les pratiques réelles, l'adoption des modèles et les frictions vécues par les développeurs).
2. **Catalogues open-source de compétences IA (Skills) :**
   - Exploration des registres spécialisés (ex: `skills.sh`, dépôts GitHub) en requêtant les termes anglophones de référence (*technology watch*, *tech-radar*, *trend-scout*).
   - Analyse comparative de 2 à 3 skills réels pour décortiquer leur prompt engineering, leurs sources de données et leur méthode de tri.

---

## 4. Le Besoin Final Concret du Lab

Le livrable et le résultat attendu de ce lab se décomposent en **trois objectifs indissociables** :

1. **Assimilation humaine (Évaluation Live Coding sans IA) :**
   L'apprenant doit être capable d'expliquer devant le formateur la définition de la veille, de justifier son importance pour son métier, et de détailler les 5 étapes du cycle sans support IA ni prompteur.
2. **Benchmark et état de l'art documenté :**
   Constituer un diaporama Marp (`2.benchmark/benchmark.md`) comparant les enseignements de `stateofai.dev` et les skills de veille anglophones existants, avec une grille multicritères claire.
3. **Outillage agentique formalisé (`tech-watch`) :**
   Rédiger la spécification technique et l'ADR du skill IA **`tech-watch`** (respect strict de la nomenclature sans préfixe `lab-*`, 10 rubriques Anthropic) pour doter **`AgentDev`** d'une compétence de veille ciblée, souveraine et économe en tokens.

# Consignes de Spécification : Étape 4 - Spécification du Skill IA (`spec-skill.md`)

Ce dossier est dédié à la formalisation technique du skill IA issu de vos tests d'expérimentation.

> ⚠️ **Règle Pédagogique & Nomenclature :**  
> 1. Le skill IA ne doit **JAMAIS** porter le préfixe `lab-*` (ex: interdit `lab-veille`, valide `tech-watch`).
> 2. La décision d'architecture (ADR) doit être justifiée par les résultats concrets obtenus dans `4.realisation/`.

---

## 🎯 Travaux à Réaliser par l'Apprenant

### 1. Décision d'Architecture (ADR)
- Formaliser le problème technique rencontré.
- Comparer les options étudiées (ex: adaptateur de skill open-source vs skill conçu de zéro).
- Justifier le choix final à partir des résultats obtenus dans `4.realisation/` (précision des sources, maîtrise des tokens, simplicité d'usage pour `AgentDev`).

### 2. Rédaction de `spec-skill.md`
- Définir le contrat d'interface et la mission de la compétence `tech-watch`.
- Renseigner les rubriques normées selon le standard Anthropic (Mission, Déclenchement, Règles inviolables, Procédure, etc.).

### 3. Transition vers le Skill Opérationnel
- Avec l'assistance de `w-spec-skill` et `skill-creator`, générer le fichier final dans `.agents/skills/tech-watch/SKILL.md`.
- Valider la conformité via le validateur déterministe :
  ```powershell
  node .agents/skills/skill-creator/scripts/validate-skills.cjs
  ```


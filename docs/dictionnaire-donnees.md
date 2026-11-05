# Dictionnaire des données

> Un champ par ligne, d'après `SUJET.md` et le fichier de `donnees/`. La première ligne sert de modèle.

| Champ | Signification | Type | Règle de validation | Unité | Exemple |
| --- | --- | --- | --- | --- | --- |
| `id` | Identifiant unique | texte | non vide, absent des données | — | 002 |
| `date` | Date de l'operation | texte | AAAA-MM-JJ | - | 2026-10-25 |
| `parcelle` | Parcelle où l'operation a lieu | texte | non vide | - | P2 |
| `culture` | Légume concerné | texte | non vide | - | gombo |
| `operation` | Travail effectué | texte | non vide, une valeur de la liste autorisée | - | désherbage |
| `coutFCFA` | Depense enregistrée | nombre | non vide, positif ou nul | FCFA | 3500 |
**Listes de valeurs autorisées** : operation, parcelle, culture 

**Sources** : `SUJET.md`, `donnees\operations.json`

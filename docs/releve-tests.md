# Relevé des tests

> Écrivez le résultat attendu avant d'essayer. Un écart n'est pas une faute : notez-le, corrigez, refaites le test.

**Calculs à la main** : refaites à la main les résultats de référence de `SUJET.md`, puis comparez avec votre programme. 
Parcelle | calcul                           | resultat attendu
P1       | 4 opérations: 3000+2000+8000+2500| 15500FCFA
P2       | 3 opérations: 4500+1500+3500     | 9500
P3       | 3 opérations: 5000+4000+6000     | 15000FCFA
**Essais dans le menu** : un ajout valide (encore là après redémarrage), chaque règle refusée, une recherche introuvable, chaque tri, la synthèse, un choix inconnu.

| Action | Attendu | Obtenu | Testeur |
| --- | --- | --- | --- |
| Ajouter 011 valide |operation ajoutée  |Opération 011 ajoutée, Le registre compte 11 opérations |moi |
| Ajouter avec id 003 | i'operation est refusé |Opération 003 introuvable | moi|
| Recherche culture tomate |nombre d'operation  |5 opérations pour la culture tomate |moi |
| Trier par coût croissant | Du plus petit au plus grand |Commence par 1500FCFA et finit par 8000FCFA  |moi |
| Synthèse | Coût total des 11 operations |Coût total: 42500 | moi|
| Ajouter année |Ajouter date format JJ-MM-AAAA |Choix inconnu : « 02-11-2026 ». Tapez un chiffre du menu. |moi |

**Sur un autre poste** (`git clone`, `node app.js`, `npm test`, en suivant le README) : ✏️

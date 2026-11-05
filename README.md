# Registre des opérations maraîchères

> Projet individuel du SAS DFS, brief 1 (sujet : [SUJET.md](SUJET.md)). Remplacez chaque ✏️ par votre texte, puis supprimez cette ligne.

## Contexte

La responsable d'une exploitation maraîchère pedagogique note ses operations dans un carnet papier. Elle veut saisit dans un terminal chaque operation: un identifiant, une date, la parcelle, la culture, le type d'operation et son coût en FCFA. Le programme affiche un menu pour ajouter, lister, rechercher et trier les operations. Les données sont enregistrées dans `donnees/operation.json` et les saisies invalides sont refusées sans arrêter le programme. L'outil n'enregistre pas les revenus et ne donne pas non également de conseil de culture.

## Prérequis et lancement

- Node.js 20 ou plus récent, Git ; aucune bibliothèque à installer.

```bash
git clone https://github.com/VOTRE-COMPTE/brief-1-registre-maraicher.git
cd brief-1-registre-maraicher
node app.js
npm test
```

Sous PowerShell, si `npm` est bloqué : `npm.cmd test`.

## Fonctionnalités

 *Cochez seulement ce qui marche : `- [x]`.*

- [x] Données lues et enregistrées dans `donnees/operations.json`
- [x] Ajouter une opération, saisies invalides refusées sans arrêter le programme
- [x] Lister les opérations, message si le registre est vide
- [x] Rechercher par identifiant ou par parcelle ; filtrer par culture
- [x] Trier par coût ou par date
- [x] Synthèse : total, nombre et total par parcelle, coût minimum et maximum
- [x] Bonus : supprimer et modifier une opération (choix 6 et 7)
- [x] Bonus : tri par coût décroissant, parcelle la plus coûteuse

## Données

 *Le fichier, le nombre d'opérations, les champs (voir [docs/dictionnaire-donnees.md](docs/dictionnaire-donnees.md)), les unités. Rappelez qu'elles sont fictives.*

 Le fichier: `donnees/operations.json`, nombre d'opération: 10, les champs: 6 champs, les unittés: les coûts en FCFA et les données sont fictives.

## Limites

 *Au moins trois. Par exemple : le registre enregistre des dépenses, pas les revenus, il ne mesure donc pas la rentabilité.*
 
Il n'y a pas de quantité récoltée, ni de surface des parcelles: les parcelles ne peuvent pas être comparer entre elles. *La liste des operations est fermée: une autre intervention ne peut pas être enregistrée.* Le même identifiant ne peut pas être enregistrer deux fois.

## Documents

[Dictionnaire des données](docs/dictionnaire-donnees.md) · [Tâches](docs/taches.md) · [Relevé des tests](docs/releve-tests.md) · [Journal de recherche](docs/journal-recherche.md) · [Fiche agronomique](docs/fiche-agronomique.md) · [Fiche individuelle](docs/fiche-individuelle.md)

## Auteur

 *Prénom NOM, compte GitHub. Entraide : avec qui, sur quoi.*
 Prénom Nom: MARIE-MANUELA SABINE AMENAN DALY
 Compte GitHub: Manu15Mai
 Entraide: MAMADOU VEHI EVELYNE pour l'explication de certaines fonctions

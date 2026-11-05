# Fiche individuelle

> Une page, avant la livraison. Prénom, nom, compte GitHub : 
 NOM: DALY
 PRENOM: MARIE-MANUELA SABINE AMENAN
 COMPTE GitHub: Manu15Mai

1. **Une fonction que j'ai écrite**, et comment elle marche :
  La fonction ecrite
   export async function chargerJson(chemin) {
  const d = await readFile(chemin,`utf-8`)
  return JSON.parse(d)
   }
   Comment elle marche
    La fonction reçoit l'adresse d'un fichier(chemin), ouvre le fichier, lit le texte et attand la fin de la lecture(await readFile). Elle transforme le texte lu en vraies données(JSON.parse) et les renvoie.

2. **Une difficulté, et sa solution** : 
    La difficulté
  Le fichier était mal extrait donc Git ne les trouvait pas.

    La solution
 J'ai créé un nouveau dépôt GitHub et refait les commandes Git dans le bon dossier.

3. **L'entraide** (qui m'a aidé, qui j'ai aidé, sur quoi) : 
j'ai été aidé par mes amis notament ABO KOUAME JOSUE, LOHOUIN LOU FRESHNELLE, GUEI DINASSON ARMEL, SOUMAHORO CHEICK TIDYANE, pour la compréhension du projet.
j'ai aidé également GUEI ARMEL pour la rectification des erreurs.





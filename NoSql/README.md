# Réponse aux questions sur la partie NoSql

TP 3 MongoDB - Redis :

-> Quelles sont les limites d’une base données orientées document ?

    Le probleme concerne le poids du document qui augmente au fur et à mesure que la BDD augmente.

    D'ailleurs voici le résultat de la BDD à l'heure actuelle si on récupère les nom des personnes : Tintin Tintin Tintin Tintin Tintin Tintin Tintin Tintin Tintin Tintin René Guy Tintin René Guy Tintin René Guy Tintin René Guy Tintin René Guy

-> Quelles sont les types de données stockés dans Redis, que peut on faire comme types de requêtes ?

    Les types de données de Redis correspondent finalement à un grand tableau associatif sur lequel il est possible de faire des requête sur une donnée ou un ensemble de donnée. Le tout est stocké en mémoire vive (RAM).

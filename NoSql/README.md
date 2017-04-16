# Réponse aux questions sur la partie NoSql

TP 3 MongoDB - Redis :

Réponse aux Questions:

-> Quelles sont les limites d’une base données orientées document ?

    Le probleme concerne le poids du document qui augmente au fur et à mesure que la BDD augmente.

    D'ailleurs voici le résultat de la BDD à l'heure actuelle si on récupère les nom des personnes : Tintin Tintin Tintin Tintin Tintin Tintin Tintin Tintin Tintin Tintin René Guy Tintin René Guy Tintin René Guy Tintin René Guy Tintin René Guy.

    Aussi les possibilité de requêtage donnent à l'utilisateur moins de fonctionnalités, et il doit lui-même
    s'assurer de la cohérence des données.

-> Quelles sont les types de données stockés dans Redis, que peut on faire comme types de requêtes ?

    Les types de données de Redis correspondent à des types de donnée simple par example un grand tableau associatif sur lequel il est possible de faire des requête sur une donnée ou un ensemble de donnée.
    Le tout est stocké en mémoire vive (RAM) avec une valeur pour une clef.

    Les requètes possibles sont : SET GET TTL ZADD SADD

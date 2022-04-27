#Activité 10

Vous devez implémenter une fonction prennant un mot de passe en paramètre et effectuant une attaque par force brute.

Vous devez générer tous les mots de passe jusqu'à ce que vous atteignez le mot de passe reçu. Ex: aaa, aab, aac, ..., zzz.

Les mots de passe sont de 3 à 5 caractères de longueur et peuvent contenir des lettres et/ou des chiffres. Vous ne pouvez pas utiliser la longueur du mot de passe dans votre algorithme.

Vous devez ensuite mettre la ligne :$start_time = microtime(true); avant l'exécution de chaque appel de fonction. Ensuite, mettre $end_time = microtime(true); $execution_times[] = ($end_time - $start_time);

Finalement vous devez afficher vos temps d'exécution sur votre page PHP. Ex:
Appel 1: xxxx ms
Appel 2: xxxx ms
Appel 3: xxxx ms

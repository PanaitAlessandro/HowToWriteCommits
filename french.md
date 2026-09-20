# Comment écrire les commits sur Git ![github](https://www.readmecodegen.com/api/social-icon?name=github&size=35)
 
Ce guide sert à comprendre comment écrire les messages de commit de manière claire, ordonnée et sans se prendre la tête. Si tu suis ces règles, ton code sera beaucoup plus facile à comprendre pour les autres aussi.
 
## La structure de base
 
Chaque commit devrait être écrit comme ceci :
 
type(partie_du_code): ce que fait le commit
 
### Les types les plus importants à utiliser
* feat : quand tu ajoutes une nouvelle fonctionnalité (ex. une nouvelle page ou un nouveau bouton).
* fix : quand tu répares une erreur ou un bug qui ne fonctionnait pas.
* docs : quand tu changes seulement les textes, les guides ou ce fichier README.
* style : quand tu changes seulement le formatage, l'espace blanc ou le graphisme mais que le code fait la même chose.
* refactor : quand tu réécris le code pour le rendre plus propre, sans ajouter de fonctionnalités.
* chore : quand tu mets à jour les packages, les bibliothèques ou que tu configures les fichiers du projet.

## Exemples faciles
 
* feat(login): ajout du contrôle du mot de passe
* fix(api): résolution du problème de chargement des données
* docs(readme): mise à jour du guide des commits

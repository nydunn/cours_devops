BOUCKITA NGOMA Moun Giscard
BECU Gabin

# TD06 - TP CONFLITS, REBASE & CODE REVIEW

||Capture d'écran du graph Git Final||

![image](https://github.com/user-attachments/assets/da43e7bc-926e-46ff-9b3c-35aa0a360b36)
## Q1. 
git push force priorisera ton dépot local et supprimera tous les commits qui ont été fait depuis le dernier pull.
git push --force-with-lease est plus sécurisé, il vérifie d'abord qu'il n'y a pas de nouveaux commits et dans le cas où il y'en a il refuse de push pour éviter d'écraser le travail des autres developpeurs. Elle est indispensable pour éviter d'écraser le travail des collaborateurs dans le cas où il y'a non conccertation

## Q2.
rebase facilite la lisibilité de l'historique en replaçant les commits de notre branche au dessus de ceux de la branche principale sans créer un commit de fusion comme avec git merge.  

## Q3. 
L'interêt est d'eliminer les commits temporaires, faire gagner du temps au viewer, de rendre l'historique plus facile à exploiter dans une pipeline CI/CD
 

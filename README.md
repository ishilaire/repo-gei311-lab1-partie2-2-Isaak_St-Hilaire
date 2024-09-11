Pour commencer, on a regarder l'ID du commit jute avant l'erreur, on a ensuite utilisé la commande "git reset --hard <id du commit>" ce qui a permis de revenir à la bonne version du commit qui n'est pas erroné. ensuite, on a fait un "git push -f origin dev_antoine" 
ce qui a permis de forcer le push malgré le fait qu'il était en retard, puis j'ai fait un merge du main avec la branche dev_antoine, ce qui a résoud le problème.



dans le cadre du laboratoire 1, j'ai beaucoup appris sur l'utilisation de github. Ce laboratoire m'a appris comment être en mesure de travailler à plusieurs 
sur un même projet. Aussi, ce laboratoire m'a permis d'apprendre à se connecter sur le repository de quelqu'un d'autre et de pusher mes propres modifications sur ma branche.
De plus, le laboratoire m'a permis de comprendre comment revenir en arrière sur un commit quand il y'a une erreur. Au final, ce laboratoire fut une bonne révision de github,
un outil qui sera très important pour les futurs projets

Git Cheat Sheat:

git clone: permet de cloner un projet git localement
git pull : permet de puller les modifications dans le git sur le repo local
git push : permet d'envoyer les modifications effectuées sur le repo
git commit: permet d'enregistrer les modifications localement
git add: permet de "stager" les modifications pour commit par la suite
git reset --hard: permet de revenir à un ancient commit


Question 1 : 
À la fin du projet, on avait trois branches principales : celle de Nadir, de Amine et Mustafa.
On a fait des merges et des rebase pour rassembler tout le travail.

Question : 2
git fetch récupère les mises à jour du dépôt distant sans modifier ma branche,
alors que git pull les récupère et les fusionne directement dans ma branche.
Par exemple, j’utilise git fetch si je veux d’abord vérifier les changements avant de les fusionner,
et git pull si je veux mettre ma branche à jour rapidement.

Question 3 :
git reset revient en arrière en supprimant des commits de ton historique local (à éviter si tu partages ta branche).
git revert, au contraire, crée un nouveau commit qui annule les changements sans casser l’historique.
Donc sur un projet en groupe, il vaut mieux faire un revert qu’un reset.
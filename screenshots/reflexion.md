1)Structure du projet Git
   À la fin du projet, on avait trois branches principales : celle de Nadir de Mustafa et la mienne (Amine).
   On a fait des merges et des rebase pour rassembler tout le travail.

2)Différence entre git fetch et git pull
git fetch permet juste de récupérer les changements du dépôt distant sans modifier ton travail local.
git pull, lui, fait la même chose mais il fusionne directement ces changements dans ta branche.
En général, j’utilise git fetch avant un rebase pour éviter les conflits.

3)Différence entre git reset et git revert
git reset revient en arrière en supprimant des commits de ton historique local (à éviter si tu partages ta branche).
git revert, au contraire, crée un nouveau commit qui annule les changements sans casser l’historique.
Donc sur un projet en groupe, il vaut mieux faire un revert qu’un reset.

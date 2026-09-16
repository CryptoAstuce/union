# 2. Clients, light clients et consensus

Un client léger conserve les informations minimales nécessaires pour vérifier les événements ou engagements d’une chaîne distante. Il n’a pas besoin de faire confiance à chaque relayer pour accepter un message.

Le client doit suivre le consensus pertinent : hauteur, en-têtes, finalité et preuves d’inclusion. Une preuve valide dans une branche réorganisée n’est pas forcément une preuve finale.

Les chaînes supportées peuvent utiliser des modèles différents. L’adaptateur doit traduire les formats sans affaiblir la vérification.

La mise à jour du client est elle-même une opération sensible et doit suivre une gouvernance explicite.

Suite : [Messages et canaux inter-chaînes](03-messages-canaux.md).

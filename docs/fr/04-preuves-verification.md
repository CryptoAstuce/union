# 4. Preuves et vérification

Une preuve relie un message à un état accepté de la chaîne source. Le vérificateur contrôle l’en-tête, la finalité, l’inclusion et l’engagement de la donnée avant d’autoriser la suite.

La vérification doit être déterministe et indépendante du relayer qui transporte la preuve. Les erreurs doivent distinguer preuve invalide, état inconnu et données temporairement indisponibles.

Les preuves zero knowledge peuvent réduire les données transportées, mais ajoutent des paramètres cryptographiques et des hypothèses de circuit.

Une preuve correcte ne donne pas automatiquement une finalité économique si la chaîne source peut encore réorganiser son état.

Suite : [Relayer, finalité et exécution](05-relayer-finalite.md).

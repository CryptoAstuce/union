# 5. Relayer, finalité et exécution

Le relayer observe les événements, construit les messages et les soumet à la chaîne destination. Il ne doit pas être le seul dépositaire de la vérité : le contrat ou le client destination refait les vérifications importantes.

La finalité détermine quand un événement source peut être accepté. Un délai trop court expose à une réorganisation ; un délai trop long dégrade l’expérience et l’immobilisation des fonds.

L’exécution consomme le message, vérifie le nonce et applique les permissions de destination. Un échec doit préserver les garanties anti-replay et offrir un mécanisme de récupération prévu.

Les frais et les limites de gas font partie du design du canal.

Suite : [Sécurité et limites](06-securite-limites.md).

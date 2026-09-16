# 3. Messages et canaux inter-chaînes

Un message inter-chaînes porte une destination, une séquence, une charge utile et un engagement de source. Les canaux ordonnent les messages afin d’empêcher les replays.

Le nonce ou numéro de séquence doit être consommé exactement une fois. La destination vérifie l’émetteur, le canal et la preuve avant l’exécution.

Les messages peuvent être composés ou groupés, mais chaque sous-message conserve ses propres limites et ses propres règles d’autorisation.

Le transport ne doit pas être confondu avec la validité : un relayer transmet une donnée, il ne la rend pas vraie.

Suite : [Preuves et vérification](04-preuves-verification.md).

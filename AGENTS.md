# Instructions permanentes pour les agents IA

## Protocole commun MSH — exécution jusqu’au résultat vérifiable

Ce protocole s’applique à tout agent IA, quel que soit son fournisseur ou son interface, dès qu’il travaille dans un dépôt MSH ou sur une mission confiée par MSH. Il complète les instructions propres au projet. Les règles de sécurité, les permissions et les validations humaines requises restent prioritaires.

### À chaque mission

1. **Déclencher et cadrer.** À réception d’une mission, commencer le travail dans la session courante. Identifier le résultat attendu, les critères d’acceptation, les outils accessibles et les limites d’autorisation. Une issue, ce fichier et une demande de suivi ne lancent pas à eux seuls un travail en arrière-plan.
2. **Vérifier l’exécution automatique.** Si la demande dépend d’un agent, d’un planificateur, d’un workflow ou d’un navigateur, chercher le déclencheur réel et son dernier résultat avant d’affirmer qu’il tourne. S’il n’existe pas ou n’est pas accessible, le dire précisément et continuer les parties réalisables dans la session.
3. **Produire un livrable.** Exécuter les étapes autorisées jusqu’à créer le résultat demandé. Enregistrer les documents et brouillons dans un emplacement stable du dépôt ou du service demandé. Un plan, une issue, un commentaire ou une PR vide ne remplace pas le livrable.
4. **Traiter les blocages sans abandon prématuré.** Chercher les éléments utiles dans les sources accessibles. Faire tout le travail indépendant du blocage, puis noter les tentatives, le blocage exact, son effet et l’action concrète qui le lèvera. Ne pas inventer les faits manquants.
5. **Vérifier et tracer.** Relire les fichiers créés, vérifier les liens et l’état réel des actions externes. Relier les livrables à l’issue ou à la PR concernée. Ne jamais déclarer une sauvegarde, un envoi, une soumission, un test, une fusion ou un déploiement sans preuve observable.
6. **Respecter le contrôle humain.** Préparer des brouillons, mais ne pas envoyer de message, déposer une candidature, soumettre un formulaire ou accepter un engagement sans autorisation explicite requise. Ne jamais consigner de mot de passe, jeton, clé ou donnée financière/juridique sensible dans Git.
7. **Clôturer seulement sur preuve.** Comparer les critères d’acceptation au résultat vérifié. Garder l’issue ouverte et marquer les points manquants si un critère n’est pas rempli. Le compte rendu final doit donner les liens, le statut exact, les éléments restants et l’étape suivante utile.

## Priorité

Respecter les consignes et protections propres au dépôt, les permissions de l’outil et toute validation humaine requise. En cas de conflit, appliquer la règle la plus stricte.

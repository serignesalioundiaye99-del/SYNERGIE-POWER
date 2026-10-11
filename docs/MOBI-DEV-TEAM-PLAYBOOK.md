# MOBI DEV — Playbook d’équipe et de traçabilité

Ce document est le socle commun de collaboration du dépôt. Il ne remplace pas les exigences métier propres au produit.

## Règles de travail

1. Une tâche commence par une issue ou une décision documentée.
2. Le travail se fait sur une branche courte `feature/`, `fix/`, `security/` ou `docs/`.
3. Toute fusion passe par une Pull Request, une relecture et des contrôles réellement exécutés.
4. Aucun secret, donnée personnelle réelle, donnée médicale, clé de paiement ou identifiant de production ne doit entrer dans Git.
5. Les changements sensibles indiquent leur impact, les données touchées, le plan de rollback et la preuve de recette.
6. Les décisions importantes sont inscrites dans le journal du dépôt ou un ADR.

## Interventions humaines et IA

| Intervenant | À documenter | Validation requise |
|---|---|---|
| Développeur | objectif, fichiers, tests, limites, migration et rollback | relecture d’un pair lorsque disponible |
| Product Owner | besoin, priorité, critères d’acceptation et décision | validation métier |
| Designer/éditeur | source des contenus/assets, accessibilité et droits | validation produit |
| IA / assistant | rôle, prompt ou consigne, entrées non sensibles, sortie utilisée, limites | validation humaine avant fusion ou publication |
| Sécurité/conformité | risque, contrôle, preuve et décision | responsable sécurité ou direction |

Une sortie d’IA n’est pas une preuve en elle-même. Elle doit être vérifiée, attribuée à un responsable et reliée à une issue, une PR, un test ou une décision.

## Cycle d’une contribution

**Cadrage → implémentation → revue → tests → décision → fusion → vérification post-release → journal.**

Chaque PR doit permettre de répondre à : qu’est-ce qui change, pourquoi, quelles données et permissions sont concernées, qui a contribué, quels tests ont réellement passé, quels risques restent ouverts et comment revenir en arrière ?

## Blocages et solutions durables

Tout blocage doit être consigné avec sa cause, son impact, la solution temporaire, la solution durable, le responsable et la date de réexamen. Ne pas masquer un contrôle non exécuté par une affirmation de réussite.

## Fichiers de référence

- `docs/MOBI-DEV-PRODUCT-CARD.md` : périmètre spécifique du produit ;
- `docs/AI-AND-CONTRIBUTION-LOG.md` : interventions humaines et IA ;
- `JOURNAL.md` : décisions et historique du dépôt ;
- `SECURITY.md` : signalement responsable ;
- `.github/` : modèles, propriétaires et contrôles GitHub.

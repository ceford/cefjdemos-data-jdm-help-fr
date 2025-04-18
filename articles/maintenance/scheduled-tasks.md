<!-- Filename: Help5.x:Scheduled_Tasks:_ / Display title: Tâches planifiées -->

## Description

Les tâches planifiées sont utilisées pour exécuter des tâches de maintenance de site de routine en tant qu'alternative aux tâches cron du serveur. Les tâches sont définies dans des plugins du groupe de tâches. Un certain nombre de plugins de tâches sont fournis et peuvent servir d'exemples pour créer d'autres tâches spécialisées.

### Éléments Communs

Certains aspects de cette page sont abordés dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonnes de liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Pagination de liste](jdocmanual?article=help/common-elements/list-pagination).

## Comment accéder

À partir du menu Administrateur :

- Sélectionnez **Système → Panneau de gestion → Tâches planifiées**

La liste initiale des Tâches Planifiées comporte trois éléments.

## Capture d'écran

![scheduled tasks list](../../../fr/images/maintenance/scheduled-tasks-list.png)

## En-têtes de colonnes

Colonnes uniques aux tâches planifiées :

- **Type de tâche** Les tâches sont créées à partir d'une liste de types disponibles.
- **Date de dernière exécution** La date et l'heure de la dernière exécution de la tâche.
- **Date de prochaine exécution** La date et l'heure de la prochaine exécution de la tâche.
- **Tester la tâche** Un bouton pour exécuter la tâche manuellement.
- **Priorité de la tâche** La priorité peut être Basse, Normale ou Haute. Les tâches de priorité plus élevée peuvent potentiellement bloquer les tâches de priorité inférieure.

## Historique d'exécution

Sélectionnez le bouton dans la barre d'outils pour voir la liste des exécutions de tâches individuelles.

![task execution history list](../../../fr/images/maintenance/scheduled-tasks-logs.png)

## Tâches disponibles

La capture d'écran suivante montre une liste des tâches disponibles. Certaines sont des démonstrations, d'autres sont utiles.

![Scheduled Tasks Available](../../../fr/images/maintenance/scheduled-tasks-types.png)

Chaque tâche a ses propres paramètres liés à la tâche qui devraient être explicites. Par exemple, la tâche **Site Hors Ligne** n'a de sens que si la **Modifier la Tâche → Champs de Base → Règle d'Exécution** est réglée sur **Exécution Manuelle**.

*Traduit par openai.com*

<!-- Filename: Help4.x:Maintenance:_Global_Check-in / Display title: Maintenance: Déverrouillage global -->

## Description

Un enregistrement de composant, par exemple un article, peut être verrouillé par un utilisateur qui l'a ouvert pour l'éditer et n'a jamais terminé la session d'édition. Dans de tels cas, les autres utilisateurs ne peuvent pas modifier l'enregistrement. Effectuer une validation globale permet de libérer tous ces enregistrements dans les tables des extensions sélectionnées.

### Éléments communs

Certains aspects de cette page sont abordés dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonne de liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Pagination de liste](jdocmanual?article=help/common-elements/list-pagination).

## Comment y accéder

- Sélectionnez **Système → Panneau de maintenance → Validation globale** dans le menu de l'administrateur.

## Capture d'écran

![maintenance global check in](../../../fr/images/maintenance/maintenance-global-check-in.png)

## Conseils

- Les articles Joomla sont stockés dans la table `#__content` (`#__` est un espace réservé pour le préfixe de table).
- Assurez-vous que personne n'est en train de modifier des éléments avant d'effectuer une validation globale. Lors de la validation globale, *tous* les éléments sont validés, y compris ceux qui sont en cours d'édition.

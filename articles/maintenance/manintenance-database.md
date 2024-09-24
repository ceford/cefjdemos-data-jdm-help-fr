<!-- Filename: Help4.x:Information:_Database / Display title: Maintenance: Base de données -->

## Description

Cette page vérifie que la structure des tables de la base de données est à jour et tente de corriger les problèmes détectés. Lors d'une mise à jour normale de Joomla, les modifications apportées à la structure des tables de la base de données (également appelée `schéma`) sont exécutées automatiquement pour synchroniser la version de la base de données avec celle de Joomla. Si une mise à jour est effectuée manuellement ou si une partie d'une mise à jour automatique échoue, il est possible que le schéma de la base de données ne soit pas mis à jour pour correspondre à la version des fichiers du programme Joomla. Dans ce cas, la page répertorie les éventuels problèmes de base de données détectés. Il est souvent possible de corriger ces problèmes en sélectionnant le bouton *Mettre à jour la structure*.

### Éléments communs

Certains aspects de cette page sont abordés dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonne de liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Pagination de liste](jdocmanual?article=help/common-elements/list-pagination).

## Comment y accéder

- Sélectionnez **Système → Panneau de maintenance → Base de données** dans le menu de l'administrateur.

## Capture d'écran

![Maintenance de la base de données](../../../fr/images/maintenance/maintenance-database.png)

## En-têtes de colonne

- **Problèmes** Tout problème sera mentionné ici. Un Tooltip en survol offre plus d'informations.
- **Version de la base de données** Le numéro de version de la base de données.
- **Version du manifest** Le numéro de version de Joomla ou de l'extension.
- **Dossier** Si l'extension est un plug-in, le sous-répertoire du dossier *plugins* de l'installation Joomla où l'extension est située.

## Conseils

- Si des problèmes surviennent lors d'une mise à jour, utilisez cette vérification de la base de données pour voir si celle-ci a été correctement mise à jour.
- Il est fortement recommandé d'utiliser le composant de mise à jour de Joomla pour effectuer les mises à jour du site afin que les modifications de la base de données soient exécutées automatiquement.

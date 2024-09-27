<!-- Filename: Help4.x:Information:_Database  / Display title: Maintenance : Base de données -->

## Description

Cette page vérifie que la structure des tables de la base de données est à jour et essaie de résoudre tous les problèmes qui sont trouvés. Lors d'une mise à jour normale de Joomla, les modifications de la structure des tables de la base de données (également appelée `schéma`) sont exécutées automatiquement pour synchroniser la version de la base de données avec la version de Joomla. Si une mise à jour est effectuée manuellement, ou si une partie de la mise à jour automatique échoue, le schéma de la base de données pourrait ne pas être mis à jour pour correspondre à la version des fichiers du programme Joomla. Dans ce cas, la page listera tous les problèmes de la base de données découverts. Il est souvent possible de résoudre ces problèmes en sélectionnant le bouton *Mettre à jour la structure*.

### Éléments communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes des colonnes de liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Pagination de liste](jdocmanual?article=help/common-elements/list-pagination).

## Comment accéder

- Sélectionnez **Système → Panneau de Maintenance → Base de Données** dans le menu Administrateur.

## Capture d'écran

![Base de données de maintenance](../../../fr/images/maintenance/maintenance-database.png)

## En-têtes de colonne

- **Problèmes** Tout problème sera mentionné ici. Un Tooltip au survol
  offre plus d'informations.
- **Version de la base de données** Le numéro de version de la base de données.
- **Version du manifest** Le numéro de version de Joomla ou de l'extension.
- **Dossier** Si l'extension est un plug-in, le sous-répertoire du
  répertoire des plugins de l'installation de Joomla! où l'extension est localisée.

## Conseils

- Si des problèmes surviennent lors d'une mise à jour, utilisez cette vérification de la base de données pour voir si la base de données a été mise à jour correctement.
- Il est fortement recommandé d'utiliser le composant de mise à jour Joomla pour la mise à jour du site afin que les modifications de la base de données soient exécutées automatiquement.

*Traduit par openai.com*


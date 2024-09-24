<!-- Filename: Help4.x:Users:_Groups / Display title: Utilisateurs : Groupes -->

## Description

Les groupes d'utilisateurs contrôlent les actions qu'un utilisateur peut effectuer sur un site. Les actions incluent des tâches telles que la consultation d'un article, la création d'un article, la modification des options d'un composant ou la connexion. L'administrateur du site attribue des autorisations pour diverses actions à chaque groupe. Les autorisations pour les actions peuvent être attribuées à différents niveaux dans la hiérarchie des composants, par exemple dans la configuration globale, les options du composant ou les options du module. Si un groupe d'utilisateurs n'a pas l'autorisation d'effectuer une action donnée, les utilisateurs de ce groupe ne pourront pas effectuer cette action.

Le contrôle d'accès aux vues est mis en œuvre via l'utilisation des **Niveaux d'accès**, qui ont un ou plusieurs groupes d'utilisateurs qui leur sont attribués. Les éléments comme les articles, les éléments de menu ou les modules sont affectés à un niveau d'accès. Un utilisateur membre d'un groupe assigné à un niveau d'accès spécifique peut consulter tout élément associé à ce niveau d'accès.

Les groupes d'utilisateurs peuvent être organisés dans une hiérarchie où tous les sous-groupes héritent des autorisations d'actions et des niveaux d'accès du groupe parent. Si utilisé intelligemment, cette fonctionnalité peut faire gagner beaucoup de temps en évitant la duplication dans la configuration du système de sécurité du site.

La page *Utilisateurs : Groupes* répertorie les groupes d'utilisateurs actuels dans une hiérarchie. Elle peut être utilisée pour créer de nouveaux groupes d'utilisateurs et supprimer les groupes qui ne sont plus nécessaires. Ne supprimez pas les groupes d'utilisateurs par défaut !

### Éléments communs

Certains éléments de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonnes de liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Pagination de liste](jdocmanual?article=help/common-elements/list-pagination).

## Comment accéder

- Sélectionnez **Utilisateurs → Groupes** dans le menu Administrateur.

## Capture d'écran

![groupes d'utilisateurs](../../../fr/images/users/users-groups-list.png)

## Conseils

- Sélectionnez le nom d'un groupe pour modifier les propriétés de ce groupe.
- Sélectionnez l'icône de permission pour examiner les autorisations du groupe concernant l'accès à chaque élément. Cela est souvent utilisé pour résoudre les problèmes d'autorisations d'accès.
- Sélectionnez le nombre d'utilisateurs activés pour voir une liste des utilisateurs activés dans ce groupe.
- Sélectionnez le nombre d'utilisateurs bloqués pour voir une liste des utilisateurs bloqués dans ce groupe.

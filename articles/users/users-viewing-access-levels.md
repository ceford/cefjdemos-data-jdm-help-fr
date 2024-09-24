<!-- Filename: Help4.x:Users:_Viewing_Access_Levels / Display title: Utilisateurs : Modifier le niveau d'accès -->

## Description

Les niveaux d'accès contrôlent quels utilisateurs peuvent voir quels éléments sur un site. Les éléments comprennent des articles de menu, des modules, des catégories et des éléments de composant (articles, contacts, etc.). Chaque élément du site est assigné à un niveau d'accès. Des groupes d'utilisateurs sont également assignés à chaque niveau d'accès.

Si un utilisateur est membre d'un groupe qui a la permission pour un niveau d'accès, cet utilisateur peut alors voir tous les éléments assignés à ce niveau d'accès. Il est important de comprendre que les groupes d'utilisateurs peuvent être organisés dans une hiérarchie parent-enfant. Dans ce cas, un groupe enfant a accès à tous les niveaux d'accès auxquels le groupe parent a accès. Il n'est donc pas nécessaire d'assigner un niveau d'accès à un groupe enfant que son groupe parent a déjà.

### Éléments communs

Certains éléments de cette page sont traités dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).

## Comment accéder

- Sélectionnez **Utilisateurs → Niveaux d'accès** dans le menu Administrateur. Ensuite...
  - Sélectionnez un lien dans la colonne **Nom du niveau** pour éditer un niveau existant. Ou...
  - Sélectionnez le bouton Nouveau pour créer un nouveau niveau d'accès.

## Capture d'écran

![niveaux d'accès des utilisateurs](../../../fr/images/users/users-edit-viewing-access-level-details-tab.png)

### Onglet Détails du niveau

- **Titre du niveau** Entrez un titre pour ce niveau d'accès.
- **Groupes d'utilisateurs avec accès en vue** Cochez tout groupe pour avoir ce niveau d'accès.

### Onglet Groupes d'utilisateurs avec accès en vue

![niveaux d'accès des utilisateurs](../../../fr/images/users/users-edit-viewing-access-level-ugwva-tab.png)

Sélectionnez une case à cocher pour ajouter un groupe d'utilisateurs à un niveau d'accès. Dans l'exemple montré, tous les groupes sont des enfants du groupe Public, il n'est donc pas nécessaire de cocher l'un des groupes enfants. Ils héritent des permissions d'accès publiques. Cette fonctionnalité ne doit être utilisée que pour des groupes personnalisés !

## Conseils

- Si vous ajoutez un nouveau groupe, vous devrez peut-être éditer tous les niveaux d'accès auxquels ce groupe devrait avoir accès.

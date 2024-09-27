<!-- Filename: Help4.x:Permissions_for_Group  / Display title: Permissions pour le groupe -->

## Description

La page *Permissions pour le groupe* affiche un rapport des permissions montrant les permissions exactes pour un groupe d'utilisateurs donné sur l'ensemble des ressources du site. Elle est utile pour déboguer les problèmes d'accès des utilisateurs.

### Éléments communs

Certains éléments de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonne de la liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Pagination de la liste](jdocmanual?article=help/common-elements/list-pagination).

## Comment accéder

- Sélectionnez **Utilisateurs → Groupes** dans le menu Administrateur. Ensuite...
  - Sélectionnez l'icône **Permissions** pour un groupe spécifique dans la liste des groupes d'utilisateurs.

## Capture d'écran

![permissions des utilisateurs pour le groupe](../../../fr/images/users/users-permissions-for-group.png)

Au-dessus du tableau des permissions, des éléments sélectionnés montrent les permissions d'accès
à l'aide d'icônes pour *Autorisé*, *Non autorisé* et *Interdit*. La légende des icônes se trouve
sous le tableau.

- **Connexion au site** Les utilisateurs du groupe peuvent-ils se connecter au Frontend du site.
- **Connexion administrateur** Les utilisateurs du groupe peuvent-ils se connecter au Backend du site.
- **Connexion aux services web** Les utilisateurs du groupe peuvent-ils accéder à l'API des services
  Web de Joomla via un jeton d'API super-utilisateur.
- **Accès hors ligne** Les utilisateurs du groupe peuvent-ils accéder au Frontend du site lorsqu'il
  est hors ligne.
- **Super-utilisateur** Les utilisateurs du groupe peuvent-ils effectuer n'importe quelle action sur
  l'ensemble du site indépendamment des autres paramètres de permission.

### En-têtes des colonnes

Le tableau contenant les actifs du site montre la permission pour le groupe sélectionné.

- **Titre de l'actif** Le nom de l'actif en langage clair.
- **Nom de l'actif** Le nom interne de l'actif.
- **Configurer les options** Les utilisateurs du groupe peuvent-ils modifier les
  options (sauf les permissions) de cet actif.
- **Accès à l'interface d'administration** Les utilisateurs du groupe peuvent-ils accéder à 
  l'interface d'administration de l'actif.
- **Créer** Les utilisateurs du groupe peuvent-ils créer du contenu dans l'actif.
- **Supprimer** Les utilisateurs du groupe peuvent-ils supprimer du contenu dans l'actif.
- **Modifier** Les utilisateurs du groupe peuvent-ils modifier le contenu de l'actif.
- **Modifier l'état** Les utilisateurs du groupe peuvent-ils modifier l'état de l'actif.
- **Modifier sa propre création** Les utilisateurs du groupe peuvent-ils modifier tout contenu qu'ils possèdent dans l'actif.
- **Modifier la valeur d'un champ personnalisé** Les utilisateurs du groupe peuvent-ils modifier
  la valeur de n'importe quel champ personnalisé dans l'actif.
- **LFT** Les valeurs de gauche et de droite dans la hiérarchie imbriquée. Cela est utilisé
  pour l'imbrication et le classement des actifs.
- **ID** C'est un numéro d'identification unique pour cet élément, attribué
  automatiquement par Joomla. Il est utilisé pour identifier l'élément en interne,
  et ne peut pas être modifié.

*Traduit par openai.com*


<!-- Filename: Help4.x:Permissions_for_User  / Display title: Permissions for User  -->

## Description

La page *Permissions pour l'utilisateur* affiche un rapport de permissions montrant les permissions exactes pour un utilisateur donné à travers tous les actifs du site. Elle est utile pour déboguer les problèmes d'accès des utilisateurs.

### Éléments communs

Certains éléments de cette page sont abordés dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=aide/elements-communs/barres-outils).
* [Filtres de liste](jdocmanual?article=aide/elements-communs/filtres-liste).
* [En-têtes des colonnes de liste](jdocmanual?article=aide/elements-communs/en-tetes-colonnes-liste).
* [Pagination de liste](jdocmanual?article=aide/elements-communs/pagination-liste).

## Comment accéder

- Sélectionnez **Utilisateurs → Gérer** dans le menu Administrateur. Ensuite...
  - Sélectionnez le bouton **Autorisations** pour un utilisateur spécifique.

## Capture d'écran

![autorisations des utilisateurs pour l'utilisateur](../../../fr/images/users/users-permissions-for-user.png)

Au-dessus du tableau des autorisations, des éléments sélectionnés montrent les autorisations d'accès
en utilisant des icônes pour *Autorisé*, *Non autorisé* et *Interdit*. La légende des icônes est en dessous
du tableau.

- **Connexion au site** L'utilisateur peut-il se connecter au frontend du site.
- **Connexion administrateur** L'utilisateur peut-il se connecter au backend du site.
- **Connexion aux services web** L'utilisateur peut-il accéder à l'API des services web de Joomla
  via un jeton API Super Utilisateur.
- **Accès hors ligne** L'utilisateur peut-il accéder au frontend du site lorsqu'il
  est hors ligne.

### En-têtes de colonnes

Le tableau contenant les ressources du site montre les autorisations pour l'utilisateur sélectionné.

- **Titre de la ressource** Le nom de la ressource en langage clair.
- **Nom de la ressource** Le nom interne de la ressource.
- **Super Utilisateur** L'utilisateur peut-il effectuer des actions de Super Utilisateur pour la ressource
  indépendamment de tout autre paramètre d'autorisation.
- **Configurer les options** L'utilisateur peut-il modifier les options de la ressource (sauf les autorisations).
- **Accéder à l'interface d'administration** L'utilisateur peut-il accéder à l'interface d'administration
  de la ressource.
- **Créer** L'utilisateur peut-il créer du contenu dans la ressource.
- **Supprimer** L'utilisateur peut-il supprimer du contenu dans la ressource.
- **Modifier** L'utilisateur peut-il modifier du contenu dans la ressource.
- **Modifier l'état** L'utilisateur peut-il modifier l'état de la ressource.
- **Modifier propre** L'utilisateur peut-il modifier tout contenu appartenant à un utilisateur dans la ressource.
- **Modifier la valeur du champ personnalisé** L'utilisateur peut-il modifier toute
  valeur de champ personnalisé dans la ressource.
- **LFT** Les valeurs gauche et droite dans la hiérarchie de l'imbrication. Ceci est utilisé
  pour l'imbrication et le classement des ressources.
- **ID** Ceci est un numéro d'identification unique pour cet élément attribué
  automatiquement par Joomla. Il est utilisé pour identifier l'élément en interne,
  et ne peut pas être modifié.

*Traduit par openai.com*


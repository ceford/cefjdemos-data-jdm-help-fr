<!-- Filename: Help4.x:Menus / Display title: Menus -->

## Description

Les *menus* permettent à un utilisateur de naviguer sur le site. Un menu est un objet qui contient un ou plusieurs éléments de menu. Chaque élément de menu pointe vers une page logique du site. Un module de menu est nécessaire pour afficher le menu sur la page. Un menu peut avoir plusieurs modules. Par exemple, un module peut n'afficher que les éléments de menu de premier niveau, tandis qu'un second module peut afficher les éléments de menu de niveau 2.

La page *Menus* fournit un aperçu des menus disponibles sur un site Joomla. Cela inclut les détails du nombre d'éléments de menu publiés, dépubliés, mis à la corbeille pour chaque menu, ainsi que les noms des modules liés.

Le processus pour ajouter un menu au site est généralement le suivant :

1. Créer un nouveau menu (en utilisant cette page).
2. Créer un ou plusieurs nouveaux éléments de menu pour ce menu. Chaque élément de menu aura un type spécifique.
3. Créer un ou plusieurs modules de menu pour afficher le menu sur le site.
   - Sélectionner les éléments de menu (pages) qui afficheront le module.

### Éléments communs

Certains éléments de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonne](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordre des éléments de la liste](jdocmanual?article=help/common-elements/list-ordering).
* [Pagination de la liste](jdocmanual?article=help/common-elements/list-pagination).

## Comment y accéder

- Sélectionnez **Menus → Gérer** dans le menu d'administration.

## Capture d'écran

![liste des menus](../../../fr/images/menus/menus-list.png)

## En-têtes de colonne

- **Titre** Le nom du menu.
- **Éléments de menu** Un lien vers les éléments de menu pour ce menu.
- **\# Publiés** Nombre d'éléments de menu publiés dans ce menu.
- **\# Non publiés** Nombre d'éléments de menu non publiés dans ce menu.
- **\# Mis à la corbeille** Nombre d'éléments de menu mis à la corbeille dans ce menu.
- **Modules liés** Une liste déroulante montre le nom, le niveau d'accès et la position du template de tout module de menu associé au menu.

## Conseils

- Les boutons numérotés mènent à une liste filtrée des éléments de menu pour ce menu.
- Un menu doit avoir un titre descriptif court adapté à une utilisation dans des listes et des listes déroulantes.
- La *Description* est un rappel utile de l'objectif pour lequel le menu a été créé.
- Si un menu n'a pas de modules associés, le bouton dans la colonne *Modules liés* est un lien vers un dialogue modal *Ajouter un module pour ce menu*.
- Si vous supprimez un menu existant, n'oubliez pas que tous les éléments de menu associés à ce menu seront également supprimés. Un message d'avertissement s'affiche :

  **Êtes-vous sûr de vouloir supprimer ces menus ? La confirmation supprimera les types de menu sélectionnés, tous leurs éléments de menu et les modules de menu associés.**

- Le menu principal contient l'élément de menu par défaut du site. Il **ne doit pas être supprimé** ! L'élément de menu par défaut définit la page affichée lors de la visite du domaine du site, tel que `www.exemple.com`. Le site ne fonctionnera pas s'il est supprimé. Il s'agit généralement de l'élément de menu *Accueil*, mais il peut être défini sur n'importe quel élément de menu, y compris un élément de menu dans un menu caché. Si l'élément de menu par défaut est modifié, assurez-vous de ne pas supprimer cet élément de menu non plus !

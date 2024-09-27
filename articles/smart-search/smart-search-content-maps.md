<!-- Filename: Help4.x:Smart_Search:_Content_Maps  / Display title: Recherche intelligente : Cartes de Contenu -->

## Description

La page *Recherche intelligente : Cartes de contenu* affiche les cartes de contenu actuellement dans l'index de Recherche intelligente. Les cartes de contenu vous permettent de faire des références croisées de votre contenu indexé (articles, etc.) avec des informations méta connexes telles que la catégorie dans laquelle il se trouve. Chaque élément de contenu indexé par Recherche intelligente est ajouté à une ou plusieurs cartes de contenu qui peuvent être utilisées comme filtres lors de la recherche dans l'index.

Les cartes de contenu sont divisées en deux parties :

- Groupe de cartes : Ce sont des super-conteneurs pour un type d'information particulier. Par exemple, un groupe de cartes peut être *Type*, *Catégorie*, *Événement*, *Langue* ou *Auteur*.
- Carte de contenu : Les cartes de contenu sont les valeurs réelles pour les informations méta dans un groupe de cartes particulier. Les cartes de contenu sont, par exemple, les noms des catégories ou des auteurs.

Ces groupes de cartes et ces cartes de contenu constituent le panneau de recherche avancée disponible sur le front-end. Pour chaque groupe de cartes, il peut y avoir une liste déroulante et les cartes de contenu sont ajoutées en tant que valeurs à la liste respective. Les constructeurs de sites plus avancés peuvent remplacer les mises en page par défaut et utiliser des listes de sélection multiple ou des cases à cocher à la place.

Il est important de noter que les groupes de cartes et les cartes de contenu provenant de différents types de contenu sont fusionnés dans une seule liste. Un article Joomla dans une catégorie appelée *News* (Nouvelles) et un flux d'actualités ou un contact dans une catégorie portant le même nom sont cartographiés dans la même carte de contenu du même groupe de cartes. C'est un peu comme étiqueter différents types de contenu avec le même label. L'effet est que le visiteur de votre site n'a pas besoin de savoir comment votre contenu est classifié pour définir les filtres corrects pour le trouver.

L'écran des cartes de contenu affiche tous les groupes de cartes dans l'index de Recherche intelligente ainsi qu'un nombre indiquant le nombre de cartes de contenu dans ce groupe de cartes et les éléments dans une carte de contenu. Cliquer sur le nombre de groupes de cartes permet de voir la carte de contenu dans ce groupe de cartes ainsi que le nombre d'éléments de contenu qui appartiennent à cette carte de contenu. Un élément de contenu peut appartenir à plusieurs cartes de contenu dans un groupe de cartes ainsi qu'à plusieurs groupes de cartes.

### Éléments communs

Certains éléments de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonnes de liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordre des éléments de liste](jdocmanual?article=help/common-elements/list-ordering).
* [Pagination de liste](jdocmanual?article=help/common-elements/list-pagination).

### Tutoriel

* Si vous êtes nouveau sur Recherche intelligente, vous devriez lire le [guide de démarrage rapide de Recherche intelligente](https://docs.joomla.org/Smart_Search_quickstart_guide).

## Comment accéder

- Sélectionnez **Composants → Recherche intelligente → Cartes de contenu** dans le menu Administrateur.

## Capture d'écran

![recherche intelligente contenu cartes](../../../fr/images/smart-search/smart-search-content-maps.png)

## En-têtes de colonnes

- **Statut** Le statut de l'élément de contenu dans Smart Search. Changer le
  statut affecte uniquement la disponibilité de l'élément de contenu dans les résultats de recherche
  et n'affecte pas l'élément de contenu lui-même.
- **Titre** Le titre du Groupe de Cartes ou de la Carte de Contenu.
- **Cartes** Le nombre de cartes à l'intérieur du Groupe de Cartes. Sélectionner le
  nombre montrera les cartes à l'intérieur du Groupe de Cartes.
- **Contenu Publié Indexé** Le nombre d'éléments de contenu publiés
  dans le Groupe de Cartes. Sélectionner le nombre montrera les éléments de contenu publiés
  à l'intérieur du Groupe de Cartes.
- **Contenu Non Publié Indexé** Le nombre d'éléments de contenu non publiés
  dans le Groupe de Cartes. Sélectionner le nombre montrera les éléments de contenu non publiés
  à l'intérieur du Groupe de Cartes.

## Barre d'outils

- **Actions** Affiche une liste d'actions pour les éléments sélectionnés. Cochez une
  ou plusieurs cases pour activer la liste.
  - **Publier**. Rend les Groupes de Cartes ou les Cartes de Contenu sélectionnés disponibles
    aux visiteurs de votre site web.
  - **Dépublier.** Rend les Groupes de Cartes ou les Cartes de Contenu sélectionnés
    indisponibles pour les visiteurs de votre site web. Un Groupe de Cartes dépublié ne sera
    pas affiché comme une liste de sélection en front-end. Une Carte de Contenu dépubliée n'apparaîtra pas dans la liste de sélection du Groupe de Cartes dans lequel elle se trouve. Le réindexage ne change pas l'état publié des Groupes de Cartes ou des Cartes de Contenu.
- **Supprimer** Supprime les Groupes de Cartes ou les Cartes de Contenu sélectionnés. Fonctionne
  avec un ou plusieurs Groupes de Cartes ou Cartes de Contenu sélectionnés. Vous pouvez
  récupérer les Groupes de Cartes ou Cartes de Contenu supprimés en exécutant à nouveau l'indexeur de Recherche Intelligente.
- **Statistiques** Affiche quelques statistiques de base sur la Recherche Intelligente.

*Traduit par openai.com*


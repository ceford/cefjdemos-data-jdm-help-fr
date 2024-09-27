<!-- Filename: Help4.x:Menu_Item:_List_All_News_Feed_Categories  / Display title: Lister toutes les catégories du fil d'actualité -->

## Description

Le type d'élément de menu **Lister toutes les catégories dans un arbre de catégories de flux d'actualité** est utilisé pour montrer une liste de toutes les catégories de flux RSS. Les catégories sont affichées dans une liste hiérarchique. Selon les options sélectionnées pour cette disposition, un titre de catégorie peut être sélectionné pour montrer les flux d'actualité dans cette catégorie.

### Éléments Communs

Certains aspects de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Détails](jdocmanual?article=help/menu-items-common/menu-item-details).
* [L'onglet Catégorie](jdocmanual?article=help/menu-items-common/menu-item-category).
* [L'onglet Dispositions de liste](jdocmanual?article=help/menu-items-common/menu-item-list-layouts).
* [L'onglet Type de lien](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [L'onglet Affichage de la page](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [L'onglet Métadonnées](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [L'onglet Associations](jdocmanual?article=help/common-elements/edit-associations).
* [L'onglet Affectation de module](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Comment Accéder

Pour créer un nouvel élément de menu Liste de Toutes les Catégories dans un Arborescence de Catégories de Flux d'Actualités :

- Sélectionnez **Menus → \[nom du menu\]** dans le menu Administrateur
  (par exemple, **Menus → Menu Principal**). Ensuite...
  - Sélectionnez le bouton Nouveau dans la barre d'outils. Ensuite...
  - Sélectionnez le bouton Sélectionner le type d'élément de menu.
  - Dans la boîte de dialogue modale, sélectionnez l'élément Flux d'Actualités pour ouvrir une liste puis
    sélectionnez l'élément **Lister Toutes les Catégories de Flux d'Actualités**.

Pour modifier un élément de menu Liste de Toutes les Catégories de Flux d'Actualités existant :

- Sélectionnez son Titre dans la liste des Éléments de Menus.

## Capture d'écran

![Menu Item list all News Feed Categories details tab](../../../fr/images/menu-items/news-feeds-list-all-categories-details-tab.png)

## Champs de Formulaire

### Onglet Catégories

![Liste des éléments de menu de toutes les catégories de flux de nouvelles onglet catégories](../../../fr/images/menu-items/news-feeds-list-all-categories-tree-categories-tab.png)

- **Description de la Catégorie de Premier Niveau** Afficher ou masquer la description de la catégorie de premier niveau. Notez que cette description peut être remplacée pour cette mise en page en saisissant une *Description Alternative*.
- **Description Alternative** Si vous saisissez du texte dans ce champ, il remplacera la Description de la Catégorie de Premier Niveau, si elle en a une. Si l'option Description de Premier Niveau est définie sur *Afficher*, cette description apparaîtra à la place de la description normale de la catégorie.
- **Niveaux de Sous-catégories** Le nombre de niveaux de sous-catégories à afficher dans la mise en page. Sélectionnez *Tous* pour afficher tous les niveaux de la hiérarchie des sous-catégories.
- **Catégories Vides** Afficher ou masquer les catégories qui ne contiennent aucun élément de contenu ou sous-catégories.
- **Descriptions des Sous-catégories** Afficher ou masquer la description des sous-catégories.
- **\# Flux dans la Catégorie** Afficher ou masquer le nombre de flux de nouvelles dans une catégorie.

### Onglet Options d'Affichage du Flux

![Liste des éléments de menu de toutes les catégories de flux de nouvelles onglet options d'affichage du flux](../../../fr/images/menu-items/news-feeds-list-all-categories-tree-feed-display-options-tab.png)

- **Image du Flux** Afficher ou masquer l'image des flux de nouvelles.
- **Description du Flux** Afficher ou masquer les descriptions des flux de nouvelles.
- **Contenu du Flux** Afficher ou masquer le contenu des flux de nouvelles.
- **Nombre de caractères** Nombre de caractères à afficher si le Contenu du Flux des flux de nouvelles est défini pour être affiché.

## Conseils

- Les catégories peuvent être *imbriquées* en niveaux, similaires aux dossiers sur un disque dur. En théorie, il n'y a pas de limite absolue au nombre de niveaux que vous pouvez avoir. Cependant, en pratique, il est recommandé de limiter le nombre de niveaux. La mise en page Afficher Toutes les Catégories peut ne pas fonctionner correctement si le nombre de niveaux affichés est supérieur à cinq.
- Si vous configurez les titres des catégories comme étant cliquables, l'utilisateur peut naviguer vers la catégorie. S'il existe un élément de menu préexistant pour cette catégorie (par exemple, un élément de menu Liste de Catégories), les options de cet élément de menu contrôleront l'affichage de cette page. Sinon, les options définies pour l'élément de menu Afficher Toutes les Catégories actuel contrôleront l'affichage de la page.
- Vous pouvez définir l'option de lien vers une liste à deux endroits.
  - Dans *Flux d'Actualités : Options* vous pouvez définir la valeur par défaut pour toutes les catégories.
  - Dans *Catégorie : Modifier* pour une Catégorie de Flux d'Actualités, vous pouvez définir une valeur pour une catégorie spécifique. Si cette valeur est définie, elle remplace la valeur par défaut.

*Traduit par openai.com*


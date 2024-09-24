<!-- Filename: Help4.x:Menu_Item:_List_All_Categories / Display title: Menus : Liste des catégories d'une catégorie parente -->

## Description

Le type d'élément de menu *Lister toutes les catégories dans un arbre de catégories d'articles* est utilisé pour afficher les catégories dans une liste hiérarchique. En fonction des options sélectionnées pour cette mise en page, vous pouvez cliquer sur un titre de catégorie pour afficher les articles de cette catégorie.

### Éléments communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Détails](jdocmanual?article=help/menu-items-common/menu-item-details).
* [L'onglet Catégorie](jdocmanual?article=help/menu-items-common/menu-item-category).
* [L'onglet Mise en page du blog](jdocmanual?article=help/menu-items-common/menu-item-blog-layout).
* [L'onglet Mise en page des listes](jdocmanual?article=help/menu-items-common/menu-item-list-layouts).
* [L'onglet Options](jdocmanual?article=help/menu-items-common/menu-item-article-options).
* [L'onglet Intégration](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [L'onglet Type de lien](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [L'onglet Affichage de la page](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [L'onglet Métadonnées](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [L'onglet Associations](jdocmanual?article=help/common-elements/edit-associations).
* [L'onglet Attribution de module](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Comment y accéder

Sélectionnez **Menus → \[nom du menu\]** dans le menu d'administration.

Pour ajouter un élément de menu :

1.  Sélectionnez le bouton **Nouveau** dans la barre d'outils.
2.  Sélectionnez le bouton **Sélectionner** du type d'élément de menu.
3.  Sélectionnez l'élément **Articles**.
4.  Sélectionnez l'élément **Lister toutes les catégories dans un arbre de catégories d'articles**.

Pour modifier un élément de menu :

- Sélectionnez un **Titre** dans la liste.

## Capture d'écran

![Onglet Détails des articles Lister toutes les catégories](../../../fr/images/menu-items/articles-list-all-categories-details-tab.png)

## Champs du formulaire

- **Titre** Le titre qui s'affichera pour cet élément de menu.
- **Alias** Le nom interne de l'élément de menu. Normalement, vous pouvez laisser ce champ vide, et Joomla remplira automatiquement une valeur par défaut avec le titre en minuscules et des tirets à la place des espaces.

### Onglet Détails

#### Panneau de gauche

- **Type d'élément de menu** Le type d'élément de menu sélectionné lors de la création de cet élément de menu. Il peut s'agir de l'un des types d'éléments de menu par défaut ou d'un type fourni par une extension installée.
- **Sélectionnez la catégorie de niveau supérieur**
  - *Racine* Inclut toutes les catégories d'articles.
  - Sinon, sélectionnez la catégorie de niveau supérieur souhaitée. Toutes les sous-catégories de la catégorie sélectionnée s'afficheront dans l'élément de menu.
- **Lien** Le lien généré par le système pour cet élément de menu. Ce champ ne peut pas être modifié et est à titre informatif uniquement.
- **Fenêtre cible** Sélectionnez dans la liste déroulante.
- **Style du modèle** Sélectionnez dans la liste déroulante.

#### Panneau de droite

- **Menu** Indique dans quel menu le lien apparaîtra.

### Onglet Catégories

![Onglet Catégories des articles Lister toutes les catégories](../../../fr/images/menu-items/articles-list-all-categories-categories-tab.png)

- **Description de la catégorie de niveau supérieur** Affiche la description de la catégorie de niveau supérieur.
- **Description alternative** Saisissez une description pour remplacer la description de la catégorie pour cet élément de menu.
- **Niveaux de sous-catégories** Contrôlez combien de niveaux de sous-catégories seront affichés.
- **Catégories vides** Affiche les catégories ne contenant pas d'articles ou de sous-catégories.
- **Descriptions des sous-catégories** Affiche la description des sous-catégories.
- **\# Articles dans la catégorie** Affiche le nombre total d'articles dans chaque catégorie.

### Onglet Mise en page du blog

Les options de mise en page du blog contrôlent l'apparence de la navigation dans la catégorie si cela entraîne une mise en page de type blog.

Le formulaire de mise en page du blog a une disposition différente de celle des éléments communs ci-dessus, mais les champs sont similaires.

### Onglet Partagé

Les options partagées s'appliquent pour les options partagées dans les listes, les blogs et les articles en vedette, à moins qu'elles ne soient modifiées par les paramètres du menu.

![Onglet Partagé des articles Lister toutes les catégories](../../../fr/images/menu-items/articles-list-all-categories-shared-tab.png)

- **Pagination** La pagination fournit des liens en bas de la page qui permettent à l'utilisateur de naviguer vers des pages supplémentaires. Cela est nécessaire si les articles ne tiennent pas sur une seule page.
  - *Masquer* Les liens de pagination ne sont pas affichés. *Note* Les utilisateurs ne pourront pas naviguer vers des pages supplémentaires.
  - *Afficher* Les liens de pagination sont affichés si nécessaire.
  - *Auto* Les liens de pagination sont affichés si nécessaire.
- **Résumé de la pagination** Affiche le numéro de la page actuelle et le nombre total de pages (par exemple, *Page 1 sur 2*) en bas de chaque page.

## Conseils

- Les catégories peuvent être *imbriquées* sur plusieurs niveaux, comme des dossiers sur un disque dur. En théorie, il n'y a pas de limite absolue au nombre de niveaux que vous pouvez avoir. Cependant, en pratique, il est recommandé de limiter les niveaux au minimum. La mise en page Lister toutes les catégories peut ne pas fonctionner correctement si le nombre de niveaux affichés est supérieur à 5.
- Si vous configurez les titres des catégories comme étant cliquables, l'utilisateur peut naviguer dans la catégorie. Lorsqu'il le fait, il verra normalement soit un élément de menu de type Liste de catégories, soit un élément de menu de type Blog de catégorie, selon l'option sélectionnée. S'il existe un élément de menu préexistant pour cette catégorie (par exemple, un élément de menu Blog de catégorie), alors cet élément de menu s'affichera lors de la navigation et les options définies pour cet élément de menu contrôleront l'affichage de la page. Sinon, les options définies pour l'élément de menu Lister toutes les catégories actuel contrôleront l'affichage de la page.
- Vous pouvez définir l'option de navigation vers une liste ou un blog à 2 endroits.
  - Dans *Articles : Options*, vous pouvez définir la valeur par défaut pour toutes les catégories.
  - Dans *Catégorie : Modifier*, vous pouvez définir une valeur pour une catégorie spécifique. Si cela est défini, cela remplace la valeur par défaut.
- Pour personnaliser un *Format de date*, vous pouvez utiliser `D M Y` pour jour mois année ou `d-m-y` pour une version courte, par exemple 17-08-05. Si vous laissez vide, la clé de traduction DATE_FORMAT_LC1 de votre fichier de langue sera utilisée.
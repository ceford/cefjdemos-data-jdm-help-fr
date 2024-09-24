<!-- Filename: Help4.x:Menu_Item:_Article_Archived / Display title: Articles archivés -->

## Description

Le type d'élément de menu *Articles archivés* affiche une liste personnalisée d'articles classés par date ou par titre.

Les articles archivés ne sont plus publiés mais restent stockés sur le site. Les articles sont archivés via l'écran de liste des articles.

### Éléments communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Détails](jdocmanual?article=help/menu-items-common/menu-item-details).
* [L'onglet Options](jdocmanual?article=help/menu-items-common/menu-item-article-options).
* [L'onglet Type de lien](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [L'onglet Affichage de la page](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [L'onglet Métadonnées](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [L'onglet Associations](jdocmanual?article=help/common-elements/edit-associations).
* [L'onglet Attribution de module](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Comment y accéder

Sélectionnez **Menus → \[nom du menu\]** dans le menu de l'administrateur.

Pour ajouter un élément de menu :

1.  Sélectionnez le bouton **Nouveau** dans la barre d'outils.
2.  Sélectionnez le bouton **Sélectionner** du type d'élément de menu.
3.  Sélectionnez l'élément **Articles** dans la boîte de dialogue contextuelle.
4.  Sélectionnez l'élément **Articles archivés**.

Pour modifier un élément de menu :

- Sélectionnez un **Titre** dans la liste.

## Capture d'écran

![Alias de l'élément de menu](../../../fr/images/menu-items/articles-archived-articles-details-tab.png)

## Champs du formulaire

- **Titre** Le titre qui s'affichera pour cet élément de menu.
- **Alias** Le nom interne de l'élément de menu. En général, vous pouvez laisser ce champ vide et Joomla remplira une valeur par défaut avec le Titre en minuscules et des tirets à la place des espaces.

### Onglet Archive

![Articles archivés dans les menus](../../../fr/images/menu-items/articles-archived-articles-archive-tab.png)

* **Ordre des articles**
  * **Les plus anciens en premier** Les articles sont affichés en commençant par les plus anciens et en terminant par les plus récents.
  * **Les plus récents en premier** Les articles sont affichés en commençant par les plus récents et en terminant par les plus anciens.
  * **Titre alphabétique** Les articles sont affichés par titre dans l'ordre alphabétique (de A à Z).
  * **Titre alphabétique inverse** Les articles sont affichés par titre dans l'ordre alphabétique inverse (de Z à A).
  * **Auteur alphabétique** Les articles sont affichés par auteur dans l'ordre alphabétique (de A à Z).
  * **Auteur alphabétique inverse** Les articles sont affichés par auteur dans l'ordre alphabétique inverse (de Z à A).
  * **Le plus de vues** Les articles sont affichés selon le nombre de vues, en commençant par celui qui a le plus de vues et en terminant par celui qui en a le moins.
  * **Le moins de vues** Les articles sont affichés selon le nombre de vues, en commençant par celui qui en a le moins et en terminant par celui qui en a le plus.
  * **Ordonnancement** Les articles sont classés selon la colonne d'ordonnancement définie dans les articles.
* **Date pour l'ordonnancement** La date utilisée lorsque les articles sont triés par date.
  * **Créé** Utilise la date de création de l'article.
  * **Modifié** Utilise la date de modification de l'article.
  * **Publié** Utilise la date de début de publication de l'article.
* **# d'articles à afficher** Nombre d'articles affichés dans la liste.
* **Champ de filtre** Affiche un champ texte dans le Frontend où l'utilisateur peut filtrer les articles.
* **Limite de texte d'introduction** Nombre maximal de caractères du texte d'introduction à afficher. Si le texte d'introduction dépasse cette valeur, il sera tronqué.

## Conseils

- La disposition des Articles archivés vous permet d'accéder à des articles anciens ou obsolètes que vous ne souhaitez pas supprimer entièrement du site.
- Si vous souhaitez afficher de vieux articles dans un blog ou une liste de catégories, créez une catégorie pour les anciens articles et déplacez-les dans cette catégorie (au lieu de changer leur statut de publication en Archivé).

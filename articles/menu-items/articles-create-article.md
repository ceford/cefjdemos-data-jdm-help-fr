<!-- Filename: Help4.x:Menu_Item:_Create_Article / Display title: Créer un article -->

## Description

L'élément de menu *Créer un article* permet aux utilisateurs de soumettre un article via l'interface du site. En général, cela n'est disponible qu'aux utilisateurs connectés sur le Frontend du site. Les utilisateurs doivent avoir la permission de créer des articles.

### Éléments communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Détails](jdocmanual?article=help/menu-items-common/menu-item-details).
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
3.  Sélectionnez l'élément **Articles** dans la boîte de dialogue popup.
4.  Sélectionnez l'élément **Créer un article**.

Pour modifier un élément de menu :

- Sélectionnez un **Titre** dans la liste.

## Capture d'écran

![Onglet Détails Créer un article](../../../fr/images/menu-items/articles-create-article-details-tab.png)

## Champs du formulaire

- **Titre** Le titre qui s'affichera pour cet élément de menu.
- **Alias** Le nom interne de l'élément de menu. En général, vous pouvez laisser ce champ vide et Joomla remplira une valeur par défaut avec le Titre en minuscules et des tirets à la place des espaces.

### Détails

#### Panneau de gauche

- **Type d'élément de menu** Le type d'élément de menu sélectionné lors de la création de cet élément de menu. Cela peut être l'un des types d'éléments de menu de base ou un type fourni par une extension installée.
- **Lien** Le lien généré automatiquement pour cet élément de menu. Ce champ ne peut pas être modifié et est fourni à titre d'information uniquement.
- **Fenêtre cible** Sélectionnez dans la liste déroulante.
- **Style de modèle** Sélectionnez dans la liste déroulante.

#### Panneau de droite

- **Menu** Indique dans quel menu le lien apparaîtra.

### Options

![Onglet Options Créer un article](../../../fr/images/menu-items/articles-create-article-options-tab.png)

- **Catégorie spécifique**
  - *Oui* Les articles seront attribués à la catégorie spécifiée. L'utilisateur ne pourra pas sélectionner une catégorie.
  - *Non* L'utilisateur pourra sélectionner la catégorie dans la liste déroulante. Seules les catégories pour lesquelles l'utilisateur a la permission *Créer* seront affichées.
- **Redirection après soumission/annulation** Sélectionnez la page vers laquelle l'utilisateur sera redirigé après une soumission d'article réussie.
- **Redirection personnalisée en cas d'annulation**
  - *Oui* Définissez une page vers laquelle rediriger lorsque l'utilisateur annule la soumission d'article.
  - *Non* Lorsque l'utilisateur annule la soumission d'article, il est redirigé vers la page de *Redirection après soumission/annulation*.

## Exemple de capture d'écran Frontend

Cette capture d'écran montre le modèle Frontend par défaut de Joomla **Cassiopeia** avec toutes les options de mise en page d'édition définies sur 'Cacher'.

[articles-create-article-frontend.png](../../../en/images/menu-items/articles-create-article-frontend.png)

## Conseils

Un utilisateur non autorisé recevra normalement une erreur lors de la sélection d'un élément de menu *Créer un article*. Pour cette raison, il est courant de donner à l'élément de menu un niveau d'accès de visualisation visible uniquement par les utilisateurs autorisés à ajouter des articles.


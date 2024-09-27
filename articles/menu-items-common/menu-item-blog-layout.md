<!-- Filename: Help6.x:Menu_Item_Blog_Layout  / Display title: Élément de Menu Disposition du Blog  -->

## Description

Tous les éléments du menu ont une disposition similaire, mais certains des champs de formulaire et certains des onglets changent d'un type à l'autre. Cette page décrit l'onglet **Disposition du Blog** utilisé pour les dispositions des Articles.

## Comment accéder

* Sélectionnez n'importe quel **Menu du site** dans le menu de l'administrateur.
* Sélectionnez le bouton **Nouveau** dans la barre d'outils.
* Sélectionnez tout type d'élément de menu de composant qui comporte un onglet *Disposition du blog*.
* Sélectionnez l'onglet **Disposition du blog**.

## Capture d'écran

![Onglet disposition du blog de l'élément de menu](../../../fr/images/menu-items-common/articles-category-blog-blog-layout-tab.png)

## Champs de formulaire

### Onglet Mise en page du blog

- **\# Articles principaux** Nombre d'articles à afficher en utilisant toute la largeur de la zone d'affichage principale. `0` signifie qu'aucun article ne sera affiché en utilisant toute la largeur. Si un article comporte une *Lire la suite...*, seule la partie du texte avant cette coupure (le texte d'introduction) sera affichée.
- **Classe des articles principaux** Vous pouvez ajouter toute classe CSS pour vos propres idées de style. Ajoutez une bordure en haut avec la classe boxed. Pour la position de l'image, utilisez par exemple image-start, image-end. Ajoutez image-alternate pour un ordre alterné des images d'introduction.
- **\# Articles d'introduction** Détermine le nombre d'articles à afficher après l'article principal. Ces articles seront affichés dans le nombre de colonnes défini dans le paramètre Colonnes ci-dessous. Si un article comporte une *Lire la suite...*, seul le texte avant cette coupure (texte d'introduction) sera affiché, suivi d'un lien *Lire la suite...*. L'ordre dans lequel les articles sont affichés est déterminé par les paramètres Ordre des catégories et Ordre des articles ci-dessous.
- **Classe des articles** Vous pouvez ajouter toute classe CSS pour vos propres idées de style. Ajoutez une bordure en haut avec la classe boxed. Pour la position de l'image, utilisez par exemple image-start, image-end. Ajoutez image-alternate pour un ordre alterné des images d'introduction.
- **\# Colonnes** Le nombre de colonnes à utiliser dans la zone des articles d'introduction. Ce nombre est généralement compris entre 1 et 3 (en fonction du modèle que vous utilisez). Si 1 est utilisé, les articles d'introduction seront affichés en utilisant toute la largeur de la zone d'affichage, tout comme les articles principaux.
- **Direction multi-colonnes** Dans les mises en page de blog multi-colonnes, détermine si les articles doivent être ordonnés de haut en bas ou de gauche à droite.
  - *De haut en bas* Ordonner les articles en descendant la première colonne, puis en passant à la colonne suivante.
  - *De gauche à droite* Ordonner les articles en traversant les colonnes, puis en revenant à la première colonne.
- **\# Liens** Le nombre de liens à afficher dans la zone des liens de la page. Ces liens permettent à un utilisateur de se lier à des articles supplémentaires, s'il y a plus d'articles que ce qui peut tenir sur la première page de la mise en page du blog.
- **Articles en vedette**
  - *Afficher* Affiche les articles en vedette et les articles non en vedette.
  - *Masquer* Affiche uniquement les articles non en vedette.
  - *Uniquement* Affiche uniquement les articles en vedette.
- **Image d'introduction liée** Si Oui, un clic sur l'image d'introduction affiche l'article.
- **Inclure les sous-catégories**
  - *Aucune* Seuls les articles de la catégorie actuelle seront affichés.
  - *Toutes* Tous les articles de la catégorie actuelle et de toutes les sous-catégories seront affichés.
  - *1-5* Tous les articles de la catégorie actuelle et des sous-catégories jusqu'à ce niveau inclus seront affichés.
- **Ordre des catégories**
  - *Aucun ordre* Les articles sont ordonnés uniquement par l'ordre des articles, sans tenir compte de la catégorie.
  - *Titre alphabétique* Les catégories sont affichées par ordre alphabétique (de A à Z).
  - *Titre alphabétique inversé* Les catégories sont affichées par ordre alphabétique inversé (de Z à A).
  - *Ordre des catégories* Les catégories sont ordonnées selon la colonne Ordre entrée dans *Articles : Catégories*.
- **Ordre des articles**
  - *Ordre des articles en vedette* Les articles sont ordonnés selon la colonne Ordre entrée dans *Articles : En vedette*.
  - *Les plus récents en premier* Les articles sont affichés en commençant par les plus récents et en terminant par les plus anciens.
  - *Les plus anciens en premier* Les articles sont affichés en commençant par les plus anciens et en terminant par les plus récents.
  - *Titre alphabétique* Les articles sont affichés par titre en ordre alphabétique (de A à Z).
  - *Titre alphabétique inversé* Les articles sont affichés par titre en ordre alphabétique inversé (de Z à A).
  - *Auteur alphabétique* Les articles sont affichés par auteur en ordre alphabétique (de A à Z).
  - *Auteur alphabétique inversé* Les articles sont affichés par auteur en ordre alphabétique inversé (de Z à A).
  - *Le plus de vues* Les articles sont affichés par le nombre de vues, en commençant par celui qui a le plus de vues et en terminant par celui qui en a le moins.
  - *Le moins de vues* Les articles sont affichés par le nombre de vues, en commençant par celui qui en a le moins et en terminant par celui qui en a le plus.
  - *Ordre aléatoire* Les articles sont affichés dans un ordre aléatoire.
  - *Ordre des articles* Les articles sont ordonnés selon la colonne Ordre entrée dans Articles.
  - *Ordre des articles inversé* Les articles sont ordonnés inversement à la colonne Ordre entrée dans Articles.
- **Date de tri** La date utilisée lorsque les articles sont triés par date.
  - *Créée* Utilisez la date de création de l'article.
  - *Modifiée* Utilisez la date de modification de l'article.
  - *Publiée* Utilisez la date de début de publication de l'article.
  - *Non publiée* Utilisez la date de non-publication de l'article.
- **Pagination** La pagination fournit des liens vers des pages au bas de la page qui permettent à l'utilisateur de naviguer vers des pages supplémentaires. Ceux-ci sont nécessaires si les articles ne tiennent pas sur une seule page.
  - *Masquer* Les liens de pagination ne sont pas affichés. *Note* Les utilisateurs ne pourront pas naviguer vers des pages supplémentaires.
  - *Afficher* Les liens de pagination sont affichés si nécessaire.
  - *Auto* Les liens de pagination sont affichés si nécessaire.
- **Résumé de pagination** Affiche le numéro de page actuel et le nombre total de pages (par exemple, *Page 1 sur 2* en bas de chaque page.


<!-- Filename: Help4.x:Articles:_Options / Display title: Articles : Paramètres -->

## Description

La page *Articles : Options* est utilisée pour définir les valeurs par défaut globales pour les articles. Elles sont appliquées lorsque l'option *Utiliser global* est sélectionnée pour une option dans un élément de menu Articles. Par exemple, pour afficher la *Date de création* d'un article dans vos éléments de menu Articles, définissez cette option sur *Afficher* ici, et elle deviendra la valeur par défaut.

### Éléments communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Onglet Permissions](jdocmanual?article=help/common-elements/edit-permissions).

## Comment y accéder

Sélectionnez le bouton **Options** dans la barre d'outils de n'importe quelle page de liste *Articles*.

## Capture d'écran

![Capture d'écran des options d'articles](../../../fr/images/articles/articles-options-articles-tab.png)

## Champs de formulaire

### Onglet Articles

Ces paramètres s'appliquent pour les mises en page d'articles sauf s'ils sont modifiés pour un élément de menu ou un article spécifique.

- **Choisir une mise en page** Sélectionnez la valeur par défaut pour les éléments de menu d'article unique.
- **Titre** Afficher le titre de l'article.
- **Titres liés** Afficher le titre comme lien vers l'article.
- **Texte d'introduction**
  - **Afficher** Le texte d'introduction de l'article sera affiché dans l'article complet.
  - **Masquer** Seule la partie de l'article après la rupture Lire la suite sera affichée dans l'article complet.
- **Position des informations de l'article**
  - **Au-dessus** Place le bloc d'informations de l'article au-dessus du texte.
  - *En dessous* Place le bloc d'informations de l'article en dessous du texte.
  - *Divisé* Divise le bloc d'informations de l'article en deux blocs séparés. Un bloc est au-dessus et l'autre en dessous du texte.
- **Titre des informations de l'article** Affiche le mot *Détails* au-dessus du bloc d'informations de l'article.
- **Catégorie** Afficher le titre de la catégorie de l'article.
  - **Lien vers la catégorie** Afficher le titre sous forme de lien vers cette catégorie. Remarque : Cela peut être défini soit sur une mise en page de blog, soit sur une mise en page de liste avec l'option *Choisir une mise en page* dans l'onglet Catégorie.
- **Catégorie parente** Afficher le titre de la catégorie parente de l'article.
  - **Lien vers la catégorie parente** Afficher le titre sous forme de lien vers cette catégorie. Remarque : Cela peut être défini soit sur une mise en page de blog, soit sur une mise en page de liste avec l'option *Choisir une mise en page* dans l'onglet Catégorie.
- **Associations** Afficher les drapeaux associés ou le code de langue. Multilingue uniquement.
  - **Utiliser les drapeaux d'image** Afficher le choix de langue sous forme de drapeaux si l'option Associations est définie sur *Afficher*.
- **Auteur** Afficher l'auteur de l'article.
  - **Lien vers la page de contact de l'auteur** Afficher comme un lien vers une mise en page de contact pour cet auteur. Remarque : l'auteur doit être configuré en tant que contact. De plus, un lien ne s'affichera pas s'il existe une valeur d'alias de l'auteur pour le contact.
- **Date de création** Afficher la date de création de l'article.
- **Date de modification** Afficher la date de modification de l'article.
- **Date de publication** Afficher la date de début de publication de l'article.
- **Navigation** Afficher un lien de navigation *Précédent* ou *Suivant*.
- **Lien "Lire la suite"** Afficher le lien Lire la suite pour lier la partie de l'article avant la coupure Lire la suite au reste de l'article.
- **Lire la suite avec titre**
  - *Afficher* Le titre de l'article fait partie du lien Lire la suite. Le lien sera au format "Lire la suite : \[titre de l'article\]".
  - *Masquer* Le lien sera "Lire la suite".
- **Limite du lien "Lire la suite" (caractères)** Le nombre maximum de caractères du titre à inclure. Remarque : Cela peut empêcher le texte Lire la suite de devenir excessivement long si l'article a un titre très long.
- **Tags** Afficher les tags pour chaque article.
- **Enregistrer les consultations** Enregistrer le nombre de fois que l'article a été consulté.
- **Consultations** Afficher le nombre de fois que l'article a été affiché par un utilisateur.
- **Liens non autorisés**
  - *Oui* Le texte d'introduction des articles restreints s'affichera. Cliquer sur le lien Lire la suite obligera les utilisateurs à se connecter pour voir le contenu complet de l'article.
  - *Non* Les articles que l'utilisateur n'est pas autorisé à consulter (en fonction du niveau d'accès de visualisation pour l'article) ne s'afficheront pas.
- **Position des liens**
  - *Au-dessus* Les liens sont affichés au-dessus du contenu.
  - *En dessous* Les liens sont affichés en dessous du contenu.

### Onglet Mise en page de l'édition

Ces options contrôlent la mise en page de la page d'édition des articles.

![Capture d'écran des options de mise en page de l'édition des articles](../../../fr/images/articles/articles-options-editing-layout-tab.png)

- **Autoriser Captcha lors de la soumission** Sélectionnez le plugin captcha qui sera utilisé dans le formulaire de soumission d'article. Si *Utiliser global* est sélectionné, assurez-vous qu'un plugin captcha est sélectionné dans la configuration globale.
- **Options de publication** Masquer l'onglet Options de publication dans l'interface d'administration lors de l'édition des articles. Cela signifie que les utilisateurs de l'interface d'administration ne pourront pas modifier les champs de cet onglet. Ces champs seront toujours définis sur leurs valeurs par défaut.
- **Options de l'article** Masquer l'onglet Options de l'article dans l'interface d'administration lors de l'édition des articles. Cela signifie que les utilisateurs de l'interface d'administration ne pourront pas modifier les champs de cet onglet. Ces champs seront toujours définis sur leurs valeurs par défaut.
- **Options de l'écran d'édition** Masquer l'onglet Configurer l'écran d'édition lors de l'édition des articles.
- **Permissions de l'article** Masquer l'onglet Permissions lors de l'édition des articles.
- **Associations multilingues** Masquer l'onglet Associations lors de l'édition des articles.
- **Activer les versions** Enregistrer l'historique des versions pour les articles et les catégories.
- **Nombre maximum de versions** Le nombre maximum de versions à conserver pour un article ou une catégorie. Si un article ou une catégorie est enregistré et que le nombre maximum de versions a été atteint, la version la plus ancienne sera automatiquement supprimée. Si cette option est définie sur "0", les versions ne seront jamais supprimées automatiquement.
- **Images et liens de l'interface utilisateur** Masquer l'onglet Images et liens dans l'éditeur d'articles de l'interface utilisateur.
- **Images et liens de l'administrateur** Masquer l'onglet Images et liens dans l'interface d'administration lors de l'édition des articles.
- **Fenêtre cible du lien A** Définit la valeur par défaut pour la cible du premier lien dans l'article. Les choix sont :
  - *Ouvrir dans la fenêtre parent* Ouvre dans la fenêtre principale du navigateur, remplaçant l'article Joomla actuel.
  - *Ouvrir dans une nouvelle fenêtre* Ouvre le lien dans une nouvelle fenêtre du navigateur.
  - *Ouvrir dans une fenêtre pop-up* Ouvre le lien dans une fenêtre pop-up du navigateur (sans les contrôles de navigation complets).
  - *Modal* Ouvre le lien dans une fenêtre pop-up modale.
- **Fenêtre cible du lien B** Définit la valeur par défaut pour la cible du deuxième lien dans l'article. Les mêmes options que pour l'URL A.
- **Fenêtre cible du lien C** Définit la valeur par défaut pour la cible du troisième lien dans l'article. Les mêmes options que pour l'URL A.
- **Classe de l'image d'introduction** Définit l'attribut de classe pour une image d'introduction sélectionnée dans le champ Image d'introduction.
- **Classe de l'image du texte complet** Définit l'attribut de classe pour une image complète de l'article sélectionnée dans le champ Image complète de l'article.

### Onglet Catégorie

Ces paramètres s'appliquent aux options de catégories d'articles, sauf s'ils sont modifiés par les paramètres individuels de la catégorie ou du menu.

![Options des catégories d'articles](../../../fr/images/articles/articles-options-category-tab.png)

- **Choisir une mise en page** Sélectionnez la mise en page par défaut à afficher lorsqu'un lien de catégorie est sélectionné.
- **Titre de la catégorie** Afficher le titre de la catégorie.
- **Description de la catégorie** Afficher la description de la catégorie.
- **Image de la catégorie** Afficher l'image de la catégorie.
- **Niveaux de sous-catégories** Contrôlez combien de niveaux de sous-catégories afficher.
- **Catégories vides** Afficher les catégories qui ne contiennent aucun article ni sous-catégorie.
- **Message "Pas d'articles"** Afficher un message "Il n'y a pas d'articles dans cette catégorie".
- **Titre des sous-catégories** Afficher les sous-catégories en tant que sous-titre sur la page.
- **Descriptions des sous-catégories** Afficher les descriptions des sous-catégories.
- **\# Articles dans la catégorie** Afficher le nombre total d'articles dans chaque catégorie.
- **Tags** Afficher les tags pour la catégorie.

### Onglet Catégories

Ces paramètres s'appliquent aux options des catégories d'articles, sauf s'ils sont modifiés par les paramètres individuels de la catégorie ou du menu.

![Options des catégories d'articles](../../../fr/images/articles/articles-options-categories-tab.png)

- **Description de la catégorie de niveau supérieur** Afficher la description de la catégorie de niveau supérieur.
- **Niveaux de sous-catégories** Contrôlez combien de niveaux de sous-catégories afficher.
- **Catégories vides** Afficher les catégories qui ne contiennent aucun article ni sous-catégorie.
- **Descriptions des sous-catégories** Afficher la description des sous-catégories.
- **\# Articles dans la catégorie** Afficher le nombre total d'articles dans chaque catégorie.

### Onglet Mises en page Blog/En vedette

Ces paramètres s'appliquent aux mises en page blog ou en vedette, sauf s'ils sont modifiés pour un élément de menu spécifique.

![Options des mises en page blog et en vedette](../../../fr/images/articles/articles-options-blog-layouts-tab.png)

- **# Articles principaux** Nombre d'articles à afficher en utilisant toute la largeur de la zone d'affichage principale. "0" signifie qu'aucun article ne sera affiché en utilisant toute la largeur. Si un article contient une coupure "Lire la suite...", seule la partie avant cette coupure (le texte d'introduction) sera affichée.
- **Classe des articles principaux** Ajouter une classe CSS pour personnaliser la mise en page. Ajouter une bordure supérieure avec la classe *boxed*. Pour la position de l'image, utilisez par exemple *image-left*, *image-right*. Ajoutez *image-alternate* pour un ordre alterné des images d'introduction.
- **# Articles d'introduction** Détermine le nombre d'articles à afficher après l'article principal. Ces articles s'afficheront dans le nombre de colonnes défini dans le paramètre Colonnes ci-dessous. Si un article a une coupure "Lire la suite...", seul le texte avant la coupure (texte d'introduction) s'affichera, suivi d'un lien "Lire la suite...". L'ordre d'affichage des articles est déterminé par les paramètres Ordre des catégories et Ordre des articles ci-dessous.
- **Classe d'article** Ajouter une classe CSS pour un style personnalisé. Ajouter une bordure supérieure avec la classe *boxed*. Pour la position de l'image, utilisez par exemple *image-left*, *image-right*. Ajoutez *image-alternate* pour un ordre alterné des images d'introduction.
- **# Colonnes** Le nombre de colonnes à utiliser dans la zone des articles d'introduction. Cela varie généralement entre 1 et 3 (selon le modèle utilisé). Si 1 est utilisé, les articles d'introduction s'afficheront en utilisant toute la largeur de la zone d'affichage, comme les articles principaux.
- **Direction multi-colonnes** Dans les mises en page blog à plusieurs colonnes, choisissez l'ordre d'affichage des articles, soit de haut en bas des colonnes, soit de gauche à droite.
  - *De haut en bas* Les articles sont ordonnés de haut en bas dans la première colonne, puis dans la colonne suivante.
  - *De gauche à droite* Les articles sont ordonnés de gauche à droite dans les colonnes, puis reviennent à la première colonne.
- **# Liens** Le nombre de liens à afficher dans la zone des liens de la page. Ces liens permettent à un utilisateur d'accéder à des articles supplémentaires, si plus d'articles existent que ce qui peut tenir sur la première page de la mise en page Blog.
- **Inclure les sous-catégories**
  - *Aucune* Seuls les articles de la catégorie actuelle seront affichés.
  - *Toutes* Tous les articles de la catégorie actuelle et de toutes les sous-catégories seront affichés.
  - *1-5* Tous les articles de la catégorie actuelle et des sous-catégories jusqu'à ce niveau seront affichés.
- **Image d'introduction liée** Si Oui, un clic sur l'image d'introduction affiche l'article.

### Onglet Mises en page Liste

Ces paramètres s'appliquent aux options des mises en page liste, sauf s'ils sont modifiés pour un élément de menu ou une catégorie spécifique.

![Options des mises en page liste](../../../fr/images/articles/articles-options-list-layouts-tab.png)

- **Sélecteur d'affichage** Afficher le contrôle Sélectionner \# qui permet à l'utilisateur de choisir le nombre d'articles à afficher.
- **Champ de filtre** Afficher un champ de texte dans le Frontend où un utilisateur peut filtrer les articles. Options dans le menu d'édition du Backend.
  - *Masquer* Ne pas afficher de champ de filtre.
  - *Titre* Filtrer par titre d'article.
  - *Auteur* Filtrer par nom de l'auteur.
  - *Consultations* Filtrer par nombre de consultations de l'article.
  - *Tags* Filtrer par tags de l'article.
  - *Mois (publié)* Filtrer par mois de publication des articles.
- **En-têtes de tableau** Afficher un en-tête dans la liste d'articles dans le Frontend.
- **Date** Afficher une date dans la liste.
  - *Masquer* Ne pas afficher de date.
  - *Créée* Afficher la date de création.
  - *Modifiée* Afficher la date de la dernière modification.
  - *Publiée* Afficher la date de début de publication.
- **Consultations** Afficher le nombre de consultations des articles.
- **Auteur** Afficher le nom de l'auteur.
- **\# Articles à lister** Nombre d'articles affichés dans la liste.

### Onglet Partagé

Ces paramètres s'appliquent aux options partagées dans les mises en page Liste, Blog et En vedette, sauf s'ils sont modifiés par les paramètres du menu.

![Options partagées des articles](../../../fr/images/articles/articles-options-shared-tab.png)

- **Ordre des catégories**
  - *Pas d'ordre* Les articles sont triés uniquement par l'Ordre des articles, sans tenir compte de la catégorie.
  - *Titre alphabétique* Les catégories sont affichées par ordre alphabétique (A à Z).
  - *Titre alphabétique inverse* Les catégories sont affichées par ordre alphabétique inverse (Z à A).
  - *Ordre des catégories* Les catégories sont ordonnées selon la colonne d'ordre entrée dans Articles : Catégories.
- **Ordre des articles**
  - *Les plus récents d'abord* Les articles sont affichés en commençant par les plus récents.
  - *Les plus anciens d'abord* Les articles sont affichés en commençant par les plus anciens.
  - *Titre alphabétique* Les articles sont affichés par titre, dans l'ordre alphabétique (A à Z).
  - *Titre alphabétique inverse* Les articles sont affichés par titre, dans l'ordre alphabétique inverse (Z à A).
  - *Auteur alphabétique* Les articles sont affichés par auteur, dans l'ordre alphabétique (A à Z).
  - *Auteur alphabétique inverse* Les articles sont affichés par auteur, dans l'ordre alphabétique inverse (Z à A).
  - *Le plus de consultations* Les articles sont affichés par nombre de consultations, en commençant par celui qui en a le plus.
  - *Le moins de consultations* Les articles sont affichés par nombre de consultations, en commençant par celui qui en a le moins.
  - *Ordre* Les articles sont ordonnés selon la colonne d'ordre entrée dans Articles.
  - *Ordre inverse* Les articles sont ordonnés dans l'ordre inverse de celui défini dans la colonne d'ordre des articles.
- **Date pour l'ordre** La date utilisée lorsque les articles sont triés par date.
  - *Créée* Utiliser la date de création de l'article.
  - *Modifiée* Utiliser la date de modification de l'article.
  - *Publiée* Utiliser la date de début de publication de l'article.
- **Pagination** La pagination fournit des liens de pages en bas de page permettant à l'utilisateur de naviguer vers des pages supplémentaires. Cela est nécessaire si les articles ne tiennent pas sur une seule page.
  - *Masquer* Les liens de pagination ne sont pas affichés. Remarque : Les utilisateurs ne pourront pas naviguer vers des pages supplémentaires.
  - *Afficher* Les liens de pagination sont affichés si nécessaire.
  - *Auto* Les liens de pagination sont affichés si nécessaire.
- **Résumé de la pagination** Afficher le numéro de page actuel et le nombre total de pages (par exemple, "Page 1 sur 2") en bas de chaque page.
- **Articles en vedette**
  - *Afficher* Afficher les articles en vedette et non en vedette.
  - *Masquer* Afficher uniquement les articles non en vedette.
  - *Uniquement* Afficher uniquement les articles en vedette.

### Onglet Intégration

Ces paramètres déterminent comment le composant d'articles s'intégrera avec d'autres extensions.

![Options d'intégration des articles](../../../fr/images/articles/articles-options-integration-tab.png)

#### Panneau Flux RSS

- **Lien vers flux RSS** Si l'option est activée, un lien vers le flux s'affichera sous forme d'icône dans la barre d'adresse de la plupart des navigateurs.
- **Inclure dans le flux**
  - *Texte d'introduction* Seul le texte d'introduction de l'article s'affichera dans le flux.
  - *Texte complet* Le texte entier de l'article s'affichera dans le flux.
- **Lien "Lire la suite"** Afficher un lien "Lire la suite" dans le flux.

#### Panneau Routage

- **Supprimer les ID des URL** Supprimer l'ID de la base de données des articles dans un lien.

#### Panneau Champs personnalisés

- **Modifier les champs personnalisés** Activer la création de champs personnalisés.

#### Panneau Workflow

- **Activer le workflow** Utiliser des workflows personnalisés pour gérer les articles.

## Conseils

- Les utilisateurs débutants peuvent conserver les valeurs par défaut ici.
- Les utilisateurs expérimentés peuvent gagner du temps en créant des valeurs par défaut appropriées ici. Les nouveaux éléments de menu et articles pourront ensuite utiliser les valeurs par défaut pour la plupart des options.
- Toutes les valeurs définies ici peuvent être remplacées au niveau de l'élément de menu, de la catégorie ou de l'article.

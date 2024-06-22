<!-- Filename: Help4.x:Articles:_Options / Display title: Articles : Paramètres -->

## Description

Used to set global defaults for menu items that display articles. These default values will be used when 'Use Global'
is selected for an option in an Articles menu item.

For example, to show the 'Create Date' for an article in your Articles
menu items, then set that option to 'Show' here and it will be the
default value.

You do not need to set any of these options. Your Joomla site will work
with the default settings.

## Comment y accéder
Sélectionner **Contenus → Articles**

- Cliquez sur le bouton **Paramètres** dans la barre d'outils.

## Capture d'écran

![Articles options screenshot](../../../fr/images/articles/articles-options-articles-tab.png "Articles options")

## Champs de formulaire

### Articles

Options used in articles and the menu items Blog, List, Featured Articles,
List All Categories, and Single Article.

#### Type de mise en page

- **Mise en page**. Choisissez dans la liste déroulante la mise en page
  à appliquer. Si vous avez défini des mises en page alternatives pour
  les articles, vous pouvez en sélectionner une dans la liste pour
  qu'elle soit la valeur par défaut pour les liens de menu sur article
  unique.
- **Titre de l'article**. Show the Article's Title.
- **Lien sur les titres**. Show the title as a link to the article.
- **Texte d'introduction**.
  - Afficher: The Intro Text of the article will show when you drill
    down to the article.
  - Masquer: Only the part of the article after the Read More break will
    show.
- **Position des informations**.
  - Au-dessus: Puts the article information block above the text.
  - Au-dessous: Puts the article information block below the text.
  - Diviser: Splits the article information block into 2 separate
    blocks. One block is above and the other is below the text.
- **Titre d'informations d'article**. Afficher ou masquer le titre
  d’informations de l'article.

#### Catégorie

- **Titre de la catégorie**. Show the Article's Category Title.
  - **Lien sur les titres**. Show the title as a link to that
    Category.Note: You can set this to be either a blog or list layout
    with the Choose a Layout
    option in the Category Tab.
- **Catégorie parente**. Afficher ou masquer le titre de la catégorie
  parente de la catégorie de l'article.
  - **Lien de catégorie parente**. Show the title as a link to that
    Category.Note: You can set this to be either a blog or list layout
    with the Choose a Layout
    option in the Category Tab.

#### Associations

- **Associations multilingues**. Show the associated flags or Language
  Code. Multilingual only.
  - **Utiliser les icônes**. Display language choice as image flags.

#### Auteur

- **Auteur**. Show the author of the Article.
  - **Lien vers sa page de contact**. Activer le lien sur le nom de
    l'auteur vers sa page de contact.Note: The author must be set up as
    a
    Contact.
    Also, a link will not show if there is an Author Alias
    value for the article.

#### Date

- **Date de création**. Show the Article's create date.
- **Date de modification**. Afficher la date et l'heure de dernière
  modification.
- **Date de Publication**. Show the Article's start publishing date.

#### Paramètres

- **Navigation entre articles**. Afficher ou masquer un lien de
  navigation (par exemple, Suivant, Précédent) entre les articles.
- **Lien "Lire la suite"**. Afficher le lien 'Lire la suite' lorsque
  l'article est affiché en format Blog ou dans un module.
- **Titre de l'article dans le lien**.
  - Afficher: The article title is part of the Read More link. The link
    will be in the format "Read More: \[article title\]".
  - Masquer: The link will be "Read more".
- **Nbr de caractères dans le lien**. The maximum number of characters
  from the title to include.Note: This can prevent the Read More text to
  become excessively long if the article has a very long title.
- **Tags de l'article**. Show the tags for each article.
- **Enregistrer les affichages**. Record the number of times the article
  has been viewed.
- **Nombre d'affichages**. Show the number of times the article has been
  displayed by a user.
- **Liens non autorisés**.
  - Oui: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - Non: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.
- **Positionnement des liens**.
  - Au-dessus: Links are shown above the content.
  - Au-dessous: Links are shown below the content.

### Agencement

Options of the article editing page.

![Articles options editing layout tab](../../../fr/images/articles/articles-options-editing-layout-tab.png "Articles options editing layout")

- **Captcha à utiliser**. Select the captcha plugin
  that will be used in the article submit form. If 'Use Global' is
  selected, make sure a captcha plugin is selected in Global Configuration.
- **Paramètres de publication**. Si non, l'onglet Paramètres de
  publication de cet écran (Articles: Écran
  Ajouter/Modifier
  ne sera pas visible. Cela signifie que les utilisateurs principaux ne
  pourront pas modifier les champs Créé par, Nom de remplacement, Date
  de création, Début de publication ou Fin de publication. Ces champs
  seront toujours définis sur leurs valeurs par défaut.
- **Paramètres d'article**. Hide the Article Options tab
  in the Backend when editing Articles. This means that Backend users
  will not be able to edit the fields in this tab. These fields will
  always be set to their default values.
- **Options d'affichage**. Hide the Configure Edit Screen tab
  when editing Articles.
- **Droits d'accès**. Hide the Permissions tab
  when editing Articles.
- **Associations multilingues**. Hide the Associations tab
  when editing Articles.
- **Activer l'historique**. Choisir de sauvegarder automatiquement ou
  non les versions anciennes d'un élément. Si oui, les versions
  anciennes seront sauvegardées automatiquement. Quand un élément sera
  modifié, une version précédente pourra être rétablie.
- **Nombre maximum de versions à conserver**. Le nombre maximum
  d'anciennes versions à sauvegarder. Si un élément est enregistré et le
  nombre maximum de versions a été atteint, la version la plus ancienne
  sera automatiquement supprimée. Si réglé sur "0", toutes les anciennes
  versions seront sauvegardées. Pour en savoir
  plus.
- **Images et liens en frontal**. Si oui, les champs Images et liens
  s'afficheront dans l'écran de l'éditeur d'articles frontal.
- **Images et liens en admin**. Hide the Images and Links tab
  in the Backend when editing Articles.
- **Cible de l'URL A**. Fenêtre cible du navigateur lorsque le lien de
  menu est cliqué. Les choix sont :
  - Ouvrir dans la fenêtre parente: Ouvre le lien dans la fenêtre
    principale du navigateur, en remplacement de l'article de Joomla!
    actuel.
  - Ouvrir dans une nouvelle fenêtre: Ouvre le lien dans une nouvelle
    fenêtre du navigateur.
  - Ouvrir en pop-up: Ouvre le lien dans une nouvelle fenêtre pop-up du
    navigateur (sans les contrôles de navigation complets).
  - Modale: Modale : ouvre le lien dans une fenêtre modale.
- **Cible de l'URL B**. Sets the default value for the target for the
  second Link in the article. Same options as URL A.
- **Cible de l'URL C**. Sets the default value for the target for the
  third Link in the article. Same options as URL A.
- **Classe de l'image de l'introduction**. fr
- **Classe de l'image de l'article complet**. fr

### Catégorie

Options control how a Category and its articles will show. They are used
in categories and the menu items Blog, List, and List All Categories.

![Articles options category tab](../../../fr/images/articles/articles-options-category-tab.png "Articles options category")

- **Mise en page**. Select the default layout to show when you click on
  a Category link.
- **Titre de la catégorie**. Show the title of the category.
- **Description**. Show the description for the category.
- **Image**. Show the category image.
- **Sous-catégories**. Control how many levels of subcategories to show.
- **Catégories vides**. Show categories that don't contain any articles
  or subcategories.
- **Message d'alerte**. Show a message "There are no articles in this
  category".
- **Titre des sous-catégories**. Show the Subcategories as subheading on
  the page.
- **Desc. des sous-catégories**. Show the descriptions for
  subcategories.
- **Nombre d'articles**. Show a count of the total number of articles in
  each category.
- **Tags de la catégorie**. Show the tags for the category.

### Catégories

Options control the display of the menu item List All Categories.

![Articles options categories tab](../../../fr/images/articles/articles-options-categories-tab.png "Articles options categories")

- **Desc. de la catégorie racine**. Show the description for the
  top-level category.
- **Sous-catégories**. Control how many levels of subcategories to show.
- **Catégories vides**. Show categories that don't contain any articles
  or subcategories.
- **Desc. des sous-catégories**. Show the description for subcategories.
- **Nombre d'articles**. Show a count of the total number of articles in
  each category.

### Blog/Épinglés

Options control the layout of the menu items
Blog,
Featured Articles,
and List All Categories.

![Articles options blog/featured layout tab](../../../fr/images/articles/articles-options-blog-layouts-tab.png "Articles options blog/featured layout")

- **Articles en pleine largeur**. Nombre d'articles en pleine largeur à
  afficher dans le blog. "0" signifie qu'il n'y aura aucun article
  affiché en pleine largeur. Si un article a la coupure "Lire la
  suite...", seule la partie du texte avant la coupure (le texte
  d'introduction) sera affichée.
- **Classe de l'article principal**. Vous pouvez ajouter n'importe
  quelle classe CSS pour vos propres idées de style. Ajoutez une bordure
  en haut avec la classe 'boxed'.Pour la position de l'image, utilisez
  par exemple 'image-left', 'image-right'. Ajoutez 'image-alternate'
  pour un ordre alternatif des images d'intro.
- **Introduction des articles**. Nombre d'articles dont seule
  l'introduction doit être affichée - ils seront affichés après les
  articles en pleine largeur s'il y en a. Les articles sont présentés en
  une ou plusieurs colonnes selon le paramètre "Nombre de colonnes"
  ci-dessous. Si un article a une coupure "Lire la suite...", seule la
  partie du texte avant la coupure (le texte d'introduction) sera
  affichée suivie d'un lien "Lire la suite...". L'ordre dans lequel
  s'affichent les articles est déterminé par l'Ordre de la Catégorie et
  le paramètre "Succession des articles" ci-dessous.
- **Classe d'article**. Vous pouvez ajouter n'importe quelle classe CSS
  pour vos propres idées de style. Ajoutez une bordure en haut avec la
  classe 'boxed'.Pour la position de l'image, utilisez par exemple
  'image-left', 'image-right'. Ajoutez 'image-alternate' pour un ordre
  alternatif des images d'intro.
- **Nombre de colonnes**. Nombre de colonnes utilisées pour l'affichage
  de l'Introduction des articles (paramètre ci-dessus). En général entre
  1 et 3 (en fonction des possibilités offertes par le template de site
  utilisé). Si 1 est utilisé, le texte d'introduction des articles
  s'affichera en utilisant la totalité de la largeur de la zone
  d'affichage comme les Articles en pleine largeur (paramètre
  ci-dessus).
- **Direction multicolonne**. In multi-column blog layouts, whether to
  order articles Down the columns or Across the columns.
  - Colonne: les articles se suivent à la verticale. Par exemple :
  - Ligne: les articles se suivent à l'horizontal. Par exemple :
- **Titres avec lien**. Nombre d'articles dont seul le titre, sous forme
  de lien, doit être affiché. Ces liens permettent à un utilisateur
  d'avoir un lien vers des articles supplémentaires dans le cas où il y
  a plus d'articles que ceux affichés sur la première page du blog.
- **Inclure les sous-catégories**.
  - Aucun: Only articles from the current category will show.
  - Tout: All articles from the current category and all subcategories
    will show.
  - 1-5: All articles from the current category and subcategories up to
    and including that level will show.
- **Image d'introduction liée**. If Yes, a click on the intro image
  shows the article.

### Listes

Options control the layout of the menu items List and List All Categories.

![Articles options list layouts tab](../../../fr/images/articles/articles-options-list-layouts-tab.png "Articles options list layouts")

- **Sélecteur d'affichage**. Show the Display \# control that allows the
  user to select the number of articles to show.
- **Champ de filtre**. Show a text field in the Frontend where a user
  can filter the articles.Options in the Backend menu item edit.
  - Masquer: Don't show a filter field.
  - Titre: Filter on article title.
  - Auteur: Filter on the author's name.
  - Clics: Filter on the number of article hits.
  - Tags: Filter on the article tags.
  - Mois (publié): Filter on the month of published articles.
- **En-tête**. Show a heading in the article list in the Frontend.
- **Date**. Show a date in the list.
  - Masquer: Don't show any date.
  - Créé: Show the created date.
  - Modifié: Show the date of the last modification.
  - Publié: Show the start publishing date.
- **Nombre d'affichages**. Show the number of hits for articles.
- **Auteur**. Show the name of the author.
- **\# Articles à lister**. Number of articles shown in the list.

### Paramètres partagés

Options shared by the menu items Blog, List, and Featured Articles.

![Articles options shared tab](../../../en/images/articles/articles-options-shared-tab.png "Articles shared")

- **Ordre des catégories**.
  - Aucun ordre: Articles are ordered only by the Article Order, without
    regard to Category.
  - Alphabétique des titres: Categories are displayed in alphabetical
    order (A to Z).
  - Alphabétique inverse des titres: Categories are displayed in reverse
    alphabetical order (Z to A).
  - Ordre des catégories: Categories are ordered according to the Order
    column entered in Articles: Categories.
- **Ordre des articles**.
  - Plus récents en premier: Articles are displayed starting with the
    most recent and ending with the oldest.
  - Plus ancien en premier: les articles sont affichés du plus ancien au
    plus récent.
  - Alphabétique des titres: Articles are displayed by Title in
    alphabetical order (A to Z).
  - Alphabétique inverse des titres: Articles are displayed by Title in
    reverse alphabetical order (Z to A).
  - Alphabétique des auteurs: Articles are displayed by Author in
    alphabetical order (A to Z).
  - Alphabétique inverse des auteurs: Articles are displayed by Author
    in reverse alphabetical order (Z to A).
  - Les plus populaires: les articles sont affichés selon le nombre de
    clics, de celui ayant le plus de clics à celui en ayant le moins.
  - Moins populaires: les articles sont affichés selon le nombre de
    clics, de celui ayant le moins de clics à celui en ayant le plus.
  - Ordre: Articles are ordered according to the Order column entered in
    Articles.
  - Ordre inverse: Articles are ordered reverse to the according of the
    Order column entered in
    Articles.
- **Classement par date**. The date used when articles are sorted by
  date.
  - Créé: Utilisez la date de création de l'article.
  - Modifié: Utilisez la date de modification de l'article.
  - Publié: Utilisez la date de début de publication de l'article.
- **Pagination**. Pagination provides page links at the bottom of the
  page that allow the User to navigate to additional pages. These are
  needed if the Articles will not fit on one page.
  - Masquer: Pagination links not shown. Note: Users will not be able to
    navigate to additional pages.
  - Afficher: Pagination links shown if needed.
  - Automatique: Pagination links shown if needed.
- **Résumé de la pagination**. Show the current page number and total
  pages (e.g., "Page 1 of 2") at the bottom of each page.
- **Articles épinglés**.
  - Afficher: Display featured articles and non-featured articles.
  - Masquer: Display only non-featured articles.
  - Uniquement: Display only featured articles.

### Intégration

Options control how Articles integrate News Feeds, Routing, Custom
Fields, and Workflow.

![Articles options integration tab](../../../fr/images/articles/articles-options-integration-tab.png "Articles options integration")

#### Fils d'actualité

- **Lien de flux RSS**. If set to Show, a Feed Link will show up as a
  feed icon in the address bar of most browsers.
- **Inclure dans le flux**.
  - Texte d'introduction: Only the article's intro text will show in the
    feed.
  - Texte complet: The entire text of the article will show in the feed.
- **Lien "Lire la suite"**. Show a "Read more" link in the feed.

#### Routage

- **Supprimer les "id" des URL**. Remove the database id of articles in
  a link.

#### Champs personnalisés

- **Intégration des champs**. Enable the creation of custom fields.
  Pour en savoir
  plus.

#### Flux de travail

- **Activer le flux de travail**. Use customised workflows to manage
  articles. Pour en savoir
  plus.

### Droits

This section lets you set up the default Access Control List
permissions for all articles in all categories.

![Articles options permissions tab](../../../fr/images/articles/articles-options-permissions-tab.png "Articles options permissions")

To change the permissions for articles and categories, do the following.

1.  Sélectionnez le groupe en cliquant sur son titre.
2.  Find the desired **Action**.
    - **Configurer les droits et paramètres**. Users can edit the
      options and permissions.
    - **Ne configurer que les paramètres**. Users can edit the options
      exept the permissions.
    - **Accès à l'interface d'administration**. Users can access user
      administration interface.
    - **Créer**. Users can create articles and categories.
    - **Supprimer**. Users can delete articles and categories.
    - **Modifier**. Users can edit articles and categories.
    - **Modifier le statut**. User can change the published state and
      related information.
    - **Modifier ses éléments**. Users can edit own created articles and
      categories.
    - **Modifier les valeurs des champs personnalisés**. Users can edit
      any value of custom fields submitted in articles and categories.
    - **Gérer le flux de travail**. Users can manage workflows.
    - **Exécuter la transition**. Users can execute transitions.
3.  Sélectionnez l'autorisation souhaitée pour l'action que vous
    souhaitez modifier.
    - **Hérité**. Inherited for users in this Group from the Global Configuration
      permissions.
    - **Autorisé**. Allowed for users in this Group.Note: If this action
      is Denied at one of the higher levels, the Allowed permission here
      will not take effect. A Denied setting cannot be overridden.
    - **Refusé**. Denied for users in this Group.
4.  Cliquez sur **Enregistrer** dans la barre d'outils située en haut à
    gauche. Lors de l'actualisation de l'écran, la colonne des Droits
    appliqués affichera les droits effectifs pour ce groupe et action.

## Barre d'outils

En haut de la page, vous verrez la barre d'outils présentée dans la
capture d'écran ci-dessus.

- **Enregistrer**. Saves the articles options and stays in the current
  screen.
- **Enregistrer & Fermer**. Saves the articles options and closes the
  current screen.
- **Fermer**. **Fermer**. Ferme l'écran actuel et retourne à l'écran
  précédent sans enregistrer les modifications que vous avez faites.
- **Afficher/Masquer l'aide**. Show help text below some options.
- **Aide**. Ouvre l'écran d'aide.

## Astuces

- Si vous êtes un utilisateur débutant, vous pouvez simplement conserver
  les valeurs par défaut ici jusqu'à en savoir plus sur l'utilisation
  des paramètres globaux.
- Si vous êtes un utilisateur expérimenté, vous pouvez gagner du temps
  en créant ici de bonnes valeurs par défaut. Lorsque vous configurez
  des éléments de menu et créez des articles, vous pourrez accepter les
  valeurs par défaut pour la plupart des paramètres.
- Toutes les valeurs définies ici peuvent être remplacées au niveau de
  l'élément de menu, de la catégorie ou de l'article.

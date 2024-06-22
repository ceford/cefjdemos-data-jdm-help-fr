<!-- Filename: Help4.x:Articles / Display title: Articles -->

## Description

La liste des articles est utilisée pour trouver, marquer les articles
épinglés, ajouter et modifier des articles.

Les articles sont les unités de base de l'information dans le système de
contenu et le plus bas niveau dans la hiérarchie du contenu. Chaque
Article est inclus dans une et une seule Catégorie.

## Comment y accéder ?
Sélectionner **Panneau d'administration → Site → Articles**

To add a Article:

- click the **New** toolbar button

To edit a Article:

- select a **Title** from the list

## Capture d'écran

![Articles list](../../../fr/images/articles/articles-list.png "Article list")

## En-Têtes de colonne

- **Checkbox**. Check this box to select articles. To select all
  articles, check the box in the column heading. After boxes are checked
  the toolbar button 'Actions' get active.
- **Ordre**. You can change the order of an article within a list as
  follows:
  - Select the Ordering icon <i class="fa-solid fa-sort"></i> in the first
  column heading to make it active.
  - Select one of the vertical ellipsis icons <span class="icon-ellipsis-v"></span>
 and drag it up or down to change the
    position of that row in the list.
  - In the Filter Options you may limit the list to articles that are
    assigned for example to a Language.
- **Épinglé**. Click the icon to toggle. The article will show on the
  Featured Articles
  page.
- **Statut**. Status of article. Hover icon for informations.
- **Titre**. The title of the article. Edit the article by clicking on
  the Title.
- **Accès**. The viewing Access level  for this article.
- **Auteur**. Name of the User who created this article.
- **Association**. Shows the associated articles. Click on the Language
  Code to open the article. Multilingual only.
- **Langue**. Articles language, default is 'All'.
- **Date de création**. The date this article was created.
- **Clics**. The number of times an article has been viewed.
- **Id**. A unique identification number for this article, you cannot
  change this number.

## Liste des filtres

**Search bar**. Near the top of the page you will see the search bar
shown in the Screenshot above.

- **Search by Text**. Enter part of the search term and click the Search
  icon. *Hover* to see a *Tooltip* indicating which fields will be
  searched.To 'Search by ID' enter "id:x", where "x" is the ID number
  (for example, "id:19").
- **Filtres d'affichage**. Click to display the additional filters.
- **Effacer**. Click to clear the Filter field and restore the list to
  its unfiltered state.
- **Ordre**. Affiche le champ d'ordre actuel de la liste. 2 façons de
  changer l'ordre :
  - Select from the dropdown list. Ordering may be in ascending or
    descending order.
  - Click a column heading. The column heading toggles between ascending
    and descending order.
- **Number to Display**. Shows the number of articles in a list. Select
  from the dropdown list to change the number displayed.The default for
  a site is '20' but this may be changed in the Global Configuration.

### Filtres d'affichage

En haut de la page, vous verrez la barre d'outils présentée dans la
capture d'écran ci-dessus.

- **Épinglé**. Select from Unfeatured Articles / Featured Articles.
- **Statut**. Select from Trashed / Unpublished / Published / Archived /
  All.
- **Catégorie**. Select from the list of available categories.
- **Niveau d'accès**. Select from the list of available viewing access
  levels.
- **Auteur**. Select from the list of available authors.
- **Langue**. Select from the list of available languages.
- **Tag**. Select from the list of available tags.
- **Niveau d'arborescence**. Select from the list of available levels.

### Pagination

**Page Controls**. When the number of articles is more than one page,
you will see a page control bar near the bottom of the page shown in the
Screenshot above. The current page number being viewed
has a dark colour background.

- **Start**. Click to go to the first page.
- **Prev**. Click to go to the previous page.
- **Numéros de page**. Cliquez pour accéder à la page désirée.
- **Next**. Click to go to the next page.
- **End**. Click to go to the last page.

## Barre d'outils

En haut de la page, vous verrez la barre d'outils présentée dans la
capture d'écran ci-dessus.

- **Nouveau**. Opens the editing screen to create a new article.
- **Actions**. Reveals a list of actions for selected articles. Check
  one or more articles checkboxes to activate the list.
  - **Publier**. Makes the selected articles available to visitors to
    your website.
  - **Dépublier**. Makes the selected articles unavailable to visitors
    to your website.
  - **Épingler**. Marks selected articles as featured.
  - **Désépingler**. Changes the status of featured articles to
    unfeatured.
  - **Archiver**. Changes the status of the selected articles to
    indicate that they are archived. Pour en savoir
    plus.
  - **Déverrouiller**. Checks-in the selected articles.
  - **Corbeille**. Changes the status of the selected articles to
    indicate that they are trashed. Pour en savoir
    plus.
  - **Traiter**. Batch processes the selected articles.
- **Paramètres**. Ouvre
- **Aide**. Ouvre l'écran d'aide.

## Processus de traitement par lots

The Batch Process allows a change in settings for a group of selected
articles.

![articles batch process](../../../fr/images/articles/articles-list-batch.png "Articles batch process")

**Comment traiter par lots** un groupe d'éléments :

1.  Select one or more articles on the list by checking the desired
    checkboxes.
2.  Click the Batch Toolbar button.
3.  Set one or more of the following values:
    - To change the **Language**, select the desired new language from
      the Set Language list box.
    - To change the **Access Levels**, select the desired new access
      level from the Set Access Level list box.
    - To change the **Category**, select a category. To leave the
      category unchanged, use the default value of 'Select'.
      - To **copy** the articles to a different category, select the
        desired category from the category list box and check the Copy
        option. In this case, the original articles are unchanged and
        the copies are assigned to the new category and, if selected,
        the new language, access level, and tag.
      - To **move** the articles to a different category, select the
        desired category from the category list box and check the Move
        option. In this case, the original articles will be moved to a
        new category and, if selected, be assigned the new language,
        access level, and tag.
    - To add **Tags**, select the desired Tags from the dropdown or
      choose to keep the tags currently added to the original articles.
4.  When all of the settings are entered, click on Process to perform
    the changes. A message **"Batch process completed successfully."**
    will show.

## Astuces

- If Joomla is installed without sample data, one article category
  called 'Uncategorised' is created automatically.
- Pour voir les articles à la corbeille et ceux archivés, mettez le
  filtre du statut à "Tout".
- Pour changer l'ordre des articles dans une catégorie, cliquez sur
  l'entête de la colonne "Ordre" pour les trier suivant cette colonne.
  De plus, il est plus facile de voir l'ordre en filtrant sur la
  catégorie souhaitée.

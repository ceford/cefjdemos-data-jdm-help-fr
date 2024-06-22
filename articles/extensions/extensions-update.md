<!-- Filename: Help4.x:Extensions:_Update / Display title: Extensions : Mettre à jour -->

## Description

Cet écran vous permet de mettre à jour les extensions installées qui
disposent d'un serveur de mise à jour. La mise à jour en direct de
l'extension se produit sans qu'il soit nécessaire de télécharger et
d'installer manuellement les fichiers d'extension mis à jour. Ils sont
obtenus à partir du serveur de mise à jour distant à l'aide de méthodes
de connexion HTTP standard.

## Comment y accéder ?

- Sélectionnez **Système → Encadré mise à jour → Extensions**
  dans l'administration. Ensuite, pour effectuer une mise à jour...
  - Cochez la case d'un ou plusieurs éléments à mettre à jour.
  - Sélectionnez le bouton **Mise à jour** dans la barre d'outils.

## Capture d'écran

<img
src="https://docs.joomla.org/images/d/d7/Help-4x-extensions-extension-manager-update-en.png"
decoding="async" data-file-width="800" data-file-height="363"
width="800" height="363"
alt="extensions extension manager update" />

## En-Têtes de colonne

<img
src="https://docs.joomla.org/images/thumb/1/1d/Help-4x-Extensions-Manage-Update-columns-en.png/680px-Help-4x-Extensions-Manage-Update-columns-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/1/1d/Help-4x-Extensions-Manage-Update-columns-en.png 1.5x"
data-file-width="871" data-file-height="29" width="680" height="23"
alt="Extensions Manage Update columns" />

- **Checkbox**. Check this box to select one or more items. To select
  all items, check the box in the column heading. After one or more
  boxes are checked, click a toolbar button to take an action on the
  selected item or items. Many toolbar actions, such as Publish and
  Unpublish, can work with multiple items. Others, such as Edit, only
  work on one item at a time. If multiple items are checked and you
  press Edit, the first item will be opened for editing.
- **Nom.** Le nom de l'extension.
- **Emplacement**. Spécifie s'il s'agit d'une extension de site ou
  d'administration.
- **Type.** Le type d'extension. Des exemples de types d'extension sont
  le module, le plugin, le template, le composant, le pack de langue ou
  le package.
- **Installé**. Le numéro de version de l'extension actuellement
  installée.
- **Disponible**. Le numéro de version de la mise à jour disponible.
- **Changelog**. Le journal des modifications.
- '*Dossier*. Si l'extension est un plugin, le sous-répertoire du
  répertoire /plugins de votre installation Joomla ! où se trouve
  l'extension. Par défaut, Joomla ! possède les sous-répertoires
  suivants dans le répertoire plugins qui représentent chacun les
  différents types de plugins définis : authentication, content,
  editors, editors-xtd, extension, search, system, user.
- **Type d'installation**. Le type d'installation qui sera effectué par
  la mise à jour. En général, il s'agit du type ***Update*** qui
  effectue une mise à jour sur place de l'extension.

## Liste des filtres

**Search bar**. Near the top of the page you will see the search bar
shown in the Screenshot above.

- **Search by Text**. Enter part of the search term and click the Search
  icon. *Hover* to see a *Tooltip* indicating which fields will be
  searched.To 'Search by ID' enter "id:x", where "x" is the ID number
  (for example, "id:19").
- **Filter Options**. Click to display the additional filters.
- **Clear**. Click to clear the Filter field and restore the list to its
  unfiltered state.
- **Ordering**. Shows the current list ordering field. 2 ways to change
  the order:
  - Select from the dropdown list. Ordering may be in ascending or
    descending order.
  - Click a column heading. The column heading toggles between ascending
    and descending order.
- **Number to Display**. Shows the number of items in a list. Select
  from the dropdown list to change the number displayed.The default for
  a site is '20' but this may be changed in the Global Configuration.

#### Filter Options

- **-Select Location-.** Select Site, Administrator or API from the
  drop-down list of available locations.
- **-Select Type-.** Select the extension type from the drop-down list
  box of available types.
- **-Select Folder-.** Select a plug-in folder from the drop-down list
  box of available folders. There is a separate folder for each type of
  plug-in defined in your Joomla installation.

**Page Controls**. When the number of items is more than one page, you
will see a page control bar near the bottom of the page shown in the
Screenshot above. The current page number being viewed
has a dark colour background.

- **Start**. Click to go to the first page.
- **Prev**. Click to go to the previous page.
- **Page numbers**. Click to go to the desired page.
- **Next**. Click to go to the next page.
- **End**. Click to go to the last page.

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above. The functions are:

- **Update.** Perform update of selected options. This will fetch an
  update file from the update server and may take several seconds.
  Please be patient!
- **Find Updates.** Query update servers for the latest versions of
  installed extensions. Again, this may take a while.
- **Clear Cache.** Clear the available extension update information
  displayed in the listing.
- **Options.** Opens the Options window where settings such as default
  parameters can be edited.
- **Help**. Opens this help screen.

## Quick Tips

- Only extensions which support the Joomla! update system will be listed
  in this screen. If you use extensions which do not support the new
  update system or you are not sure, consult the extension developer's
  website.
- It is critical to keep your extensions up-to-date. Failure to do so
  may expose a vulnerability in your Joomla! installation which can be
  exploited by hackers.
- It is recommended to backup your Joomla! installation files and
  database before attempting to update extensions or the Joomla!
  installation itself. This will ensure that you can restore your
  Joomla! installation to its previous state if the update fails or
  causes unexpected results.

<!-- Filename: Help4.x:Modules / Display title: Modules -->

## Description

Les modules sont des extensions légères et flexibles utilisées pour afficher des extraits d'informations dans des encadrés disposés autour d'un composant sur une page. Un exemple bien connu est le module *Connexion*. Les modules sont assignés par élément de menu, ce qui vous permet de décider d'afficher ou de masquer un module en fonction de la page que l'utilisateur consulte actuellement.

Certains modules sont liés à des composants. Par exemple, le module *Dernières Nouvelles* est lié au composant de contenu pour afficher des liens vers les articles les plus récents. Les modules n'ont pas besoin d'être liés à des composants. Ils peuvent même ne pas être liés à quoi que ce soit et se contenter d'être du HTML ou du texte statique.

Il peut y avoir plusieurs instances du même module. Par exemple, vous pouvez utiliser une instance du module *Image Aléatoire* pour certaines pages et une autre instance pour d'autres pages, chacune utilisant un dossier d'images différent.

Les listes *Modules (Site)* et *Modules (Administrateur)* affichent les modules actuellement installés dans chaque interface et fournissent un accès pour ajouter de nouveaux modules ou modifier des modules existants.

### Éléments communs

Certains éléments de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonne](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordre des éléments de la liste](jdocmanual?article=help/common-elements/list-ordering).
* [Pagination de la liste](jdocmanual?article=help/common-elements/list-pagination).
* [Processus par lots](jdocmanual?article=help/common-elements/list-batch-process).

Pour voir les listes des modules installés et disponibles, sélectionnez l'un des éléments suivants :

* [Modules de site](jdocmanual?article=help/modules-site/site-modules-site)
* [Modules administratifs](jdocmanual?article=help/modules-admin/admin-modules-administrator)

## Comment y accéder

- Sélectionnez **Contenu → Modules de site** dans le menu d'administration. Ou...
- Sélectionnez **Contenu → Modules administratifs** dans le menu d'administration.

## Filtres de liste

* **Site ou Administrateur** Sélectionne soit les modules de site, soit les modules administratifs.

## En-têtes de colonne

Voici une courte liste des en-têtes uniques aux listes de modules.

- **Position** La position sur la page où ce module est affiché.
- **Type** Le nom système du module.
- **Pages** Les éléments de menu où ce module sera affiché. Cet élément n'est pas présent dans les listes de modules administratifs.
  - *Tous* Affiché sur toutes les pages
  - *Aucun* Affiché sur aucune page
  - *Sélectionné* Affiché uniquement sur les pages sélectionnées
  - *Tous sauf sélectionnés* Affiché sur toutes les pages sauf celles sélectionnées
- **Accès** Le niveau d'accès pour ce module.
- **Langue** La langue des modules, par défaut c'est *Tous*. Cet élément n'est pas présent dans les listes de modules administratifs.

### Positions des modules

Pour afficher les positions des modules sur un site en direct, allez dans **Système → Templates** et sélectionnez le bouton **Options** dans la barre d'outils. Réglez *Aperçu des positions des modules* sur activé et cliquez sur *Enregistrer*. Ce paramètre est valable pour les templates de site et d'administrateur. Ensuite, ajoutez `?tp=1` à la fin d'une URL qui ne contient pas déjà de chaîne de requête ou `&tp=1` à la fin d'une URL qui contient déjà une chaîne de requête. La page affichera toutes les positions de module disponibles, même celles auxquelles aucun module n'a été assigné. Les positions sont également affichées dans le formulaire de modification des modules.

## Conseils

- Les sites Joomla nécessitent au moins un module de menu.
- D'autres types de modules (par exemple, les bannières) sont optionnels.
- Certains modules sont liés à des composants. Par exemple, chaque module de menu est lié à un menu.
- D'autres modules (par exemple, les fil d'Ariane) ne dépendent d'aucun autre contenu.
- Plusieurs occurrences d'un module sont autorisées et courantes.

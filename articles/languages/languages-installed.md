<!-- Filename: Help4.x:Languages:_Installed / Display title: Langues : Installées -->

## Description

La page *Langues : Installées* est utilisée pour lister les langues installées et définir les langues par défaut indépendamment pour les interfaces du site et de l'administrateur.

### Éléments communs

Certains éléments de cette page sont abordés dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonne de liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Pagination de liste](jdocmanual?article=help/common-elements/list-pagination).

## Comment y accéder

- Sélectionnez **Système → Panneau de gestion → Langues** dans le menu de l'administrateur.

## Capture d'écran

![Liste des langues installées pour le site](../../../fr/images/languages/languages-installed-site.png)

## Filtres de liste

### Filtrer par Site ou Administrateur

- **Site** Affiche les langues installées pour l'interface du site (frontend). Sélectionnez un élément dans la colonne *Par défaut* pour le définir comme langue par défaut du frontend.
- **Administrateur** Affiche les langues installées pour l'interface de l'administrateur (backend). Sélectionnez un élément dans la colonne *Par défaut* pour le définir comme langue par défaut du backend.

## Conseils

- Les utilisateurs peuvent utiliser n'importe quelle langue de la liste des langues installées, en assignant des langues Backend et Frontend dans l'onglet *Paramètres de base* du formulaire *Utilisateurs : Modifier* de l'administrateur ou dans le formulaire *Modifier votre profil* du frontend. Cela fera que les messages système de Joomla! s'afficheront dans cette langue uniquement pour cet utilisateur. Par exemple, si un utilisateur choisit l'espagnol comme langue, le module de recherche s'affichera avec des messages en espagnol.
- Changer la langue d'un utilisateur ou la langue par défaut n'affecte pas les articles et autres contenus du site.
- **Important:** Ne supprimez pas les fichiers de langue par défaut (par exemple, avec FTP). Cela créera des erreurs à la fois sur le frontend et le backend.
- Des langues supplémentaires peuvent être ajoutées via l'écran d'installation des langues.
- Si vous le souhaitez, vous pouvez afficher le site frontend dans une langue et les pages d'administration backend dans une autre langue. De plus, des articles individuels peuvent être configurés pour utiliser une langue différente dans le panneau des paramètres avancés lors de la modification de l'article.

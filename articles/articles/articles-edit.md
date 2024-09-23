<!-- Filename: Help4.x:Articles:_Edit / Display title: Articles : Modifier -->

## Description

Cette page est utilisée pour ajouter un nouvel article ou modifier un article existant, généralement en utilisant un éditeur Wysiwyg. L'éditeur par défaut est TinyMCE, mais si d'autres éditeurs sont installés, l'éditeur par défaut peut être défini sur autre chose pour l'ensemble du site ou pour des utilisateurs individuels.

### Éléments communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Schéma](jdocmanual?article=help/common-elements/edit-schema).
* [L'onglet Publication](jdocmanual?article=help/common-elements/edit-publishing).
* [L'onglet Associations](jdocmanual?article=help/common-elements/edit-associations).
* [L'onglet Permissions](jdocmanual?article=help/common-elements/edit-permissions).
* [L'historique des versions](jdocmanual?article=help/common-elements/edit-version-history).

Ou dans des articles utilisateurs :

* [Ajouter une image à un article](jdocmanual?article=user/articles/adding-an-image-to-an-article)

## Comment y accéder

* Sélectionnez **Contenu → Articles** dans le menu Administrateur. Ou...
* Sélectionnez **Articles** depuis le tableau de bord d'accueil. Ensuite...
    * Sélectionnez le **Titre** d'un article existant dans la liste pour le modifier. Ou...
    * Sélectionnez le bouton **Nouveau** dans la barre d'outils pour créer un nouvel article.
Vous pouvez également créer un nouvel article en sélectionnant l'icône **+** dans le menu ou le tableau de bord d'accueil.

## Capture d'écran

![Capture d'écran de la modification des articles](../../../fr/images/articles/articles-edit-content-tab.png)

## Champs du formulaire

- **Titre** Le titre de cet article.
- **Alias** Le nom interne de cet article. Normalement, vous pouvez laisser ce champ vide et Joomla générera automatiquement une valeur par défaut basée sur le titre, en minuscules et avec des tirets à la place des espaces.

### Onglet Contenu

#### Panneau gauche

- **Texte de l'article** C'est ici que vous entrez le contenu de l'article. Joomla inclut 3 éditeurs, l'éditeur par défaut - TinyMCE est affiché ci-dessus.

    La liste déroulante CMS Content permet d'accéder à des liens vers un article, un contact, un champ, une image média, un menu, un module, une rupture de page ou une rupture Lire la suite.

    Le symbole des points de suspension (<span class="icon-ellipsis-h"></span>) bascule la visibilité des outils supplémentaires.
- **Basculer l'éditeur** Le bouton sous la fenêtre d'édition vous permet de basculer entre l'éditeur TinyMCE et aucun éditeur. Cela vous permet de voir et parfois de corriger le code HTML.

#### Panneau droit

- **Statut** Le statut de publication de cet article.
  - *Publié* L'article est visible dans l'interface du site.
  - *Non publié* L'article ne sera pas visible pour les invités dans l'interface du site. Il peut être visible pour les utilisateurs connectés ayant l'autorisation de modifier l'état de l'article.
  - *Archivé* L'article ne s'affichera plus dans les éléments de menu ou la liste des catégories.
  - *Dans la corbeille* L'article est supprimé du site mais reste dans la base de données.
- **Catégorie** Sélectionnez la catégorie pour cet article.
- **En vedette** Sélectionnez Oui si l'article doit être affiché dans l'élément de menu En vedette.
- **Accès** Sélectionnez le niveau d'accès de visualisation pour cet article. Les niveaux d'accès dépendent de ce qui a été configuré dans Utilisateurs : Niveaux d'accès.
- **Langue** Sélectionnez la langue de cet article. Conservez la valeur par défaut 'Tous' si vous n'utilisez pas la fonction multilingue.
- **Étiquettes** Assignez des étiquettes à cet article. Vous pouvez sélectionner une étiquette dans une liste prédéfinie ou en entrer une nouvelle en tapant le nom dans le champ et en appuyant sur Entrée.
- **Note** Ceci est normalement à l'usage de l'administrateur (par exemple, pour documenter des informations sur cet article) et n'apparaît pas dans l'interface.
- **Note de version** Champ facultatif pour identifier la version de cet article dans l'historique des versions de l'article.

### Onglet Images et Liens

**Remarque :** Cet onglet peut être masqué dans *Article : Options* par un utilisateur avec des permissions d'administration. Il permet d'afficher des images et des liens dans les articles en utilisant des mises en page standardisées.

![Onglet images et liens](../../../fr/images/articles/articles-edit-images-tab.png)

#### Image d'introduction

- **Image d'introduction** Cliquez sur le bouton Sélectionner pour choisir une image à afficher à un emplacement fixe dans le texte d'introduction de cet article. Cela ouvrira une fenêtre permettant de sélectionner une image dans le dossier des images.
- **Description de l'image (texte Alt)** Définissez l'attribut alt pour cette image. Quelques mots descriptifs pour les lecteurs d'écran.
- **Pas de description** Cochez dans le cas rare d'une image purement décorative. Notez que si la description de l'image est vide et que la case Pas de description n'est pas cochée, l'image ne respectera pas les critères d'accessibilité. Si une description d'image est présente, cette case à cocher n'a aucun effet.
- **Classe d'image** Ajoutez toute classe CSS pour un style personnalisé. Par exemple, pour la position de l'image, utilisez float-start ou float-end.
- **Légende** Créez une légende pour cette image.

#### Image de l'article complet

- **Image de l'article complet** Cliquez sur le bouton Sélectionner pour choisir une image à afficher à un emplacement fixe dans le texte complet de cet article. Cela ouvrira une fenêtre permettant de sélectionner une image dans le dossier des images.
- **Description de l'image (texte Alt)** Définissez l'attribut alt pour cette image. Quelques mots descriptifs pour les lecteurs d'écran.
- **Pas de description** Cochez dans le cas rare d'une image purement décorative. Notez que si la description de l'image est vide et que la case Pas de description n'est pas cochée, l'image ne respectera pas les critères d'accessibilité. Si une description d'image est présente, cette case à cocher n'a aucun effet.
- **Classe d'image** Ajoutez toute classe CSS pour un style personnalisé. Par exemple, pour la position de l'image, utilisez float-start ou float-end.
- **Légende** Entrez une légende facultative pour cette image.

#### Lien A

- **Lien A** L'URL du premier lien à afficher à un emplacement fixe dans le texte de l'article. Cela doit être une URL complète, et non relative. Par exemple, elle commencerait normalement par `https:`.
- **Texte du lien A** Le texte utilisé pour le lien A. Si vide, l'URL sera affichée.
- **Fenêtre cible de l'URL** Définit la valeur par défaut pour la cible du premier lien dans cet article. Les choix sont :
  - *Ouvrir dans la fenêtre parente* Ouvre dans la fenêtre principale du navigateur, remplaçant l'article Joomla actuel.
  - *Ouvrir dans une nouvelle fenêtre* Ouvre le lien dans une nouvelle fenêtre du navigateur.
  - *Ouvrir dans une fenêtre popup* Ouvre le lien dans une fenêtre popup du navigateur (sans les contrôles de navigation complets).
  - *Modal* Ouvre le lien dans une fenêtre popup modale.

#### Lien B, Lien C

- Les mêmes options que Lien A.

### Onglet Options

**Remarque :** Cet onglet peut être masqué par un utilisateur avec des permissions d'administration dans Article : Options. Il s'agit d'un ensemble d'options utilisées pour contrôler comment cet article s'affichera dans l'interface.

![Onglet Options](../../../fr/images/articles/articles-edit-options-tab.png)

#### Mise en page

- **Mise en page** Utilisez une mise en page à partir de la vue article fournie ou des surcharges dans les modèles.
- **Titre** Afficher le titre de l'article.
- **Titres liés** Afficher le titre comme un lien vers l'article.
- **Étiquettes** Entrez des étiquettes pour cet article. Sélectionnez des étiquettes existantes en tapant les premières lettres ou créez de nouvelles étiquettes en les entrant ici.
- **Texte d'introduction**
  - *Afficher* Le texte d'introduction de l'article apparaîtra sur une page affichant l'article complet.
  - *Masquer* Seule la partie de l'article après la rupture Lire la suite apparaîtra sur une page affichant l'article complet.
- **Position des informations sur l'article**
  - *Au-dessus* Place le bloc d'informations de l'article au-dessus du texte.
  - *En dessous* Place le bloc d'informations de l'article sous le texte.
  - *Divisé* Sépare le bloc d'informations de l'article en deux blocs distincts. Un bloc est au-dessus et l'autre est en dessous du texte.
- **Titre des informations sur l'article** Affiche 'Détails' en haut du bloc d'informations sur l'article.

#### Catégorie

- **Catégorie** Afficher le titre de la catégorie de l'article.
- **Lien vers la catégorie** Afficher le titre comme un lien vers cette catégorie.
- **Catégorie parente** Afficher le titre de la catégorie parente de l'article.
- **Lien vers la catégorie parente** Afficher le titre comme un lien vers cette catégorie.

#### Associations

- **Associations** Afficher les drapeaux associés ou le code de langue. Multilingue uniquement.

#### Auteur

- **Auteur** Afficher l'auteur de l'article.
- **Lien vers la page de contact de l'auteur** L'afficher comme un lien vers une mise en page de contact pour cet auteur. Remarque : L'auteur doit être configuré en tant que contact.

#### Date

- **Date de création** Afficher la date de création de l'article.
- **Date de modification** Afficher la date de modification de l'article.
- **Date de publication** Afficher la date de début de publication de l'article.

#### Options

- **Navigation** Afficher les liens de navigation, *Précédent* et/ou *Suivant*, lors de l'affichage d'une page contenant l'article complet.
- **Hits** Afficher le nombre de fois que l'article a été affiché par un utilisateur.
- **Liens non autorisés** Si Oui, le texte d'introduction des articles restreints s'affichera. Cliquer sur le lien Lire la suite nécessitera une connexion pour voir le contenu complet de l'article.
- **Position des liens**
  - *Au-dessus* Les liens s'affichent au-dessus du contenu.
  - *En dessous* Les liens s'affichent en dessous du contenu.
- **Texte Lire la suite** Personnaliser le texte qui s'affiche pour le libellé par défaut 'Lire la suite'.
- **Titre de la page du navigateur** Texte pour le titre de la page du navigateur utilisé lorsque l'article est consulté avec un élément de menu non lié à l'article. Si vide, le titre de l'article sera utilisé à la place.

### Onglet Champs

Cette section affiche les champs personnalisés définis pour cet article. Ce sont des champs qui ne sont pas assignés à un groupe de champs. Chaque groupe de champs, s'il est défini, apparaîtra comme un onglet séparé.

![Onglet Champs](../../../fr/images/articles/articles-edit-fields-tab.png)

### Onglet Configurer l'écran de modification

**Remarque :** Cet onglet peut être masqué par un utilisateur avec des permissions d'administration dans Article : Options.

![Onglet Configurer l'écran de modification](../../../fr/images/articles/articles-edit-editor-tab.png)

- **Options de publication** Si Masquer, l'onglet Options de publication ne s'affichera pas dans l'interface. Cela signifie que les utilisateurs du backend ne pourront pas modifier les champs de cet onglet. Ces champs seront toujours définis sur leurs valeurs par défaut.
- **Options de l'article** Si Masquer, l'onglet Options de l'article ne s'affichera pas dans l'interface. Cela signifie que les utilisateurs du backend ne pourront pas modifier les champs de cet onglet. Ces champs seront toujours définis sur leurs valeurs par défaut.
- **Images et liens de l'administrateur** Si Oui, l'onglet Images et liens s'affichera.
- **Images et liens dans l'interface** Si Oui, l'onglet Images et liens s'affichera dans l'écran de l'éditeur d'articles de l'interface.

## Conseils

- Il existe 2 méthodes pour insérer une image dans un article en utilisant l'éditeur TinyMCE.
  1. La liste déroulante *CMS Content* donne accès à l'écran Média.
  2. La liste déroulante *Insérer* est un formulaire simple qui nécessite l'URL de l'image. Il est utilisé pour les images externes.
- Un insert *Lire la suite* économise de l'espace sur toute page de mise en page En vedette ou Blog en affichant uniquement la première partie d'un article. Les inserts *Rupture de page* fournissent une navigation multi-page pour les articles longs. Les deux peuvent être utilisés dans un même article si désiré. Par exemple, une rupture *Lire la suite* peut être placée après le premier paragraphe et des ruptures *Rupture de page* peuvent être placées après d'autres groupes de paragraphes pour créer un article multi-page. Aucune navigation de page ne s'affichera sur la page En vedette ou Blog jusqu'à ce que l'utilisateur sélectionne le lien Lire la suite. À ce moment, la table des matières de l'article s'affichera, montrant des liens vers chaque page.

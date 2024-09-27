<!-- Filename: Help4.x:Tags:_New_or_Edit / Display title:  Tags : Ajouter ou Modifier un tag -->

## Description

La page *Tags: New or Edit* est utilisée pour ajouter ou modifier des tags qui peuvent être utilisés pour afficher le contenu du site par nom de tag.

### Éléments Communs

Certains aspects de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).

## Comment y accéder

- Sélectionnez **Composants → Étiquettes** dans le menu Administrateur. Ensuite
  - Sélectionnez le bouton '**Nouveau'** dans la barre d'outils pour créer une nouvelle étiquette.
  - Sélectionnez un titre d'étiquette dans la colonne **Titre** de la liste pour modifier une étiquette existante.

## Capture d'écran

![édition des balises, onglet des détails de la balise](../../../fr/images/tags/tags-edit-tag-details-tab.png)

## Champs de Formulaire

- **Titre** Le nom de cet article. Ce champ est requis.
- **Alias** Le nom interne de l'article. Normalement, vous pouvez laisser
  ce champ vide et Joomla remplira une valeur par défaut du Titre en minuscules
  et avec des tirets à la place des espaces.

### Onglet Détails des Étiquettes

#### Panneau de gauche

- **Description** Indiquez le but de cette étiquette.

#### Panneau de droite

- **Parent** L'élément (catégorie, élément de menu, etc.) qui est le
  parent de l'élément en cours de modification.
- **Statut** Le statut de publication de l'article.
- **Accès** Le niveau d'accès de visualisation pour cet article.
- **Langue** La langue de l'article.
- **Note** Ce champ est normalement utilisé par l'administrateur du site (par
  exemple, pour documenter des informations sur cet article) et ne s'affiche pas
  sur le frontend du site.
- **Note de Version** Champ optionnel pour identifier cette version de l'article
  dans la fenêtre Historique des Versions de l'article.

### Onglet Options

![étiquettes modifier l'onglet des options](../../../fr/images/tags/tags-edit-options-tab.png)

#### Panneau Options

- **Mise en page** Utilisez une mise en page de la vue du composant fournie ou des
  substitutions dans les modèles.
- **Classe CSS pour le lien de l'étiquette** Ajoutez des classes CSS spécifiques pour le lien de l'étiquette.
  Si vide, *label label-info* sera ajouté par la mise en page de l'étiquette par défaut.

#### Panneaux d'Images

- **Image de Teaser** L'image qui sera affichée comme partie de la liste.
- **Float** Attribut float pour l'image.
- **Alt** Texte alternatif pour l'image.
- **Légende** La légende pour l'image.
- **Image Complète** Une image qui sera affichée dans la vue de l'étiquette unique.

### Onglet Publication

![étiquettes modifier l'onglet publication](../../../fr/images/tags/tags-edit-publishing-tab.png)

#### Panneau de Publication

- **Date de Création** Date à laquelle l'article (Article, Catégorie, etc.) a été créé.
- **Créé par** Nom de l'utilisateur Joomla qui a créé cet article. Cela
  sera par défaut l'utilisateur actuellement connecté. Si vous souhaitez
  changer cela pour un autre utilisateur, cliquez sur le bouton Sélectionner Utilisateur pour choisir un
  utilisateur différent.
- **Alias de Créé par** Ce champ optionnel vous permet d'entrer un alias
  pour cet Auteur pour cet Article. Cela vous permet d'afficher un nom d'Auteur différent pour cet Article.
- **Date de Modification** Date de la dernière modification.
- **Modifié par** Nom d'utilisateur qui a effectué la dernière modification.
- **Révision** ...
- **Hits** Le nombre de fois qu'un article a été consulté.
- **ID** C'est un numéro d'identification unique pour cet élément attribué
  automatiquement par Joomla. Il est utilisé pour identifier l'élément en interne,
  et vous ne pouvez pas changer ce numéro. Lors de la création d'un nouvel élément, ce
  champ affiche "0" jusqu'à ce que vous sauvegardiez la nouvelle entrée, auquel cas un nouveau
  ID lui est attribué.

#### Panneau des Métadonnées

- **Meta Description** Un paragraphe optionnel à utiliser comme
  description de la page dans la sortie HTML. Cela s'affichera généralement
  dans les résultats des moteurs de recherche. Si saisi, cela crée un élément méta HTML avec un attribut name
  de `<description>` et un attribut content égal au texte saisi.
- **Mots-clés** Entrée optionnelle pour des mots-clés. Doivent être saisis, séparés
  par des virgules (par exemple : chats, chiens, animaux de compagnie) et peuvent être saisis en
  majuscules ou minuscules. (Par exemple : *CHATS* correspondra à *chats* ou
  *Chats*). Les mots-clés peuvent être utilisés de plusieurs manières :
  1.  Pour aider les moteurs de recherche et autres systèmes à classifier le contenu de
      l'Article.
  2.  En combinaison avec des étiquettes de Bannière, pour afficher des Bannières spécifiques basées
      sur le contenu de l'Article. Par exemple, disons que vous avez une Bannière avec
      une publicité pour des produits pour chiens et une autre Bannière pour des produits pour chats. Vous pouvez
      faire afficher votre Bannière pour chiens lorsqu'un Utilisateur consulte un
      Article lié aux chiens et votre Bannière pour chats pour un Article lié aux chats. Pour ce faire, vous devez :
      - Ajouter les mots-clés "chien" et "chat" aux Articles appropriés.
      - Ajouter les Étiquettes "chien" et "chat" aux Bannières appropriées dans
        Bannière : Modifier.
      - Définir le Paramètre du module de Bannière 'Recherche par Étiquettes' sur "Oui" dans
        la liste des Modules de Site : Bannières.
  3.  Pour les articles uniquement, en combinaison avec le module Articles - Liés,
      pour afficher des Articles qui partagent au moins un mot-clé en commun. Par exemple,
      si l'Article actuellement affiché a les mots-clés "chats,
      chiens, singes", tout autre Article avec au moins un de ces
      mots-clés s'affichera dans le module 'Articles - Liés'.
- **Auteur** Entrée optionnelle pour un nom d'Auteur dans les métadonnées. Si saisi, cela crée un élément méta HTML avec l'attribut name de 'author' et l'attribut content tel qu'entré ici.
- **Robots** Les instructions pour les 'robots' web qui parcourent cette
  page.
  - *index, follow* Indexer cette page et suivre les liens sur cette page.
  - *noindex, follow* Ne pas indexer cette page, mais suivre les
    liens sur la page. Par exemple, vous pourriez faire cela pour une page de plan du site
    où vous voulez que les liens soient indexés mais que cette
    page ne s’affiche pas dans les moteurs de recherche.
  - *index, nofollow* Indexer cette page, mais ne suivre aucun lien sur
    la page. Par exemple, vous pourriez vouloir faire cela pour un calendrier d’événements,
    où vous voulez que la page s’affiche dans les moteurs de recherche, mais vous
    ne voulez pas indexer chaque événement.
  - *noindex, nofollow* Ne pas indexer cette page ou suivre les liens
    sur la page.
  - *Utiliser la Configuration Globale* Définie dans Configuration Globale : Paramètres des Métadonnées.

*Traduit par openai.com*


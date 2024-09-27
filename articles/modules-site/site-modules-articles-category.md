<!-- Filename: Help4.x:Site_Modules:_Articles_-_Category  / Display title: Modules: Articles - Catégorie -->

## Description

Le type de module *Articles - Catégorie* affiche une liste d'articles publiés
provenant d'une ou plusieurs catégories.

### Éléments Communs

Certains éléments de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Les Modules : Onglet Modules](jdocmanual?article=help/modules/modules-module-tab).
* [Les Modules : Onglet d'Assignation de Menu](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Les Modules : Onglet Avancé](jdocmanual?article=help/modules/modules-advanced-tab).
* [L'Onglet Permissions](jdocmanual?article=help/common-elements/edit-permissions).

<!-- À faire : Un tutoriel pour montrer comment utiliser ce module -->

## Comment accéder

- Sélectionnez **Système → Gérer le panneau → Modules du site** dans le menu Administrateur. Ensuite...
  - Pour créer un nouveau module : sélectionnez le bouton **Nouveau** dans la barre d'outils. Ensuite...
    - Sélectionnez le type de module requis.
  - Pour modifier un module existant :
    - Trouvez le module dans la liste des modules installés et sélectionnez le lien du titre dans la colonne **Titre**.

## Capture d'écran

![onglet module catégorie articles](../../../fr/images/modules-site/modules-articles-category-module-tab.png)

## Champs de Formulaire

- **Titre** Le titre du module. C'est aussi le titre affiché pour le module en fonction du champ de formulaire *Afficher le Titre*.

### Onglet Module

#### Panneau de Gauche

- **Mode** Sélectionnez le mode à utiliser. Si le mode Normal est choisi, configurez simplement le module et il affichera une liste statique d'articles sur les éléments de menu auxquels vous attribuez le module. Si le mode Dynamique est choisi, vous pouvez toujours configurer le module normalement, mais l'option Catégorie ne sera plus utilisée. Au lieu de cela, le module détectera dynamiquement si vous êtes sur une vue de Catégorie et affichera la liste des articles dans cette Catégorie en conséquence. Lorsque le mode Dynamique est choisi, il est préférable de laisser le module défini pour s'afficher sur toutes les pages, car il décidera dynamiquement d'afficher ou non quelque chose.
- **Afficher sur la Page Article** Cet élément apparaît si le mode *Dynamique* est sélectionné. Sélectionnez pour afficher ou masquer une liste d'articles depuis les pages d'articles. Cela signifie que le module ne s'affichera dynamiquement que sur les pages de Catégorie.

### Onglet Options de Filtrage

![onglet options de filtrage des catégories d'articles](../../../fr/images/modules-site/modules-articles-category-filtering-options-tab.png)

- **Articles en Vedette** Afficher ou masquer ou sélectionner uniquement les articles en vedette.
- **Nombre** Le nombre d'éléments à afficher. La valeur par défaut de 0 affichera tous les articles.
- **Type de Filtrage de Catégorie** Inclure ou exclure les catégories sélectionnées.
- **Catégorie** Sélectionnez une ou plusieurs catégories.
- **Articles de Catégorie Enfant** Inclure ou exclure les articles de catégories enfants.
- **Profondeur de Catégorie** Le nombre de niveaux de sous-catégorie à retourner.
- **Type de Filtrage des Auteurs** Inclure ou exclure les articles des auteurs sélectionnés.
- **Auteurs** Sélectionnez un ou plusieurs auteurs dans la liste.
- **Type de Filtrage des Alias d'Auteur** Inclure ou exclure les alias d'auteur sélectionnés.
- **Alias des Auteurs** Sélectionnez un ou plusieurs alias d'auteur dans la liste.
- **IDs d'Articles à Exclure** Entrez chaque ID d'article à exclure sur une nouvelle ligne.
- **Filtrage par Date** Sélectionnez le type de filtrage par date.
- **Champ de Plage de Dates** Sélectionnez le champ de plage de dates à utiliser.
- **Plage de Dates de Début** Si Plage de Dates est sélectionnée ci-dessus, entrez une date de début.
- **Jusqu'à Date** Si Plage de Dates est sélectionnée ci-dessus, entrez une date de fin.
- **Date Relative** Si Date Relative est sélectionnée ci-dessus, entrez une valeur numérique de jour. Les résultats seront récupérés par rapport à la date actuelle et à la valeur entrée.

### Onglet Options de Classement

![onglet options de classement des catégories d'articles](../../../fr/images/modules-site/modules-articles-category-ordering-options-tab.png)

- **Champ d'Article à Classer** Sélectionnez un champ de la liste. Le classement des articles en vedette ne doit être utilisé que lorsque l'option de filtrage pour les articles en vedette est définie sur *Uniquement*.
- **Direction du Classement** Sélectionnez la direction du classement des articles.

### Onglet Options de Groupement

![onglet options de groupement des catégories d'articles](../../../fr/images/modules-site/modules-articles-category-grouping-options-tab.png)

- **Groupement d'Article** Sélectionnez une méthode de groupement des articles dans la liste.
- **Direction du Groupement** Sélectionnez la direction du classement.
- **Format d'Affichage du Mois et de l'Année** Entrez un format de date valide.

### Onglet Options d'Affichage

![onglet options d'affichage des catégories d'articles](../../../fr/images/modules-site/modules-articles-category-display-options-tab.png)

- **Titres Liés** Afficher les titres comme des liens vers les articles.
- **Date** Afficher ou masquer la date de l'article.
- **Champ de Date** Sélectionnez le champ de date à afficher.
- **Format de Date** Entrez un format de date valide.
- **Catégorie** Afficher ou masquer le nom de la catégorie de l'article.
- **Hits** Afficher ou masquer les hits de l'article.
- **Auteur** Afficher ou masquer le nom de l'auteur ou de l'alias de l'auteur.
- **Introtexte** Afficher ou masquer le texte d'introduction de l'article.
- **Limite d'Introtexte** Le nombre maximum de caractères à afficher.
- **Afficher "Lire la suite"** Afficher ou masquer le lien *Lire la suite...* si le texte principal de l'article a été fourni.
- **Afficher le Titre avec Lire la suite** Afficher ou masquer le titre de l'article dans le lien *Lire la suite...*.
- **Limite de "Lire la suite"** Limitez le nombre de caractères du titre de l'article à afficher dans le lien *Lire la suite...*.

*Traduit par openai.com*


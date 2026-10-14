<!--
{
    "source": "https://docs.joomla.org/Help5.x:Site_Modules:_Articles",
    "title": "Modules : Articles",
    "description": " ",
    "author": ""
}
-->

## Description

Le module **Articles** affiche une liste d’articles. Il est destiné à remplacer
cinq autres modules d’articles :

* [Modules : Articles - Archivés](jdocmanual?article=help/modules-site/site-modules-articles-archived).
* [Modules : Articles - Catégorie](jdocmanual?article=help/modules-site/site-modules-articles-category).
* [Modules : Articles - Derniers](jdocmanual?article=help/modules-site/site-modules-articles-latest).
* [Modules : Articles - Les plus lus](jdocmanual?article=help/modules-site/site-modules-articles-most-read).
* [Modules : Articles - Flash d’information](jdocmanual?article=help/modules-site/site-modules-articles-newsflash).

Les options du module **Articles** sont principalement configurées via quatre onglets :

- L’*onglet Options de filtrage* permet de spécifier les articles affichés.
- L’*onglet Options d’affichage* spécifie comment les articles sont affichés dans le module et quels détails sont inclus.
- L’*onglet Options de tri* permet de configurer la priorité des articles.
- L’*onglet Options de regroupement* permet de configurer la priorité des articles.

**Important :** le module apparaît uniquement lorsqu’un ou plusieurs articles correspondants sont disponibles. S’il est vide, le module n’apparaît pas.

### Éléments communs

Certains éléments de cette page sont traités dans des articles d’aide distincts :

* [Barres d’outils](jdocmanual?article=help/common-elements/toolbars).
* [L’onglet Modules : Modules](jdocmanual?article=help/modules/modules-module-tab).
* [L’onglet Modules : Affectation de menus](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [L’onglet Modules : Avancé](jdocmanual?article=help/modules/modules-advanced-tab).
* [L’onglet Droits](jdocmanual?article=help/common-elements/edit-permissions).

## Comment y accéder

- Sélectionnez **Contenu → Modules du site** ou **Système → Panneau de gestion → Modules du site**
  dans le menu d’administration, ou **Panneau du site → Modules** depuis le tableau de bord d’accueil.
  Puis...
  - Pour créer un nouveau module : sélectionnez le bouton **Nouveau** dans la barre d’outils de la
    liste des *Modules*. Puis...
     - Sélectionnez le module **Articles**.
  - Pour modifier un module existant : recherchez le module dans la liste des modules installés
    et sélectionnez le lien du titre dans la colonne **Titre**.

## Capture d’écran

![Formulaire du module Articles, onglet Module](../../../fr/images/modules-site/site-modules-articles/01-module-tab.png)

## Champs du formulaire

### Onglet Module

#### Panneau de gauche

- **Mode**
  - Le *Mode normal* configure le module pour afficher une liste statique d’articles.
  - Le *Mode dynamique* configure le module pour détecter s’il utilise ou non une vue de catégorie et affiche en conséquence la liste des articles de cette catégorie. Lorsque le mode dynamique est choisi, il est préférable de laisser le module configuré pour s’afficher sur toutes les pages, car il déterminera dynamiquement s’il doit afficher quelque chose ou non.
- **Articles à afficher** Nombre maximal d’articles à afficher.
- **Type de filtrage des catégories** Spécifie comment les articles sont filtrés en fonction des catégories indiquées dans le champ *Catégorie*.
  - *Inclusif* Seuls les articles appartenant aux catégories spécifiées sont affichés.
  - *Exclusif* Les articles appartenant aux catégories spécifiées sont exclus.
- **Catégorie** Affiche ou exclut les articles appartenant aux catégories sélectionnées. Ce paramètre fonctionne en complément des autres paramètres de filtrage.
- **Articles des sous-catégories** Visible uniquement lorsque le paramètre *Exclure ou inclure des articles* est défini sur *Inclure*. Inclut ou exclut les articles appartenant aux catégories qui sont des sous-catégories des catégories indiquées dans le champ *Catégorie*.
- **Profondeur des catégories** Visible uniquement lorsque le paramètre *Articles des sous-catégories* est défini sur *Inclure*. Spécifie le nombre de niveaux de sous-catégories utilisés.
- **Exclure ou inclure des articles** Inclut ou exclut des articles spécifiques.
- **Articles à inclure** Visible uniquement lorsque le paramètre *Exclure ou inclure des articles* est défini sur *Inclure*. Si ce champ est vide, tous les articles sont inclus ; sinon, seuls les articles sélectionnés sont inclus.
- **Exclure l’article actuel** Visible uniquement lorsque le paramètre *Exclure ou inclure des articles* est défini sur *Exclure*. Exclut ou inclut l’article actuel.
- **Articles à exclure** Visible uniquement lorsque le paramètre *Exclure ou inclure des articles* est défini sur *Exclure*. Spécifie les articles à exclure de la liste.

### Onglet des options d’affichage

![Onglet du module de formulaire du module Articles](../../../fr/images/modules-site/site-modules-articles/02-display-options-tab.png)

- **Titre uniquement (listes)** (*Oui/Non*). Si *Oui*, la liste des articles se compose uniquement des titres des articles, liés à l’article. Toutes les autres options sont masquées.
- **Mise en page**
  - *Verticale* Les articles apparaissent dans une seule colonne verticale.
  - *Horizontale* Les articles apparaissent dans un maximum de 1 à 4 colonnes verticales, selon la largeur du module ; la largeur du module est déterminée par la position du module, la mise en page de la page, le modèle, la largeur de l’écran, la largeur d’affichage du navigateur et d’autres facteurs. 
- **Nombre maximal de colonnes** Cette option apparaît uniquement lorsque la mise en page est définie sur Horizontale. Elle spécifie le nombre maximal de colonnes dans une mise en page horizontale (*2–4*).
- **Titre de l’article** Affiche ou masque le titre de l’article.
- **Niveau d’en-tête** Cette option apparaît uniquement lorsque *Titre de l’article* est défini sur *Afficher*. Elle spécifie le niveau de titre HTML du titre de l’article (*h1–h5, aucun*). 
- **Lien du titre** Cette option apparaît uniquement lorsque *Titre de l’article* est défini sur *Afficher*. 
  - *Oui* Le titre est un hyperlien vers l’article.
  - *Non* Le titre n’est pas un hyperlien vers l’article.
- **Auteur** Affiche ou masque l’auteur de l’article.
- **Catégorie** Affiche ou masque la catégorie de l’article.
- **Lien de catégorie** Apparaît uniquement si la *Catégorie* est affichée.
  - *Afficher* Lie le titre de la catégorie à sa page de catégorie.
  - *Masquer* Affiche le titre de la catégorie, mais ne le lie pas.
- **Date** Affiche ou masque la date de l’article.
- **Champ de date** Cette option apparaît uniquement lorsque *Date* est défini sur *Afficher*. Elle spécifie la date de l’article qui sera affichée : *Date de création/Date de modification/Date de début de publication*.
- **Format de date** Cette option apparaît uniquement lorsque *Date* est défini sur *Afficher*. Elle spécifie le format de date, par exemple Y-m-d H-i-s. Consultez le [manuel PHP](https://www.php.net/manual/en/datetime.format.php) pour obtenir des informations sur le formatage.
- **Affichages** Affiche ou masque le nombre de fois où l’article a été consulté.
- **Mise en page des informations de l’article** Apparaît uniquement si l’un des champs de métadonnées ci-dessus (*Auteur, Catégorie, Date ou Affichages*) est affiché. Spécifie la manière dont les métadonnées de l’article sont affichées :
  - *Multiligne* Chaque paramètre est affiché sur sa propre ligne.
  - *Une seule ligne* Les paramètres apparaissent côte à côte sur une seule ligne, qui peut être renvoyée à la ligne selon leur taille et la largeur du module.
- **Balises** Affiche ou masque les balises d’un article.
- **Déclencher les événements des plugins** Sélectionnez *Oui* pour déclencher des événements de plugins supplémentaires afin d’afficher du contenu supplémentaire, tel que des champs personnalisés ou des informations de vote.
- **Texte d’introduction** Affiche ou masque le texte d’introduction de l’article. La quantité de texte affichée est contrôlée par le paramètre *Limite du texte d’introduction (caractères)*.
- **Limite du texte d’introduction (caractères)** Cette option apparaît uniquement lorsque *Texte d’introduction* est défini sur *Afficher*. Elle spécifie le nombre de caractères d’introduction affichés. Si la valeur est définie sur 0, le texte de l’article entier est affiché. 
- **Afficher les images de l’article** Cette option apparaît uniquement lorsque *Texte d’introduction* est défini sur *Afficher* et que *Limite du texte d’introduction (caractères)* est définie sur zéro (ce qui affiche le texte intégral de l’article). Si cette option est définie sur *Afficher*, les images de l’article sont affichées avec le texte.
- **Afficher l’image d’introduction/complète** Affiche l’image d’introduction de l’article, l’image complète ou aucune image au-dessus du titre et des détails de l’article.
- **Lien « Lire la suite »** Affiche ou masque un lien « Lire la suite » sous les détails de l’article.
- **Lire la suite avec le titre** Cette option apparaît uniquement lorsque l’option *Lire la suite* est définie sur *Afficher*. Elle ajoute le titre au lien *Lire la suite*.
- **Limite de « Lire la suite » (caractères)** Cette option apparaît uniquement lorsque l’option *Lire la suite avec le titre* est définie sur *Afficher*. Elle spécifie le nombre maximal de caractères du titre à afficher dans le lien *Lire la suite*.

### Onglet Options de filtrage

![Onglet du formulaire du module Articles](../../../fr/images/modules-site/site-modules-articles/03-filtering-options-tab.png)

- **Articles en vedette**
  - *Afficher* Permet aux articles en vedette d’apparaître dans la liste.
  - *Masquer* Exclut les articles en vedette de la liste.
  - *Uniquement* Affiche uniquement les articles en vedette dans la liste.
- **Articles archivés** Indique comment les articles archivés apparaissent dans la liste.
  - *Aucun* Exclut les articles archivés de la liste.
  - *Uniquement* Affiche uniquement les articles archivés dans la liste.
- **Balises** Si cette option est renseignée, limite la liste aux seuls articles possédant une ou plusieurs des balises spécifiées.
- **Type de filtrage par auteur** Filtre la liste par auteur.
  - *Inclusif* Limite la liste aux articles des auteurs spécifiés uniquement.
  - *Exclusif* Exclut les articles des auteurs spécifiés.
  - *Uniquement de l’utilisateur actuel* Affiche uniquement les articles rédigés par l’utilisateur actuel.
- **Auteurs** Liste des auteurs à inclure ou à exclure.
- **Type de filtrage par alias d’auteur** Filtre la liste par alias d’auteur.
  - *Inclusif* Limite la liste aux articles des alias d’auteur spécifiés uniquement.
  - *Exclusif* Exclut les articles des alias d’auteur spécifiés.
- **Alias d’auteur** Liste des alias d’auteur à inclure ou à exclure.
- **Filtrage par date** Indique comment les articles sont filtrés par date.
  - *Désactivé* Aucun filtrage par date.
  - *Plage de dates* Limite la liste aux articles dont les dates se situent dans la plage de dates spécifiée.
  - *Date relative* Limite la liste aux articles qui se situent dans un nombre de jours spécifié par rapport à la date actuelle.
- **Champ de la plage de dates** Cette option apparaît uniquement lorsque le *Filtrage par date* est défini sur *Plage de dates* ou *Date relative*. Indique quelle date de l’article utiliser pour le filtrage par date (*Date de création/Date de modification/Date de début de publication*).
- **Début de la plage de dates** Cette option apparaît uniquement lorsque le *Filtrage par date* est défini sur *Plage de dates*. Elle indique la date et l’heure de début du filtre de plage de dates.
- **Jusqu’à la date** Cette option apparaît uniquement lorsque le *Filtrage par date* est défini sur *Plage de dates*. Elle indique la date et l’heure de fin du filtre de plage de dates.
- **Date relative** Cette option apparaît uniquement lorsque le *Filtrage par date* est défini sur *Date relative*. Elle indique le nombre de jours par rapport à la date actuelle à inclure dans la liste des articles.

### Onglet Options de tri

![Onglet du formulaire du module Articles](../../../fr/images/modules-site/site-modules-articles/04-ordering-options-tab.png)

- **Champ d’article pour le tri**
  - *Ordre des articles* Ordre dans lequel les articles sont organisés manuellement dans l’écran d’administration *Contenu > Articles*.
  - *Ordre des articles en vedette* Ordre dans lequel les articles en vedette sont organisés dans l’écran d’administration *Contenu > Articles en vedette*.
  - *Nombre de clics* Trié selon le nombre de consultations de la page (clics).
  - *Titre* Trié selon le titre de l’article.
  - *ID* Trié selon le numéro d’identification de l’article.
  - *Alias* Alias de navigation de l’article.
  - *Date de création/Date de modification/Date de début de publication/Date de fin de publication* Trié selon la date de l’article.
  - *Aléatoire* Tri aléatoire à chaque accès ou actualisation de la page. La *Direction du tri* est ignorée.

### Onglet Options de regroupement

![Onglet du formulaire du module Articles](../../../fr/images/modules-site/site-modules-articles/05-grouping-options-tab.png)

Les champs *Champ de regroupement par date* et *Format d’affichage du mois et de l’année* sont uniquement visibles lorsqu’un regroupement lié à une date est sélectionné.

- **Regroupement des articles**
  - *Aucun* Aucun regroupement.
  - *Année* Affiche l’année comme titre.
  - *Mois et année* Affiche le mois et l’année comme titre.
  - *Auteur* Affiche l’*Alias d’auteur* ou l’*Auteur* comme titre.
  - *Catégorie* Les catégories apparaissent comme titres.
  - *Balises* Les balises apparaissent comme titres. Les articles possédant plusieurs balises apparaissent sous plusieurs titres.
- **Champ de regroupement par date** Affiché uniquement lorsque *Année* ou *Mois et année* est sélectionné. Date de l’article selon laquelle effectuer le regroupement (*Date de création/Date de modification/Date de début de publication*).
- **Format d’affichage du mois et de l’année** Affiché uniquement lorsque *Année* ou *Mois et année* est sélectionné. Indique comment afficher le titre du mois et de l’année. Consultez le [manuel PHP](https://www.php.net/manual/en/datetime.format.php) pour obtenir des informations sur le formatage.
- **Direction du regroupement** Indique comment trier les titres des groupes (*Croissant/Décroissant*).

## Capture d’écran du site en frontal

*Les images d’exemple du site en frontal ont été obtenues avec le template Cassiopeia.*

Module Articles dans la barre latérale droite affichant uniquement les titres.

![Capture d’écran du site montrant le module avec uniquement les titres des articles](../../../en/images/modules-site/site-modules-articles/06-site-titles.png)

Module Articles dans la barre latérale droite affichant le titre, l’auteur et la date.

![Capture d’écran du site montrant le module avec le titre, l’auteur et la date des articles](../../../en/images/modules-site/site-modules-articles/07-title-author-date.png)

Module Articles dans l’emplacement principal supérieur affichant le texte d’introduction et l’image, ainsi qu’un bouton *Lire la suite*.

![Capture d’écran du site montrant l’emplacement supérieur du module et le bouton Lire la suite](../../../en/images/modules-site/site-modules-articles/08-top-text-image-readmore.png)

Module Articles dans l’emplacement principal supérieur configuré pour une disposition horizontale avec le texte d’introduction et l’image, ainsi qu’un bouton *Lire la suite*.

![Capture d’écran du site montrant le module avec le texte d’introduction de l’article, l’image et le bouton Lire la suite](../../../en/images/modules-site/site-modules-articles/09-text-image-readmore.png)

## Exemples de configuration

Le module Articles affiche une liste d’articles dans différents formats et agencements. Il a été conçu dans le but de créer un module unique hautement configurable, capable de remplacer les fonctionnalités limitées de cinq modules Articles distincts. Cette section présente des exemples simples de configuration du module pour chacun de ces rôles.

## Articles - Archivés

Le module *Articles - Archivés* affiche une liste de titres mois/année correspondant aux mois qui contiennent des articles archivés. Le titre est un lien vers la vue des articles archivés, où les articles individuels sont affichés. Le module *Articles* peut être configuré pour obtenir un résultat similaire.

**Paramètres de configuration**

| Onglet              | Paramètre          | Réglage |
|-------------------|--------------------|---------|
| Options d’affichage   | Titres uniquement (listes) | Oui     |
| Options de filtrage | Articles archivés  | Uniquement    |
| Options de regroupement  | Regroupement des articles   | Mois et année |
| Options de regroupement  | Format d’affichage du mois et de l’année | F, Y |

![Comparaison des articles archivés avec chaque méthode](../../../en/images/modules-site/site-modules-articles/10-config-archived.png)

<big>*Remarques*</big>

Le module *Articles - Archivés* affiche un lien unique vers une page d’articles archivés qui présente la liste des articles archivés et permet d’ajuster la date d’archivage. Le module *Articles* affiche directement la liste des articles ; le regroupement par mois et année est facultatif. La liste peut être filtrée précisément à l’aide des nombreux contrôles disponibles, et un large éventail d’options d’affichage permet de présenter des informations supplémentaires sur les articles. 

## Articles - Catégorie

Le module *Articles - Catégorie* affiche une liste de liens vers les articles d’une catégorie spécifiée.

**Paramètres de configuration**

| Onglet             | Paramètre          | Réglage |
|-----------------|--------------------|----|
| Module          | Catégorie           | [indiquer la catégorie et les sous-catégories souhaitées]|
| Options d’affichage | Titres uniquement (listes) | Oui |

![Comparaison des articles par catégorie avec chaque méthode](../../../en/images/modules-site/site-modules-articles/11-config-category.png)

## Articles - Derniers

Le module *Articles - Derniers* affiche une liste de liens vers les articles les plus récents.

**Paramètres de configuration**

| Onglet              | Paramètre          | Réglage |
|------------------|--------------------|----|
| Options d’affichage  | Titres uniquement (listes) | Oui |
| Options de tri | Champ d’article selon lequel effectuer le tri | Date de début de publication|
| Options de tri | Sens du tri | Décroissant |

![Comparaison des derniers articles avec chaque méthode](../../../en/images/modules-site/site-modules-articles/12-config-latest.png)

<big>*Remarques*</big>

Le module *Articles* ne propose pas le tri *Consultés* disponible dans le module *Articles - Derniers*, mais il offre plusieurs options de tri qui ne sont pas disponibles dans le module *Articles - Derniers*. 

## Articles - Les plus lus

Le module *Articles - Les plus lus* affiche une liste de liens vers les articles ayant enregistré le plus grand nombre de consultations.

**Paramètres de configuration**

| Onglet              | Paramètre          | Réglage |
|------------------|--------------------|----|
| Options d’affichage  | Titres uniquement (listes) | Oui |
| Options de tri | Champ d’article selon lequel effectuer le tri | Consultations |
| Options de tri | Sens du tri | Décroissant |

![Comparaison des articles les plus lus avec chaque méthode](../../../en/images/modules-site/site-modules-articles/13-config-most-read.png)

## Articles - Flash d’actualités

Le module *Articles - Flash d’actualités* affiche le texte d’un ou de plusieurs articles. Par défaut, seul le texte de l’article est affiché ; toutefois, il peut être configuré pour afficher le titre, les images, les liens « Lire la suite » et davantage. Ici, il est configuré pour afficher le titre et le texte de plusieurs articles. Dans cet exemple, le module *Articles* est configuré pour reproduire ce comportement de base.

**Paramètres de configuration**

| Onglet            | Paramètre          | Paramètre |
|------------------|--------------------|----|
| Options de classement | Champ de l’article pour le classement | Date de début de publication |
| Options de classement | Sens du classement | Décroissant |
| Options d’affichage  | Titre uniquement (listes) | Non |
| Options d’affichage  | Lien du titre         | Non |
| Options d’affichage  | Texte d’introduction          | Afficher |
| Options d’affichage  | Limite du texte d’introduction (caractères) | 0 (pour un texte illimité) |

![Comparaison des flashs d’actualités d’articles avec chaque méthode](../../../en/images/modules-site/site-modules-articles/14-config-news-flash.png)

*Traduit par openai.com*
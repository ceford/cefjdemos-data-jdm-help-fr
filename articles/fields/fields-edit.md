<!-- Filename: Help4.x:Fields:_Edit / Display title: Articles: Modifier le champ -->

## Description

La page *Composant : Modifier le champ* est similaire pour tous les composants qui implémentent des champs, mais le titre de la page change en fonction du contexte : *Articles : Modifier le champ*, *Contacts : Modifier le champ* ou *Utilisateurs : Modifier le champ*.

L'onglet **Général** change pour refléter le type de champ en cours de modification et, une fois un champ enregistré, son type ne peut plus être modifié. Cependant, il est facile de supprimer des champs et d'en créer de nouveaux.

### Éléments communs

Certains aspects de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Onglet Publication](jdocmanual?article=help/common-elements/edit-publishing).
* [Onglet Permissions](jdocmanual?article=help/common-elements/edit-permissions).

## Comment y accéder

* Sélectionnez **Contenu → Champs** dans le menu d'administration. Ou...
* Sélectionnez **Contact → Champs** dans le menu d'administration. Ou...
* Sélectionnez **Utilisateurs → Champs** dans le menu d'administration. Puis...
  * Sélectionnez le bouton **Nouveau** dans la barre d'outils pour créer un nouveau champ. Ou...
  * Sélectionnez un **Titre** dans la liste pour modifier un champ existant.

**Remarque :** Il existe une liste déroulante permettant de créer des champs pour une catégorie et le courrier dans le composant Contact. Ils nécessitent une certaine expérience en codage pour préparer des substitutions de modèles appropriées.

## Capture d'écran

![Modifier le champ des articles](../../../fr/images/fields/articles-edit-field.png)

## Champs du formulaire

- **Titre** Le titre de ce champ.

### Onglet Général

#### Panneau de gauche

Paramètres pour tous les champs :

- **Type** Si vous créez un champ, vous pouvez choisir l'un des 16 types de champs. Une fois le champ enregistré, ce type est permanent.
- **Nom** Le nom sera utilisé pour identifier le champ. Laissez ce champ vide et Joomla remplira une valeur par défaut à partir du titre.
- **Étiquette** Utilisez un texte descriptif pour l'étiquette du champ. Ce texte n'est pas traduisible. Si vous n'entrez pas de texte pour une étiquette, le texte du titre sera également utilisé comme étiquette.
- **Description** La description du champ. Un texte qui sera affiché comme info-bulle lorsque l'utilisateur déplacera la souris sur la zone de texte dans le backend lors de la création d'un article ou d'un contact, ou d'un composant tiers qui prend en charge les champs. Ce texte n'est pas traduisible. Vous ne voyez pas cette description dans le frontend.
- **Obligatoire** Ce champ est-il obligatoire ? Dans ce cas, le champ doit être rempli avant de soumettre un article, un contact ou un composant tiers qui prend en charge les champs.

#### Panneau de droite

- **Statut** Le statut de publication de ce champ.
  - *Publié* Le champ est visible lors de l'édition d'un article ou d'un contact. Et il est visible dans le frontend.
  - *Non publié* Le champ ne sera pas visible pour les utilisateurs lors de l'édition d'un article ou d'un contact.
  - *Archivé* Le champ ne s'affichera plus lors de l'édition d'un article ou d'un contact. Vous pouvez l'ouvrir dans Champs lorsque vous définissez le filtre sur Archivé.
  - *À la corbeille* Le champ est supprimé mais toujours présent dans la base de données. Il peut être supprimé définitivement de la base de données dans Champs avec la fonction Vider la corbeille.
- **Groupe de champs** Vous pouvez affecter un champ à un groupe de champs.
- **Catégorie** Vous pouvez affecter un champ à une ou plusieurs catégories. Notez que la valeur par défaut *Tout* n'inclut pas les articles *Non catégorisés*.
- **Accès** Sélectionnez le niveau d'accès d'affichage pour ce champ. Les niveaux d'accès dépendent de ce qui a été configuré dans *Utilisateurs : Niveaux d'accès*.
- **Langue** Sélectionnez la langue de ce champ. Si vous n'utilisez pas la fonctionnalité multilingue de Joomla, conservez la valeur par défaut *Tout*.
- **Note** Un champ optionnel pour ajouter des notes personnelles concernant le champ.

### Onglet Options

![Onglet Options de modification du champ des articles](../../../fr/images/fields/articles-edit-field-options-tab.png)

#### Options du formulaire

- **Espace réservé** Un texte d'espace réservé qui apparaîtra à l'intérieur du champ comme une suggestion pour l'entrée. L'espace réservé est actif dans le backend lors de la création d'un article ou d'un contact, ou d'un composant tiers prenant en charge les champs. Vous ne le voyez pas dans le frontend.
- **Classe du champ** Les attributs de classe du champ lorsqu'il est rendu. Si plusieurs classes sont nécessaires, listez-les avec des espaces.
- **Classe de l'étiquette (Formulaire)** Classe CSS à appliquer à l'étiquette du champ en mode édition (saisie dans un champ).
- **Modifiable dans** Dans quelle partie du site le champ doit-il être affiché ? Dans le backend, dans le frontend ou les deux ?
- **Attribut Showon** Afficher ou masquer conditionnellement le champ en fonction de la valeur d'autres champs. La syntaxe à utiliser ici, par exemple :
  `liste-d-éléments:valeur1[OU]liste-d-éléments:valeur2`
  - liste-d-éléments : Le *nom* d'un champ déjà créé dont ce champ dépendra pour être affiché.
  - valeur1 : La valeur nécessaire pour que le champ dont il dépend soit affiché.
  - `[OU]` : Pour créer un choix parmi plusieurs champs. Dans l'exemple, ce champ s'affichera lorsque le champ *liste-d-éléments* aura la valeur : *valeur1* OU *valeur2*
  - `[ET]` : Pour combiner plusieurs champs. Ce champ ne s'affichera que lorsque le champ *liste-d-éléments* aura la valeur : *valeur1* ET *valeur2*
  - Vous pouvez également utiliser la valeur *n'est pas égale à* comme dans *liste-d-éléments!:valeur1*. La syntaxe affichera ce champ uniquement lorsque *liste-d-éléments* n'est pas égal à *valeur1*
  - Pour afficher ce champ lorsque le champ *liste-d-éléments* a été sélectionné et ne contient pas de valeur vide, utilisez la syntaxe *liste-d-éléments!:* (sans valeur spécifiée).

**Remarque :** Les champs sous-formulaire traitent l'identifiant *nom* de *liste-d-éléments* différemment. Si vous créez un champ personnalisé de sous-formulaire et que vous ajoutez ce champ conditionnel, vous devez utiliser *field\[ID\]* au lieu de *liste-d-éléments*, où ID est l'identifiant du champ *liste-d-éléments*. Par conséquent, l'attribut *showon* pour ce champ conditionnel que vous créez doit être : `field36:valeur1[OU]field36:valeur2` où 36 est l'identifiant du champ 'Liste d'éléments'.

#### Options d'affichage

- **Classe d'affichage** La classe du conteneur du champ dans la sortie.
- **Classe de la valeur** La classe de la valeur du champ dans la sortie.
- **Étiquette** Afficher l'étiquette lorsque le champ est rendu.
- **Classe de l'étiquette (Sortie)** Classe CSS à appliquer à l'étiquette du champ lorsqu'il est affiché (affichage de la sortie d'un champ).
- **Affichage automatique** Joomla propose certains événements de contenu qui sont déclenchés pendant le processus de création de contenu. C'est ici que vous définissez comment les champs doivent être intégrés dans le contenu. Vous pouvez choisir
  - Après le titre
  - Avant le contenu affiché
  - Après le contenu affiché
  - Ne pas afficher automatiquement
- **Préfixe** Texte fixe à afficher avant un champ, par exemple £.
- **Suffixe** Texte fixe à afficher après un champ, par exemple €.
- **Mise en page** Si une mise en page personnalisée existe, elle serait sélectionnée ici.
- **Afficher en lecture seule** Si le champ est en lecture seule (peut-être que l'utilisateur n'a pas le niveau d'accès), le champ doit-il être affiché ou masqué.

#### Recherche intelligente

- **Index de recherche**  Avertissement : Lorsque *Rendre recherchable* est sélectionné, le contenu du champ est indexé avec les autorisations de visualisation de l'élément de contenu. Cela pourrait entraîner une divulgation d'informations inattendue.

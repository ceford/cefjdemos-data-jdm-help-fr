<!-- Filename: Help4.x:Component:_New_or_Edit_Field_Group  / Display title: Composant : Modifier le groupe de champs -->

## Description

Les groupes de champs sont utilisés pour collecter des champs connexes sous un onglet nommé dans un formulaire de saisie de données. Le composant : Modifier le groupe de champs est similaire pour tous les composants qui implémentent des champs, mais le titre de la page change en fonction du contexte : Articles : Modifier le groupe de champs, Contacts : Modifier le groupe de champs ou Utilisateurs : Modifier le groupe de champs.

### Éléments communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Publication](jdocmanual?article=help/common-elements/edit-publishing).
* [L'onglet Permissions](jdocmanual?article=help/common-elements/edit-permissions).

## Comment Accéder

* Sélectionnez **Contenu → Groupes de Champs** dans le menu Administrateur. Ou...
* Sélectionnez **Contact → Groupes de Champs** dans le menu Administrateur. Ou...
* Sélectionnez **Utilisateurs → Groupes de Champs** dans le menu Administrateur. Ensuite...
  * sélectionnez le bouton **Nouveau** dans la barre d'outils pour créer un nouveau champ. Ou...
  * Sélectionnez un **Titre** dans la liste pour modifier un champ existant.

**Remarque :** Il y a une liste déroulante qui permet la création de Champs pour une 
Catégorie et un Courrier dans le composant Contact. Ils nécessitent une certaine 
expérience en codage pour préparer des substitutions de modèle appropriées.

## Capture d'écran

Cet exemple est une page *Articles : Modifier le groupe de champs*. *Contacts : Modifier le groupe de champs* et *Utilisateurs : Modifier le groupe de champs* sont similaires.

![groupe de champs de modification des articles](../../../fr/images/fields/articles-edit-field-group.png)

## Champs de Formulaire

- **Titre** Le Titre de ce groupe de champs.

### Général

#### Panneau de Gauche

- **Description** Texte qui sera affiché comme une info-bulle lorsque vous passez
  la souris sur la boîte de texte lors de la création d'un article, d'un contact ou d'un
  composant tiers qui supporte les champs personnalisés. Ce texte n'est pas
  traduisible. Vous ne voyez pas cette description dans le Frontend.

#### Panneau de Droite

- **Statut** Le statut de publication de ce groupe de champs.
  - *Publié* Le groupe de champs est visible lors de l'édition d'un article ou d'un
    contact. Et il est visible dans le Frontend.
  - *Non publié* Le groupe de champs ne sera pas visible par les utilisateurs lors de
    l'édition d'un article ou d'un contact.
  - *Archivé* Le groupe de champs n'apparaîtra plus lors de l'édition d'un article
    ou d'un contact. Vous pouvez l'ouvrir dans Groupes de Champs lorsque vous définissez le filtre
    sur archivé.
  - *Supprimé* Le groupe de champs est supprimé mais toujours dans la base de données. Il
    peut être supprimé définitivement de la base de données dans Groupes de Champs avec la
    fonction Vider la Corbeille.
- **Accès** Sélectionnez le niveau d'accès de visualisation pour ce groupe de champs. Les
  niveaux d'accès dépendent de ce qui a été configuré dans Utilisateurs : Niveaux d'Accès.
- **Langue** Sélectionnez la langue pour ce groupe de champs. Si vous n'utilisez pas
  la fonctionnalité multilingue de Joomla, gardez la valeur par défaut *Tous*.
- **Note** Un champ optionnel pour prendre vos notes personnelles pour le groupe
  de champs.

### Options

- **Afficher en Lecture Seule** Si le groupe de champs est en lecture seule (peut-être
  que l'utilisateur n'a pas le niveau d'accès) le groupe de champs doit-il être
  affiché ou masqué.


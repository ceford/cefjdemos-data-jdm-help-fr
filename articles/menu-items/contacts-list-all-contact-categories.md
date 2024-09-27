<!-- Filename: Help4.x:Menu_Item:_List_All_Contact_Categories  / Display title: Liste de toutes les catégories de contacts  -->

## Description

Le type d'élément de menu **Lister Toutes les Catégories dans un Arbre de Catégories de Contacts** est utilisé pour afficher une liste des catégories de contacts au sein d'une catégorie.

### Éléments communs

Certains aspects de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Détails](jdocmanual?article=help/menu-items-common/menu-item-details).
* [L'onglet Catégorie](jdocmanual?article=help/menu-items-common/menu-item-category).
* [L'onglet Dispositions de Liste](jdocmanual?article=help/menu-items-common/menu-item-list-layouts).
* [L'onglet Intégration](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [L'onglet Type de Lien](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [L'onglet Affichage de la Page](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [L'onglet Métadonnées](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [L'onglet Associations](jdocmanual?article=help/common-elements/edit-associations).
* [L'onglet Affectation de Module](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Comment accéder

Pour créer un nouvel élément de menu Liste de toutes les catégories de contact :

- Sélectionnez **Menus → \[nom du menu\]** depuis le menu Administrateur
  (par exemple, **Menus → Menu Principal**).
- Sélectionnez le bouton Nouvel Outil.
- Sélectionnez le bouton Sélectionner le type d'élément de menu. Ensuite...
  - Dans le dialogue modal, sélectionnez l'élément Contacts pour ouvrir une liste, puis
    sélectionnez l'élément **Liste de toutes les catégories de contact**.

Pour modifier un élément de menu existant Liste de toutes les catégories de contact :

- Sélectionnez son titre dans la liste des éléments des menus.

## Capture d'écran

![Élément de menu Contacts Liste Toutes les catégories onglet détails de l'arborescence](../../../fr/images/menu-items/contacts-list-all-categories-tree-details-tab.png)

## Champs de Formulaire

### Onglet Catégories

Les Options des Catégories contrôlent la manière dont les informations 
des catégories sont affichées dans la mise en page. Vous pouvez modifier :

![Onglet Catégories arbre de la liste de tous les contacts des éléments de menu](../../../fr/images/menu-items/contacts-list-all-categories-tree-categories-tab.png)

- **Description de la catégorie de premier niveau** Afficher ou masquer 
  la description de la catégorie de premier niveau ou éventuellement la remplacer 
  par le texte du champ de description trouvé dans l'élément de menu. Si Root est 
  utilisée comme catégorie de premier niveau, le champ de description doit être rempli.
- **Description alternative** Si vous saisissez du texte dans ce champ, il 
  remplacera la description de la catégorie de premier niveau, si elle en a une.
- **Niveaux de sous-catégories** Le nombre de niveaux de sous-catégories à afficher.
- **Catégories vides** Afficher ou masquer les catégories vides. Une catégorie 
  n'est vide que si elle n'a ni Contacts ni sous-catégories.
- **Descriptions des sous-catégories** Afficher ou masquer la description des sous-catégories.
- **\# Contacts dans la catégorie** Afficher ou masquer le nombre de contacts dans une catégorie.

### Onglet Options d'affichage des contacts

Les Options d'affichage des contacts contrôlent l'apparence de la mise en page de la liste.

![Onglet Options d'affichage des contacts arbre de la liste de tous les contacts des éléments de menu](../../../fr/images/menu-items/contacts-list-all-categories-tree-contact-display-options.png)

- **Catégorie des contacts** Afficher ou masquer la vue d'affichage de la catégorie des contacts.
    - *Utiliser Global* Utiliser la valeur par défaut de l'écran des options des contacts.
    - *Masquer* Ne pas afficher le nom de la catégorie des contacts.
    - *Afficher sans lien* Afficher le nom de la catégorie des contacts comme texte stylisé en titre uniquement.
    - *Afficher avec lien* Afficher le nom de la catégorie des contacts comme texte stylisé en titre avec un lien vers la catégorie.
- **Liste de sélection des contacts** Permettre à l'utilisateur d'utiliser une liste déroulante de tous les contacts dans une catégorie de contacts.
- **Nom** Afficher le *Nom* du contact.
- **Tags** Afficher les *Tags* du contact.
- **Informations de contact** Si réglé sur Afficher, les champs suivants sont disponibles :
  - **Position du contact** Afficher ou masquer la *Position du contact*.
  - **Email** Afficher ou masquer l'*Email* du contact.
  - **Adresse de la rue** Afficher ou masquer l'*Adresse de la rue* du contact.
  - **Ville ou banlieue** Afficher ou masquer la *Ville ou banlieue* du contact.
  - **État ou comté** Afficher ou masquer l'*État ou comté* du contact.
  - **Code postal** Afficher ou masquer le *Code postal* du contact.
  - **Pays** Afficher ou masquer le *Pays* du contact.
  - **Téléphone** Afficher ou masquer le *Téléphone* du contact.
  - **Téléphone portable** Afficher ou masquer le *Téléphone portable* du contact.
  - **Fax** Afficher ou masquer le *Fax* du contact.
  - **Page Web** Afficher ou masquer la *Page Web* du contact.
  - **Image** Afficher ou masquer l'*Image* du contact.
- **vCard** Afficher la *vCard* du contact.
- **Informations diverses** Afficher les *Informations diverses* du contact.
- **Articles d'utilisateur** Afficher les *Articles* du contact.
- **\# Articles à lister** Le nombre d'articles du contact à lister.
- **Liens de contact** Afficher ou masquer les *liens supplémentaires* du contact. Ceux-ci peuvent être des liens vers des comptes de réseaux sociaux, tels que Twitter, Facebook, Skype...
- **Étiquette de lien \<lettre\>**. Étiquettes \<A à E\> (5) pour remplacer l'étiquette affichée du lien.

### Onglet Options de courrier

![Onglet Options de courrier arbre de la liste de tous les contacts des éléments de menu](../../../fr/images/menu-items/contacts-list-all-categories-tree-mail-options-tab.png)

- **Formulaire de contact** Afficher ou masquer le *formulaire de contact* du contact.
- **Envoyer une copie au soumettant** Afficher ou masquer une case à cocher 
  pour permettre au soumettant d'envoyer une copie de l'email à lui-même.
- **Vérification de session** Vérifiez l'existence d'un cookie de session. Les utilisateurs sans cookies activés ne pourront pas envoyer d'emails.
- **Réponse personnalisée** Activer ou désactiver la réponse personnalisée au soumettant du formulaire de contact.
- **Redirection de contact** Saisissez une URL alternative pour rediriger le soumettant 
  après l'envoi réussi d'un email via le formulaire de contact.

*Traduit par openai.com*


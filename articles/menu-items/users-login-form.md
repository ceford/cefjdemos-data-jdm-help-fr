<!-- Filename: Help4.x:Menu_Item:_Login_Form  / Display title: Formulaire de Connexion -->

## Description

Le type d'élément de menu **Formulaire de Connexion** est utilisé pour créer une page contenant un formulaire de connexion.

### Éléments Communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Détails](jdocmanual?article=help/menu-items-common/menu-item-details).
* [L'onglet Type de Lien](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [L'onglet Affichage de la Page](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [L'onglet Métadonnées](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [L'onglet Associations](jdocmanual?article=help/common-elements/edit-associations).
* [L'onglet Affectation des Modules](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Comment Accéder

Pour créer un nouvel élément de menu **Formulaire de Connexion** :

- Sélectionnez **Menus → \[nom du menu\]** dans le menu de l'administrateur
  (par exemple, **Menus → Menu Principal**). Ensuite...
  - Sélectionnez le bouton Nouveau dans la barre d'outils. Ensuite...
  - Sélectionnez le bouton Sélectionner le type d'élément de menu.
  - Dans la boîte de dialogue modale, sélectionnez l'élément Utilisateurs pour ouvrir une liste, puis
    sélectionnez l'élément **Formulaire de Connexion**.

Pour modifier un élément de menu Formulaire de Connexion existant :

- Sélectionnez son titre dans la liste *Menus : Élément.*

## Capture d'écran

![Onglet des détails du formulaire de connexion](../../../fr/images/menu-items/users-login-form-details-tab.png)

## Champs de Formulaire

### Onglet Options

![Onglet des détails du formulaire de connexion](../../../fr/images/menu-items/users-login-form-options-tab.png)

#### Panneau de Connexion

- **Choisir le Type de Redirection de Connexion** Cela peut être un *Élément de Menu* ou une *URL Interne*. 
  Les champs suivants changent en fonction du paramètre de ce paramètre. Pour
  un site multilingue, l'*Élément de Menu* est recommandé.
  - **Redirection de Connexion de l'Élément de Menu** Sélectionnez ou créez un élément de menu pour la page
    à laquelle rediriger après une connexion réussie. Si aucun élément de menu n'est sélectionné,
    les utilisateurs seront redirigés vers leur profil après connexion.
  - **Redirection de Connexion** Sélectionnez une URL interne vers laquelle rediriger après la connexion.
- **Description de Connexion** Affichez ou masquez la description de connexion.
- **Texte de Description de Connexion** Entrez le texte à afficher sur la page de Connexion.
- **Image de Connexion** Sélectionnez ou téléchargez une image à afficher sur la page de Connexion.
- **Description de l'Image (Texte Alternatif)** Nécessaire pour les lecteurs d'écran à des fins d'accessibilité.
- **Aucune Description** Une case à cocher pour sélectionner si l'image est purement décorative et
  ne nécessite aucune explication.

#### Panneau de Déconnexion

Ce panneau utilise les mêmes en-têtes de champ pour contrôler le processus de déconnexion.

## Conseils

- L'**URL de Connexion et de Déconnexion** peut être utilisée pour envoyer un utilisateur vers une page spécifique créée pour fournir des commentaires à l'utilisateur. Par exemple, une page intitulée *Vous êtes maintenant connecté* avec des informations générales. L'utilisation d'un Module Utilisateur pour afficher des liens pour Mettre à Jour le Profil Utilisateur, Voir le Profil Utilisateur et d'autres fonctions Utilisateur pourrait être affichée sur cette page, améliorant ainsi l'expérience de l'utilisateur sur le site.

*Traduit par openai.com*


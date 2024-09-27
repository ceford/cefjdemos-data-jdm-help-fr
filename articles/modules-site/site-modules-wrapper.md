<!-- Filename: Help4.x:Site_Modules:_Wrapper / Display title:  Modules : Fenêtre intégrée (IFrame) -->

## Description

Le type de module *Wrapper* vous permet d'afficher un site web externe dans un module. La fonctionnalité est la même que celle de la *iFrame Wrapper* que vous pouvez ajouter en tant qu'élément de menu. Si la page à laquelle le wrapper est lié est plus grande que le cadre, des barres de défilement verticales et horizontales seront affichées.

### Éléments Communes

Certains éléments de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Le Modules: Onglet Modules](jdocmanual?article=help/modules/modules-module-tab).
* [Le Modules: Onglet Affectation du Menu](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Le Modules: Onglet Avancé](jdocmanual?article=help/modules/modules-advanced-tab).
* [L'onglet Permissions](jdocmanual?article=help/common-elements/edit-permissions).

## Comment Accéder

- Sélectionnez **Système → Gérer le Panneau → Modules du Site** dans le
  menu de l'Administrateur. Puis...
  - Pour créer un nouveau module : sélectionnez le bouton **Nouveau** dans la Barre d'outils. Puis...
    - Sélectionnez le type de module requis.
  - Pour modifier un module existant :
    - Trouvez le module dans la liste des modules installés et sélectionnez le
      lien de titre dans la colonne **Titre**.

## Capture d'écran

![onglet du module wrapper](../../../fr/images/modules-site/modules-wrapper-module-tab.png)

## Champs de formulaire

- **Titre** Le titre du module. C'est aussi le titre affiché
  pour le module en fonction du champ de formulaire *Afficher le titre*.

### Onglet Module

#### Panneau de gauche

- **URL** URL du site ou du fichier que vous souhaitez afficher dans l'iframe.
- **Ajout automatique** Par défaut, http:// sera ajouté sauf s'il détecte 
  http:// ou https:// dans l'URL que vous fournissez. Cela vous permet
  de désactiver cette fonctionnalité.
- **Barres de défilement** Afficher ou masquer les barres de défilement horizontales et verticales.
- **Largeur** Largeur de la fenêtre iFrame. Vous pouvez entrer une valeur 
  absolue en pixels ou une valeur relative en ajoutant un %.
- **Hauteur** Hauteur de la fenêtre iFrame.
- **Hauteur automatique** La hauteur sera automatiquement définie en fonction de la taille de la 
  page externe. Cela ne fonctionnera que pour les pages de votre propre domaine.
- **Bordure de cadre** Afficher une bordure de cadre autour de l'iframe.
- **Nom de la cible** Nom de l'iFrame lorsqu'il est utilisé comme cible.

*Traduit par openai.com*


<!-- Filename: Help4.x:Site_Modules:_Menu / Display title: Modules: Menu -->

## Description

Ce type de module *Menu* vous permet de placer un menu à la position désirée et sur les pages web souhaitées. Un site web peut avoir plus d'un menu sur une seule page et différents menus sur différentes pages web.

### Éléments communs

Certains éléments de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Modules : Modules](jdocmanual?article=help/modules/modules-module-tab).
* [L'onglet Modules : Assignation de menu](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [L'onglet Modules : Avancé](jdocmanual?article=help/modules/modules-advanced-tab).
* [L'onglet Permissions](jdocmanual?article=help/common-elements/edit-permissions).

## Comment y accéder

- Sélectionnez **Système → Panneau de gestion → Modules de site** dans le menu d'administration. Ensuite...
  - Pour créer un nouveau module : sélectionnez le bouton **Nouveau** dans la barre d'outils. Ensuite...
    - Sélectionnez le type de module requis.
  - Pour modifier un module existant :
    - Trouvez le module dans la liste des modules installés et sélectionnez le lien de titre dans la colonne **Titre**.

## Capture d'écran

![onglet module menu](../../../fr/images/modules-site/modules-menu-module-tab.png)

## Champs du formulaire

- **Titre** Le titre du module. C'est également le titre affiché pour le module selon le champ de formulaire *Afficher le titre*.

### Onglet Module

#### Panneau gauche

- **Sélectionner le menu** Sélectionnez un menu dans la liste des menus disponibles.
- **Élément de base** Sélectionnez un élément de menu à utiliser toujours comme base pour l'affichage du menu. Vous devez définir le Niveau de départ au même niveau ou à un niveau supérieur à celui de l'élément de base. Cela fera en sorte que le module soit affiché sur toutes les pages assignées. Si *Actuel* est sélectionné, l'élément actif actuellement est utilisé comme base. Cela fait que le module ne s'affiche que lorsque l'élément parent du menu est actif.
- **Niveau de départ** Niveau à partir duquel commencer à afficher le menu. Définir les niveaux de départ et de fin au même numéro et régler *Afficher les éléments de sous-menu* sur *Afficher* n'affichera que ce niveau unique.
- **Niveau de fin** Niveau à partir duquel arrêter l'affichage du menu. Si vous choisissez *Tous*, tous les niveaux seront affichés en fonction du paramètre *Afficher les éléments de sous-menu*.
- **Éléments de sous-menu** Afficher ou masquer les éléments de sous-menu.

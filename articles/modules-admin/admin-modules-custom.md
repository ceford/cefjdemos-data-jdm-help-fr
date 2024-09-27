<!-- Filename: Help4.x:Admin_Modules:_Custom  / Display title: Modules : Personnalisé -->

## Description

Le type de module *Custom* vous permet de créer une unité HTML autonome et de la placer ensuite à n'importe quel endroit valide sur une page.

Il existe de nombreux cas où du HTML en format libre peut être affiché dans l'interface administrateur. Par exemple, un message système temporaire pourrait être affiché en haut de toutes les pages de l'administrateur (position customtop). Un style supplémentaire peut être requis via l'onglet Avancé.

### Éléments Communs

Certains éléments de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Les Modules : Onglet Module](jdocmanual?article=help/modules/modules-module-tab).
* [Les Modules : Onglet Avancé](jdocmanual?article=help/modules/modules-advanced-tab).
* [L'Onglet des Permissions](jdocmanual?article=help/common-elements/edit-permissions).

## Comment accéder

- Sélectionnez **Système → Gérer le panneau → Modules administrateur** dans le
  menu Administrateur. Ensuite...
  - Pour créer un nouveau module : sélectionnez le bouton **Nouveau** dans la barre d'outils.
    Ensuite...
    - Sélectionnez le type de module requis.
  - Pour modifier un module existant :
    - Trouvez le module dans la liste des modules installés et sélectionnez le
      lien du titre dans la colonne **Titre**.

## Capture d'écran

![modules articles dernier onglet](../../../fr/images/modules-admin/modules-custom-module-tab.png)

## Champs de formulaire

- **Titre** Le titre du module. C'est également le titre affiché
  pour le module en fonction du champ de formulaire *Afficher le Titre*.

### Onglet du Module

#### Panneau de gauche

- **Éditeur** Les filtres de texte Joomla et l'éditeur TinyMCE ne permettent pas chacun
  l'entrée de certaines balises HTML.
  - Les filtres de texte peuvent être configurés dans l'onglet *Filtres de texte* de la Configuration Globale. Par exemple, par défaut, les groupes d'utilisateurs Invité, Public et Enregistré ne sont pas autorisés à entrer de l'html dans les champs de formulaire.
  - Les filtres TinyMCE peuvent être configurés dans son plugin. Par défaut, il interdit
    l'entrée des balises script, applet et iframe.

*Traduit par openai.com*


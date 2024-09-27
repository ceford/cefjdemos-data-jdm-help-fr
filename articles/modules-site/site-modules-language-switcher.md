<!-- Filename: Help4.x:Site_Modules:_Language_Switcher  / Display title: Modules: Changeur de langue -->

## Description

Le type de module *Switcher de Langue* vous permet de basculer entre les langues de contenu disponibles. Sélectionner une langue vous emmènera à la page correspondante pour cette langue.

### Éléments Courants

Certains éléments de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Les Modules : Onglet Modules](jdocmanual?article=help/modules/modules-module-tab).
* [Les Modules : Onglet Affectation de Menu](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Les Modules : Onglet Avancé](jdocmanual?article=help/modules/modules-advanced-tab).
* [L'Onglet Permissions](jdocmanual?article=help/common-elements/edit-permissions).

## Comment accéder

- Sélectionnez **Système → Gérer Panneau → Modules du Site** depuis le
  menu Administrateur. Ensuite...
  - Pour créer un nouveau module : sélectionnez le bouton **Nouveau** dans la barre d'outils. Ensuite...
    - Sélectionnez le type de module requis.
  - Pour modifier un module existant :
    - Trouvez le module dans la liste des modules installés et sélectionnez le lien du titre dans la colonne **Titre**.

## Capture d'écran

![onglet du module de changement de langue](../../../fr/images/modules-site/modules-language-switcher-module-tab.png)

## Champs de Formulaire

- **Titre** Le titre du module. C'est aussi le titre affiché
  pour le module en fonction du champ de formulaire *Afficher le titre*

### Onglet Module

#### Panneau de Gauche

- **Texte préalable** C'est le texte ou HTML qui est affiché au-dessus
  du sélecteur de langue.
- **Texte postérieur** C'est le texte ou HTML qui est affiché en dessous du
  sélecteur de langue.
- **Utiliser le menu déroulant** Les trois éléments suivants changent pour *Oui* et *Non*
  - **Non**
    - **Utiliser des drapeaux d'image** Si réglé sur *Oui*, afficher le choix de langue
    sous forme de drapeaux d'image. Sinon, utiliser les noms natifs des langues de contenu. 
    Si réglé sur *Non*, un champ supplémentaire apparaît : **Noms complets des langues**, 
    qui affiche un code de langue à deux caractères en majuscules pour chaque langue.
    - **Langue active** Afficher ou non la langue active.
    Si affichée, la classe `lang-active` sera ajoutée à l'élément.
    - **Affichage horizontal** Par défaut, réglé sur *Oui*, c'est-à-dire
    créer un affichage en liste horizontale. Régler sur *Non* pour une liste verticale.
  - **Oui** L'élément *Langue active* est affiché sélectionné.
    - **Utiliser des drapeaux pour le menu déroulant** Si réglé sur *Oui*, le drapeau de la langue
      est placé avant le nom de la langue dans la liste déroulante.
    - **Noms complets des langues** Si réglé sur *Non*, afficher un code de langue à
      deux caractères en majuscules pour chaque langue.
    - **Langue active** Aucun effet dans la liste déroulante.

*Traduit par openai.com*


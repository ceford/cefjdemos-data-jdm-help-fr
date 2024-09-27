<!-- Filename: Help4.x:Menu_Item:_Iframe_Wrapper  / Display title: Conteneur d'Iframe -->

## Description

Le type d'élément de menu *Iframe Wrapper* est utilisé pour créer une page avec un contenu intégré en utilisant un IFrame avec un contrôle de la taille, de la largeur et de la hauteur de l'iframe.

### Éléments Communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Détails](jdocmanual?article=help/menu-items-common/menu-item-details).
* [L'onglet Type de Lien](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [L'onglet Affichage de la Page](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [L'onglet Métadonnées](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [L'onglet Associations](jdocmanual?article=help/common-elements/edit-associations).
* [L'onglet Attribution de Module](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Comment Accéder

Pour créer un nouvel Élément de Menu IFrame Wrapper :

- Sélectionnez **Menus → \[nom du menu\]** dans le menu Administrateur
  (par exemple, **Menus → Menu Principal**). Puis...
  - Sélectionnez le bouton **Nouveau** dans la barre d'outils. Puis...
  - Sélectionnez le bouton Sélectionner le Type d'Élément de Menu.
  - Dans le dialogue modal, sélectionnez l'élément Utilisateurs pour ouvrir une liste, puis
    sélectionnez l'élément de menu **IFrame Wrapper**.

Pour modifier un élément de menu *IFrame Wrapper* existant :

- Sélectionnez son Titre dans la liste *Menu : Éléments*.

## Capture d'écran

![Onglet de détails de l'encapsuleur d'iframe](../../../fr/images/menu-items/wrapper-iframe-wrapper-details-tab.png)

## Champs de Formulaire

### Onglet des Paramètres de la Barre de Défilement

![Onglet des paramètres de la barre de défilement du wrapper Iframe](../../../fr/images/menu-items/wrapper-scroll-bar-parameters-tab.png)

- **Largeur** Largeur de la fenêtre IFrame. Entrez un nombre de pixels ou un
  pourcentage. Par exemple, *550* signifie 550 pixels ; *75%* signifie 75% de la
  largeur du conteneur `<main>`. Un nombre absolu de pixels peut être plus large que
  le conteneur et causer des problèmes de mise en page. En cas de doute, essayez 100%.
- **Hauteur** Hauteur de la fenêtre IFrame. Entrez un nombre de pixels. Par exemple,
  *550* signifie 550 pixels.

### Onglet Avancé

![Onglet avancé du wrapper Iframe](../../../fr/images/menu-items/wrapper-advanced-tab.png)

- **Hauteur automatique** Définir automatiquement la hauteur à celle de la page externe.
  *Remarque* - cela ne fonctionnera que si la page externe se trouve sur le **même
  domaine**. Par exemple, `http://www.example.com`, le fichier HTML externe doit
  être dans la structure de fichiers racine de `example.com`. Les sous-domaines ne fonctionneront pas,
  car un sous-domaine est considéré comme un domaine distinct.
- **Ajout automatique** Préfixer automatiquement l'adresse Web avec http://. Cette
  fonctionnalité détectera automatiquement et ne préfixera pas une URL avec http:// ou
  https:// si elle est déjà utilisée dans l'URL.
- **Chargement paresseux** ...

*Traduit par openai.com*


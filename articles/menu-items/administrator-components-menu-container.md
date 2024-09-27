<!-- Filename: Help4.x:Menu_Item:_Components_Menu_Container  / Display title: Élément du menu : Conteneur du menu des composants -->

## Description

Le menu des composants Conteneur est utilisé pour afficher un conteneur de composants dans l'interface Administrateur. Un cas d'utilisation pourrait être le suivant :

Supposons que vous souhaitiez montrer à certains utilisateurs uniquement des liens vers un sous-ensemble des composants de votre site. Les Super Utilisateurs verront bien sûr des liens vers tout. Vous pouvez faire cela de la manière suivante :

- Créez un nouveau Groupe d'utilisateurs nommé, disons, Branche, avec Public pour parent.
- Définissez les permissions globales de ce groupe pour permettre la connexion en tant qu'administrateur.
- Créez un nouveau menu nommé, disons, Menu Branche sans présélections importées.
- Créez un module lié nommé, disons, Menu Branche avec un menu à afficher comme Menu Branche. Définissez Vérifier le Menu sur Non et Accès sur Public.
- Créez un élément de menu Conteneur de Menu des Composants pour le Menu Branche nommé, disons, Composants de la Branche.
  - Cachez les composants que vous ne souhaitez pas que les utilisateurs de la Branche voient.
  - Affichez ceux auxquels ils devraient avoir accès.
- Définissez les permissions des composants pour le groupe Branche à permises pour tous sauf Configurer ACL et Configurer les Options.

Pour un Super Utilisateur, le menu Administrateur aura une duplication évidente des liens. Cependant, un utilisateur de la Branche ne verra que le menu Composants de la Branche et le Tableau de Bord Accueil. Vous devrez également ajuster les permissions d'accès des modules de l'icône rapide là-bas ! Et vous devez vraiment créer un module Tableau de Bord pour tous les composants auxquels les utilisateurs de la Branche ont accès.

Pour les utilisateurs qui ont besoin d'accéder aux Articles, vous pouvez ajouter plus d'éléments de menu au Menu Branche. De cette manière, vous pouvez construire un menu personnalisé complet pour les utilisateurs de la Branche.

### Éléments Communs

Certains aspects de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Type de Lien](jdocmanual?article=help/menu-items-common/menu-item-link-type).

## Comment Accéder

Pour créer un nouvel Élément de Menu Conteneur de Composants :

- Créez un nouveau menu depuis **Menus → Gérer** dans le menu Administrateur.
  - Sélectionnez **Administrateur** dans le sélecteur déroulant *Site/Administrateur*.
  - Sélectionnez le bouton **Nouveau** dans la barre d'outils. Remplissez le formulaire :
    - **Titre** Menu de Branche
    - **Nom Unique** menu_branche
    - **Description** Menu personnalisé pour la Branche.
    - **Preset d’Importation** Aucun
    - **Enregistrer**
    - **Permissions** Sélectionnez le groupe *Branche* et définissez tout à *Autoriser*.
    - **Enregistrer & Fermer**
    - Sélectionnez le bouton **Créer un Module** et remplissez le formulaire dialogue :
    - **Titre** Composants de Branche
    - **Vérifier le Menu** Non (sinon, il y aura un message vous invitant à 
      *activer le mode de récupération du menu*.)
    - **Accès** Spécial
    - **Position** Menu
- Sélectionnez **Menus → \[nom du menu\]** dans le menu Administrateur.
- Sélectionnez le bouton **Nouveau** dans la barre d'outils pour créer un nouvel élément de menu.
- Sélectionnez le bouton **Sélectionner** pour le Type d'Élément de Menu.
- Sélectionnez le lien **Liste des Conteneurs de Composants** depuis **Liens Système** dans
  la boîte de dialogue modale de Type d'Élément de Menu.

Pour modifier un Élément de Menu Conteneur de Composants existant, sélectionnez son titre dans
la liste des Élément de Menu.

## Capture d'écran

![Éléments de menu Conteneur du menu Composants](../../../en/images/menu-items/administrator-components-menu-container.png)

## Champs de formulaire

- **Nom** Le nom de l'élément de menu, par exemple *Menu de filiale*. Il apparaîtra 
  en bas du menu Administrateur.
- **Alias** Le nom interne de l'élément. Normalement, vous pouvez laisser ce 
  champ vide et Joomla remplira une valeur par défaut: Titre en minuscules et 
  avec des tirets à la place des espaces.

### Onglet Détails

#### Panneau de gauche

- **Type d'élément de menu** Dans ce cas *Conteneur de menu des composants*.
- **Afficher ou masquer les éléments de menu** Liste des éléments de menu avec des boutons pour définir 
  le statut de visibilité. Si un élément parent est défini comme *Masqué*, tous les éléments 
  enfants sont également masqués, même s'ils sont définis comme *Afficher*.

#### Panneau de droite

- **Menu** Indique dans quel menu apparaîtra le lien.
- **Parent** L'élément (catégorie, élément de menu, etc.) qui est le 
  parent de l'élément en cours d'édition.
- **Ordre** Indique l'ordre de cet élément de menu dans le menu. L'ordre 
  par défaut est d'ajouter l'élément de menu à la fin du menu. Cet élément 
  de menu sera déplacé à la position d'ordre juste après l'élément de menu 
  sélectionné dans la liste déroulante. Notez que l'ordre des éléments de 
  menu peut également être modifié dans le gestionnaire d'éléments de menu.
- **Statut** Le statut de publication de l'élément.
- **Note** Ceci est normalement pour l'utilisation de l'administrateur du site 
  (par exemple, pour documenter des informations sur cet élément) et ne s'affiche pas 
  dans le frontend du site.


## Conseils

- L'élément **Composants de Branche** apparaît en bas du menu Administrateur. L'accès au menu principal Administrateur et à cette section peut être personnalisé pour le groupe de Branche.

*Traduit par openai.com*


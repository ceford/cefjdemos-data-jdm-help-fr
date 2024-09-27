<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Tour  / Display title: Visites Guidées : Modifier la Visite -->

## Description

Cette page est utilisée pour ajouter une nouvelle visite ou modifier une visite existante. Une visite doit 
comprendre au moins une étape. Une fois qu'une visite a été nouvellement créée, allez à la liste des visites 
et sélectionnez le bouton avec le label *0* dans la colonne des Étapes. La première 
étape de la visite est automatiquement créée à partir du titre et de la description de la visite.

### Éléments Communs

Certains aspects de cette page sont traités dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Publication](jdocmanual?article=help/common-elements/edit-publishing).

## Comment accéder

- Sélectionnez **Système -> Gérer -> Visites guidées** dans le menu Administrateur.
- Sélectionnez le bouton de la barre d'outils **Nouveau** pour ajouter une visite.
- Sélectionnez un **Titre** dans la liste pour modifier une visite.

## Capture d'écran

![Éditer la visite guidée](../../../fr/images/guided-tours/guided-tours-edit-tour.png)


## Champs de formulaire

- **Titre** Le titre de cette visite. Si le titre est une clé de langue, un champ supplémentaire est affiché, représentant la traduction de cette clé pour la langue de l'utilisateur.
- **Identifiant de la visite** Un identifiant unique pour la visite. Lors de l'**Enregistrement**, ou **Enregistrement en tant que copie**, une valeur est fournie par défaut. Un format suggéré serait *nomdelauteur-nomdelavisite*, *nomdelasociété-nomdelavisite* ou *domaine-nomdelavisite*. Cet identifiant a plusieurs objectifs : démarrer une visite depuis n'importe où (et pas seulement depuis le module Visites Guidées), différencier les visites provenant d'origines différentes, et sur les sites multilingues, il dicte la structure des noms de fichiers de langue.

### Onglet Modifier la visite

#### Panneau de gauche

- **URL relative** Le chemin relatif obligatoire à partir d'où la visite commence. Par exemple, pour démarrer une visite à partir de la page de la visite, entrez `administrator/index.php?option=com_guidedtours&view=tours`.
- **Description** C'est ici que vous entrez la description de la visite. La description de la visite peut être une clé de langue. Lorsque c'est le cas, un champ secondaire présente la description traduite de cette clé pour la langue de l'utilisateur.

#### Panneau de droite

- **Sélecteur de composant** La visite sera visible en priorité sur les pages des extensions sélectionnées. Utilisez *Tout* pour afficher la visite sur toutes les pages. Lorsqu'elle est définie sur *Tout*, la visite est placée en dernier dans la liste des visites contextuelles du menu déroulant du module. Ceci est un champ obligatoire.
- **Démarrage automatique** Permet à la visite de démarrer automatiquement lorsqu'un utilisateur atteint le contexte dans lequel la visite doit être affichée.

## Conseils

- Il existe 2 méthodes pour insérer une image dans la description de la visite à l'aide de l'éditeur TinyMCE.
  1. La liste déroulante **CMS Contenu** donne accès à l'écran **Médias** qui vous permet de parcourir les fichiers d'images et de télécharger des images.
  2. La liste déroulante *Insérer* est un formulaire simple pour lequel vous devez connaître l'URL de l'image. Elle est utilisée pour les images externes.
- Il existe 2 façons de créer des visites pour des environnements multilingues :
  1. Créer une visite pour chaque langue prise en charge.
  2. Créer une seule visite pour toutes les langues et utiliser des clés de langue pour le titre et la description.
- Utilisez **GUIDEDTOUR** dans les clés de langue comme convention partout où des clés de langue sont utilisées (pour le titre et la description).

*Traduit par openai.com*


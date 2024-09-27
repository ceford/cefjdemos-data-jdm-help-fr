<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Step  / Display title: Visites Guidées : Modifier l'Étape -->

## Description

Cette page est utilisée pour ajouter une nouvelle Étape ou modifier une Étape existante d'un tour.

### Éléments Communs

Certains aspects de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Publication](jdocmanual?article=help/common-elements/edit-publishing).

## Comment accéder

- Sélectionnez **Système -> Gérer -> Visites guidées** dans le menu Administrateur.
- Sélectionnez le bouton **Étapes** numéroté pour une visite pour ouvrir la page des étapes de la visite.
- Sélectionnez le bouton de la barre d'outils **Nouveau** pour ajouter une étape.
- Sélectionnez un **Titre** dans la liste pour modifier une étape.

## Capture d'écran

![Étape d'édition des visites guidées](../../../fr/images/guided-tours/guided-tours-edit-step.png)

## Champs de Formulaire

- **Titre** Le titre de cette étape. Il s'agit généralement d'un appel à l'action, par exemple `Entrez un titre` si l'étape requiert une interaction de l'utilisateur. Si le titre est une clé de langue, un champ additionnel est affiché représentant la traduction de cette clé pour la locale de l'utilisateur.

### Onglet Modifier l'Étape

#### Panneau Gauche

- **Description** C'est ici que vous entrez la description de l'étape, généralement une explication détaillée ou une aide pour l'étape. La description de l'étape peut être une clé de langue. Dans ce cas, un champ secondaire présente la description traduite de cette clé pour la locale de l'utilisateur.

#### Panneau Droit

- **Position** La position de l'étape par rapport à l'information à laquelle elle fait référence.
  - **En bas** L'étape s'affiche en dessous de la cible.
  - **Centre** L'étape s'affiche au centre de l'écran. Lorsqu'une cible est manquante, ceci est la position par défaut.
  - **Gauche** L'étape s'affiche à gauche de la cible.
  - **Droite** L'étape s'affiche à droite de la cible.
  - **En haut** L'étape s'affiche au-dessus de la cible.
- **Cible** L'élément de l'écran que l'étape pointe. Il utilise la syntaxe CSS.

  Par exemple, *.button-new* ciblera le bouton de la page ayant la classe *button-new*.

  Si la cible n'est pas unique, la première cible trouvée est utilisée. Lors de la création d'étapes interactives, assurez-vous que la cible est focalisable pour l'accessibilité. Vous pouvez utiliser plusieurs sélecteurs, séparés par des virgules. Le premier valide deviendra la cible (un sélecteur est valide s’il est trouvé sur la page, non désactivé, non en lecture seule et non caché). Si une cible a été définie mais qu'elle n'est pas trouvée ou qu'elle est invalide, le tour ne sera pas interrompu mais affichera l'étape au centre de l'écran.
- **Type** Le type d'étape.
  - **Suivant** L'utilisateur effectuant le tour passera à l'étape suivante.
  - **Redirection** L'étape sera redirigée vers une autre page.
  - **Interactif** L'étape requiert une interaction de l'utilisateur, comme saisir des données.
- **URL** L'URL vers laquelle rediriger pour une étape de type *Redirection*. Par exemple, *administrator/index.php?option=com_users&view=user&layout=edit* redirigera l’étape vers l'écran d'édition de l'utilisateur.
- **Type Interactif** Le type d'interaction pour une étape interactive.
  - **Soumettre le Formulaire** La cible est un bouton qui soumet un formulaire.
  - **Champ de Texte** La cible est un champ de texte. Si le champ est obligatoire, la personne effectuant le tour ne pourra pas passer à l'étape suivante tant que des données ne seront pas entrées.
  - **Bouton** La cible est un bouton sur l'écran.
  - **Autre** La cible est tout autre élément de formulaire.

### Onglet Options

![Onglet des options d'édition des étapes des visites guidées](../../../fr/images/guided-tours/guided-tours-edit-step-options-tab.png)

## Conseils

- Utilisez **GUIDEDTOUR** dans les clés de langue comme convention partout où les clés de langue sont utilisées (pour le titre et la description).

*Traduit par openai.com*


<!-- Filename: Help4.x:Banners:_Edit  / Display title: Bannières : Modifier -->

## Description

Utilisé pour ajouter ou modifier des bannières qui peuvent être affichées sur votre site Joomla! N'oubliez pas de créer au moins un Client de Bannière et une Catégorie de Bannière avant de créer des Bannières.

### Éléments Communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Publication](jdocmanual?article=help/common-elements/edit-publishing).
* [Le Popup de l'Historique des Versions](jdocmanual?article=help/common-elements/edit-version-history).

## Comment Accéder

Depuis le menu Administrateur :
- Sélectionnez **Composants → Bannières** pour aller à la page de la liste des Bannières.
- Sélectionnez le bouton **Nouveau** dans la Barre d'outils pour créer une nouvelle Bannière.
- Sélectionnez un **nom** de Bannière dans la colonne *Nom* pour modifier une Bannière existante.

## Capture d'écran

Une bannière peut être une image cliquable ou un code personnalisé. Le type d'image est
montré dans la capture d'écran ci-dessous. Le type personnalisé remplace la boîte de sélection
d'image par une zone de texte pour le code.

![Onglet de modification des détails des bannières](../../../fr/images/banners/banners-edit-details-tab.png)

## Champs de formulaire

- **Nom** Le nom de la Bannière. C'est le nom qui s'affichera dans la colonne *Nom* de la liste des Bannières.
- **Alias** Le nom interne de l'élément. Normalement, vous pouvez laisser ce champ vide et Joomla remplira une valeur par défaut dérivée du Nom mais en minuscules et avec des tirets à la place des espaces.

## Onglet Détails

### Panneau de Gauche

- **Type** Le type de bannière à afficher. Les options sont un fichier image ou
  du code HTML personnalisé.
  - **Image** Fichier image à afficher pour la bannière. Cliquez sur le bouton *Sélectionner*
    pour parcourir et sélectionner le fichier image à utiliser. Utilisez la page Médias
    pour télécharger les fichiers image des Bannières sur votre site. Les images des Bannières
    doivent être situées dans le répertoire /images/banners/.
    - **Largeur** La largeur fixe pour redimensionner l'image de la bannière. Laissez
      ce champ vide si vous voulez utiliser la largeur réelle du fichier image de la bannière.
    - **Hauteur** La hauteur fixe pour redimensionner l'image de la bannière. Laissez
      ce champ vide si vous voulez utiliser la hauteur réelle du fichier image de la bannière.
    - **Texte Alternatif** Texte à afficher à la place de l'image de la bannière
      dans le cas où l'image ne peut pas être affichée.
    - **Texte Alternatif** Texte alternatif pour l'image de la Bannière.
  - **Personnalisé** Sélectionnez Personnalisé si vous souhaitez entrer un code personnalisé pour
    votre bannière.
    - **Code Personnalisé** Utilisez {CLICKURL} et {NAME} pour fusionner respectivement les valeurs 'Cliquer URL'
      et 'Nom' dans votre code personnalisé. Par exemple:<br>
      `<a href=`&#34;`{CLICKURL}"><img src=`&#34;`entrez l'URL de l'image" alt="{NAME}" title="{NAME}"></a>`.
      Une autre option est d'entrer un code HTML personnalisé. Par exemple:<br>
      `<div class="yourclass"><a href=`&#34;`https://votredomaine.com"><img src=`&#34;`chemindevotreimage"></a></div>`
- **URL de Clic** L'URL vers laquelle naviguer lorsque l'utilisateur clique sur la
  Bannière.
- **Description** Entrez une description pour la Bannière.

### Panneau de Droite

- **Statut** Le statut publié de l'élément.
- **Épinglé** Si la Bannière est *épinglée* ou non. Si une
  ou plusieurs Bannières dans une Catégorie sont désignées *épinglées*, elles auront
  priorité sur les Bannières qui ne le sont pas.
    - Par exemple, si deux Bannières dans une Catégorie sont épinglées et qu'une troisième Bannière
    ne l'est pas, la troisième Bannière ne s'affichera pas si le paramètre du module d'affichage de Bannières est *Épinglé, Aléatoire* ou *Épinglé, Ordre*. Seules les deux Bannières épinglées seront affichées. Si les bannières épinglées ont un nombre fixe d'impressions, une fois ces impressions épuisées, les bannières épinglées ne seront plus affichées et les bannières non épinglées commenceront à être affichées automatiquement.
- **Langue** Langue de l'élément.
- **Note de Version** Champ optionnel pour identifier cette version de l'élément
  dans la fenêtre Historique des Versions de l'élément.

### Onglet Détails de la Bannière

![Onglet des détails d'édition des bannières](../../../fr/images/banners/banners-edit-banner-details-tab.png)

- **Impressions Max.** Le nombre d'Impressions achetées pour cette
  Bannière. Les impressions sont le nombre de fois qu'une Bannière sera affichée
  sur une page. Cochez la case 'Illimité' si un nombre illimité d'Impressions est autorisé.
- **Impressions Totales** Le nombre de fois que cette Bannière a été
  affichée sur une page web pour un utilisateur. Aucune entrée n'est autorisée. Vous pouvez réinitialiser
  ce nombre à 0 en appuyant sur le bouton 'Réinitialiser les impressions'.
- **Clics Totals** Le nombre de fois que cette Bannière a été cliquée. Aucune
  entrée n'est autorisée. Vous pouvez réinitialiser ce nombre à 0 en appuyant sur le
  bouton *Réinitialiser les clics*.
- **Client** Le Client pour cette Bannière. Sélectionnez-en un dans la liste déroulante
  des Clients existants.
- **Type d'Achat:** Le type d'achat de la bannière. Cela est utilisé pour
  indiquer comment le client de la bannière a acheté le temps d'affichage pour la
  bannière.
- **Suivi des Impressions** Indiquez si oui ou non le nombre de fois que la
  bannière est affichée aux visiteurs du site web doit être suivi.
- **Suivi des Clics** Indiquez si oui ou non le nombre de fois que la
  bannière est cliquée par les visiteurs du site web doit être suivi.

## Conseils

- Les bannières sont placées sur des pages spécifiques en ajoutant des modules de type *Bannières* en utilisant la liste des Modules.
- Si vous avez une série de bannières que vous souhaitez afficher sur une ou plusieurs pages dans un ordre aléatoire :
  1.  Créez les bannières que vous souhaitez inclure, en vous assurant qu'elles ont le même client et la même catégorie.
  2.  Créez un module de bannière pour ce client et cette catégorie, et dans l'assignation du menu, choisissez les sélections de menu pour lesquelles le module doit s'afficher.
  3.  Dans le module de bannière, définissez la valeur *Randomise* sur *Sticky, Randomise*.

  Avec ces paramètres, les différentes bannières pour ce client et cette catégorie s'afficheront sur les pages sélectionnées dans un ordre aléatoire.


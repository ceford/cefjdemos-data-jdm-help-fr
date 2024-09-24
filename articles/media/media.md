<!-- Filename: Help4.x:Media / Display title: Média -->

## Description

Le composant Médias est un outil de gestion des fichiers dans le dossier d'images et d'autres dossiers locaux définis par l'utilisateur. Les actions disponibles incluent :

- Téléverser une nouvelle image (ou un document)
- Supprimer une image existante
- Renommer une image
- Modifier une image
- Obtenir un lien vers une image
- Créer un nouveau dossier

### Éléments communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).

## Comment y accéder

- **Tableau de bord principal → Site → Médias**.

## Capture d'écran

![Médias](../../../fr/images/media/media.png)

## Zone d'affichage des images

### Local

Cette zone affiche la structure des dossiers locaux du site, par défaut le dossier *images*.

Le dossier actuellement sélectionné est affiché dans les *Fil d'Ariane* au-dessus de la zone d'affichage des images.

### Barre supérieure

- **Case à cocher** Sélectionner ou désélectionner toutes les images. Après la sélection, les images individuelles peuvent être désélectionnées.
- **Fil d'Ariane** Sélectionnez un élément du fil d'Ariane pour revenir dans la hiérarchie des dossiers.
- **Recherche** Tapez une partie du nom d'une image dans la zone de recherche. Le filtre fonctionne de manière progressive : par exemple, entrer la lettre `k` réduira instantanément les images affichées à celles contenant un `k`.
- **Icônes de loupe** Diminuez ou augmentez la taille visible des vignettes.
- **Icônes Vue Liste ou Vue Vignette** Basculer entre les vues Vignette et Liste – l'icône change en conséquence.
- **Icône d'information** Affiche les informations sur l'élément sélectionné. Si une image est sélectionnée, elle montrera le nom du fichier, le chemin du dossier, la taille et d'autres propriétés. Sélectionnez pour ouvrir ou fermer le panneau d'information.

### Actions

Survolez une image et sélectionnez le bouton de menu étiqueté avec une ellipse (...). Six icônes apparaissent offrant les actions suivantes :

1.  **Aperçu** Sélectionnez l'icône de loupe - l'image s'affiche en taille réelle dans une boîte de dialogue.
2.  **Modifier** Sélectionnez l'icône de crayon pour ouvrir la fenêtre d'édition des médias. Cela permet de recadrer, redimensionner ou faire pivoter l'image.
3.  **Télécharger** Sélectionnez l'icône de téléchargement - votre ordinateur vous demandera ce que vous souhaitez faire avec le fichier. Il peut simplement l'enregistrer ou l'ouvrir dans une application d'affichage d'image.
4.  **Obtenir un lien partageable** Sélectionnez l'icône de lien pour obtenir un lien vers l'image à partager. Une boîte de dialogue vous permet de copier le lien dans le presse-papiers pour le coller dans un e-mail ou un document.
5.  **Renommer** Sélectionnez l'icône de renommage pour ouvrir une boîte de dialogue permettant de renommer l'image.
6.  **Supprimer** Sélectionnez l'icône de la corbeille pour supprimer l'image. Une confirmation vous sera demandée. Une fois supprimée, elle est définitivement perdue ! Peut également être utilisé pour supprimer un dossier.

## Conseils

- Si vous souhaitez conserver les images et les documents dans des dossiers locaux séparés :
  1.  créez un dossier à la racine de votre site, par exemple **fichiers**
  2.  allez dans le plugin *Filesystem - Local* et ajoutez **fichiers** sous **Sélectionner les répertoires**.
  3.  De retour dans le composant Médias, vous verrez *images* et *fichiers* comme des éléments distincts dans le panneau Local.
- La taille maximale de téléversement dans les Médias peut être modifiée à une valeur autre que `10 Mo` dans les Options des Médias.
- Vous pouvez téléverser ou supprimer plusieurs fichiers en même temps.

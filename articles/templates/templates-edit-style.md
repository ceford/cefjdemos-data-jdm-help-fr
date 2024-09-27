<!-- Filename: Help4.x:Templates:_Edit_Style  / Display title: Modèles : Modifier le style -->

## Description

La page *Styles de Modèles: Modifier* est utilisée pour modifier les styles de modèle. Lorsqu'un modèle est installé pour la première fois, un style par défaut est créé pour celui-ci. Le style par défaut pour le modèle aura le même nom que le modèle avec le suffixe *- Default*. Pour créer une variation différente du style de modèle par défaut, cochez la case du style par défaut et appuyez sur l'icône *Dupliquer* dans la barre d'outils. Ensuite, éditez le duplicata.

### Éléments Communs

Certains éléments de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).

## Comment Accéder

- Sélectionnez **Système → Panneau de Templates → Styles des Templates de Site** 
  dans le menu Administrateur. Ou...
- Sélectionnez **Système → Panneau de Templates → Styles des Templates Administrateur** 
  dans le menu Administrateur. Ensuite...
  - Sélectionnez le nom du Style de Template à éditer dans la colonne Style.

## Capture d'écran

![modèles cassiopeia éditer l'onglet de l'éditeur de style](../../../fr/images/templates/templates-site-edit-style-details-tab.png)

## Champs de Formulaire

- **Nom du Style** Le nom du style. C'est le nom qui s'affichera dans la colonne Style de l'écran *Modèle : Styles*.

### Onglet Détails

- **Informations** Le nom du modèle, indicateur de Site ou d'Administrateur et une brève description.

### Onglet Avancé

![onglet avancé de l'éditeur de style modèle cassiopeia](../../../fr/images/templates/templates-site-edit-style-advanced-tab.png)

Cette section peut ne pas être présente pour tous les styles. Si un modèle à partir duquel un style est dérivé dispose d'options configurables, elles seront présentes ici. Ce sont ces options configurables supplémentaires qui vous permettent d'avoir plusieurs styles différents de modèles avec des variations de ces options. Les options disponibles varient selon les options mises à disposition par le développeur du modèle.

### Paramètres de Couleur Atum

Le modèle Administrateur par défaut vous permet d'expérimenter avec les variations de couleur. Sauvegardez et voyez !

### Paramètres d'Image Atum

Vous pouvez sélectionner une image pour remplacer le **Logo de Connexion** dans le formulaire de connexion de l'Administrateur, et le **Logo de Marque** dans la barre de titre de l'Administrateur en mode étendu et en mode compacté. Les valeurs par défaut sont les logos de marque Joomla. Dans la barre de titre, le mot Joomla! est présent dans la version **Grande Marque** et omis dans la version **Petite Marque**. Sélectionnez **Basculer le Menu** pour voir le changement.

Si vous fournissez votre propre Petite Marque, vous devez également fournir une substitution de style de largeur. Pour ce faire, créez un fichier user.css à la racine du modèle et insérez le texte suivant, en remplaçant 3rem par une largeur appropriée pour votre image:

       .header .logo.small {
           width: 3rem;
       }

### Onglet Attribution des Menus

![onglet attribution des menus de l'éditeur de style modèle cassiopeia](../../../fr/images/templates/templates-site-edit-style-menu-assignment-tab.png)

Cette section contient tous les éléments de menu configurés sur votre site Joomla! Pour appliquer le style actuel à la page web correspondante de l'élément de menu, cochez la case à côté de l'élément de menu. Vous pouvez appuyer sur le bouton *Basculer la Sélection* pour inverser les sélections des éléments de menu.

**Remarque** Si une case à cocher est grisée et ne peut pas être cochée, alors cela peut être parce que l'élément de menu est utilisé par un autre utilisateur. Vous pouvez vérifier si c'est le cas en allant à l'écran du gestionnaire de menus pour le menu concerné. S'il y a un symbole de cadenas à côté de l'élément de menu, alors il est actuellement utilisé par un autre utilisateur.

*Traduit par openai.com*


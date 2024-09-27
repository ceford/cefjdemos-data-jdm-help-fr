<!-- Filename: Help6.x:Modules_Advanced_Tab  / Display title: Modules : Onglet Avancé -->

## Description

L'onglet Module : Avancé est utilisé avec quelques variations mineures dans tous les formulaires d'édition de module.

## Capture d'écran

![Onglet avancé des modules](../../../fr/images/modules/modules-custom-advanced-tab.png)

## Champs de Formulaire

### Onglet Avancé

- **Disposition** Si vous avez défini une ou plusieurs dispositions alternatives pour un module, soit dans le modèle, soit dans Joomla! Core, vous pouvez sélectionner la disposition à utiliser pour ce module.
- **Classe du Module** Un suffixe appliqué à la classe CSS du Module. Ceci vous permet de créer des styles CSS personnalisés qui s'appliqueront uniquement à ce module. Vous modifierez alors le fichier `user.css` de votre modèle pour appliquer le style à cette nouvelle classe. Entrez ce paramètre avec un espace initial pour créer une nouvelle classe CSS pour ce module. Entrez le paramètre sans espace initial pour changer le nom de la classe CSS de ce module.
- **Titre Automatique** Présent dans certains modules pour ...
- **Mise en Cache** Utiliser Global / Pas de Mise en Cache. Détermine si le contenu de ce Module doit être mis en cache ou non. Un paramètre de *Utiliser Global* utilisera les paramètres de cache de la page de Configuration Globale.
- **Durée de la Mise en Cache** Le nombre de secondes pendant lesquelles l'élément sera mis en cache localement. Il peut être laissé en toute sécurité à la valeur par défaut.
- **Style du Module** Vous pouvez utiliser cette option pour remplacer le style des modèles pour sa position.
- **Tag du Module** La balise HTML dans laquelle le module sera placé. Par défaut, il s'agit d'une balise `div`, mais d'autres éléments HTML5 peuvent également être utilisés.
- **Taille Bootstrap** (Valeurs de 0 à 12) Cela vous permet de choisir la largeur du module via l'élément span intégré dans Bootstrap.
- **Tag d'En-tête** La balise HTML à utiliser pour l'en-tête ou le titre des modules. Il peut s'agir d'une balise `h1`, `h2`, `h3`, `h4`, `h5`, `h6` ou d'une balise `p`. Notez que vous devez utiliser un style de module (chrome) de HTML5 ou ajouter vos styles de modules personnalisés dans `<mamodele>/html/modules.php`.
- **Classe d'En-tête** Ici, vous pouvez ajouter des classes CSS optionnelles à ajouter à l'élément en-tête ou titre des modules.

*Traduit par openai.com*


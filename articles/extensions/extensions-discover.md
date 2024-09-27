<!-- Filename: Help4.x:Extensions:_Discover  / Display title: Extensions : Découvrir  -->

## Description

Cette page vous permet de découvrir des extensions qui n'ont pas été installées via le processus d'installation normal. Par exemple, certaines extensions sont trop volumineuses pour être téléchargées via l'interface web en raison des limitations de l'environnement d'hébergement web. En utilisant cette fonctionnalité, vous pouvez télécharger les fichiers d'extension directement sur votre serveur web en utilisant d'autres moyens tels que FTP ou SFTP et placer ces fichiers d'extension dans le répertoire approprié. Vous pouvez ensuite utiliser la fonction de découverte pour trouver la nouvelle extension téléchargée et l'activer dans votre installation Joomla!. En utilisant l'opération de découverte, vous pouvez également découvrir et installer plusieurs extensions en même temps. Une extension peut être installée avec la fonction de découverte et les étapes suivantes :

1.  Téléchargez les fichiers d'extension non compressés dans le répertoire approprié de votre installation Joomla!. Par exemple, si vous souhaitez télécharger une extension de modèle de site dans votre installation Joomla!, vous devez créer un répertoire pour l'extension de modèle dans le sous-répertoire /templates de votre installation Joomla!. Ensuite, vous téléchargez les fichiers de l'extension de modèle dans ce répertoire.
2.  Après avoir téléchargé les fichiers d'extension, retournez à la page Découvrir du Gestionnaire d'extensions et sélectionnez le bouton **Découvrir** dans la barre d'outils. Cela lancera la fonction de recherche qui cherchera dans vos répertoires d'extensions Joomla! pour trouver des extensions non installées.
3.  Si l'extension que vous avez téléchargée est compatible avec votre version de Joomla! et n'est pas déjà installée, elle apparaîtra dans la liste des extensions découvertes sur cette page.
4.  Cochez la case à gauche de l'extension découverte, puis sélectionnez le bouton **Installer** dans la barre d'outils. Cela installera l'extension dans votre installation Joomla!.

### Éléments Communs

Certains éléments de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonnes de liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordre des éléments de la liste](jdocmanual?article=help/common-elements/list-ordering).
* [Pagination de la liste](jdocmanual?article=help/common-elements/list-pagination).

## Comment accéder

- Sélectionnez **Système → Panneau d'installation → Découvrir** dans le menu Administrateur.

## Capture d'écran

![Liste de découverte des extensions](../../../fr/images/extensions/discover-list.png)

## En-têtes de colonne

- **Nom** Le nom de l'extension.
- **Emplacement** Indique s'il s'agit d'une extension de site ou d'administrateur.
- **Type** Le type d'extension – Module, Plugin, Template, Langue.
- **Version** Le numéro de version de l'extension.
- **Date** La date de publication de l'extension.
- **Auteur** L'auteur de l'extension.
- **Répertoire** Si l'extension est un plugin, cela montre le sous-répertoire dans le répertoire /plugins de l'installation Joomla! où l'extension est située. Par défaut, Joomla! a les sous-répertoires suivants dans le répertoire Plugins, chacun représentant différents types de plugins définis : authentication, content, editors, editors-xtd, extension, search, system, user.
- **ID** Le numéro d'identification. Un numéro d'identification unique attribué à cette entrée. Il est automatiquement attribué par Joomla! et est utilisé pour l'identification interne de l'entrée. Le numéro ne peut pas être modifié.

## Conseils

- Si vous avez de nombreuses extensions que vous souhaitez installer, vous pouvez les télécharger toutes dans les répertoires appropriés de votre installation Joomla! et ensuite utiliser cet écran pour les découvrir toutes en une seule opération. Vous pouvez ensuite installer toutes les extensions en une seule étape en les sélectionnant toutes et en cliquant sur le bouton **Installer** dans la barre d'outils.

*Traduit par openai.com*


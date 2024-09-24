<!-- Filename: Help4.x:Extensions:_Install / Display title: Extensions : Installer -->

## Description

Les extensions sont utilisées pour ajouter des fonctionnalités à Joomla! qui n'existent pas dans l'installation standard. Des centaines d'extensions sont disponibles pour Joomla!, et de nouvelles sont développées en permanence.

Les extensions sont classées en cinq types, comme suit :

- Un *Composant* est une mini-application qui affiche le contenu principal de la page. Des exemples de composants sont les Contacts, la Page d'accueil et les Flux d'actualités.
- Un *Module* est une extension plus petite, généralement utilisée pour afficher un petit élément sur plusieurs pages. Des exemples de modules incluent les Menus et les Articles connexes.
- Un *Plugin* est une section de code qui s'exécute lorsqu'un événement prédéfini se produit dans Joomla!. Par exemple, les éditeurs sont des plugins qui s'exécutent lorsqu'une session d'édition est ouverte.
- L'extension *Langue* permet d'afficher l'interface Frontend et Backend de Joomla! dans n'importe quelle langue pour laquelle une extension de langue existe. Ainsi, Joomla! peut être diffusé dans une nouvelle langue sans modification du programme principal.
- Un *Template* contrôle la façon dont le contenu d'un site web est affiché, y compris l'emplacement et la disposition des éléments, les couleurs, les polices, etc. Les templates permettent de séparer l'apparence du site web de son contenu.

### Éléments communs

Certains éléments de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).

## Comment y accéder

- Sélectionnez **Système → Panneau d'installation → Extensions** depuis le menu d'administration.

Quatre méthodes d'installation sont disponibles. Si **Installer depuis le Web** est défini comme premier dans la liste ou était la dernière méthode sélectionnée, il y aura un bref délai pendant que Joomla télécharge une sélection initiale de données d'extensions depuis le Joomla Extensions Directory.

L'ordre normal des onglets pour les méthodes d'installation est le suivant :

* Télécharger le fichier du package
* Installer depuis un dossier
* Installer depuis une URL
* Installer depuis le Web

Une seule méthode est nécessaire pour installer une extension donnée. La procédure normale pour installer une extension Joomla! est la suivante :

1.  Téléchargez un ou plusieurs fichiers d'archive (généralement au format ".zip" ou "tar.gz") depuis le site web du fournisseur d'extensions vers un répertoire local sur votre ordinateur. Notez que certaines extensions s'installent en un seul fichier (par exemple, un composant ou un module) tandis que d'autres peuvent avoir deux fichiers ou plus (par exemple, un composant et un module). S'il y a plusieurs parties, chacune peut avoir son propre fichier d'archive. Ou bien, les parties peuvent être combinées dans un fichier package.
2.  Choisissez une des méthodes décrites pour installer l'extension.
3.  Une fois terminé, l'écran affichera un message **Succès** ou **Échec**.
4.  Selon l'extension, il peut être nécessaire d'activer l'extension (par exemple, dans les listes des modules ou des plugins).

## Onglet Télécharger le fichier du package

![Onglet installer extension télécharger le fichier du package](../../../fr/images/extensions/install-upload-package-file.png)

- Faites glisser et déposez ou parcourez jusqu'à l'emplacement où vous avez téléchargé le fichier d'archive de l'extension.

Le téléchargement commence automatiquement. Notez la **Taille maximale de téléchargement : 32,00 Mo** définie pour votre installation. Si vous ne pouvez pas augmenter cette valeur, vous pouvez utiliser *Installer depuis un dossier*.

## Onglet Installer depuis un dossier

![Onglet installer extension depuis un dossier](../../../fr/images/extensions/install-from-folder.png)

1.  Créez un répertoire temporaire sur votre disque dur local et décompressez le fichier d'archive de l'extension dans ce répertoire temporaire.
2.  Utilisez FTP pour télécharger le contenu de ce répertoire (y compris les fichiers et sous-répertoires) vers un répertoire sur votre serveur.
3.  Dans le champ *Répertoire d'installation*, spécifiez le répertoire serveur où vous avez téléchargé les fichiers et sous-répertoires du package.
4.  Cliquez sur le bouton *Vérifier et installer* et Joomla! installera le contenu du répertoire donné.

Notez qu'il est courant de placer le dossier contenant votre extension décompressée dans le dossier tmp de votre site Joomla.

## Onglet Installer depuis une URL

![Onglet installer extension depuis une URL](../../../fr/images/extensions/install-from-url.png)

Au lieu de télécharger le fichier d'archive sur votre ordinateur local, spécifiez simplement l'URL du fichier d'archive cible. Ensuite, cliquez sur le bouton "Vérifier et installer" et Joomla! l'installera automatiquement directement depuis cette URL. *Notez qu'avec cette méthode, vous n'aurez pas de copie du fichier d'archive sur votre ordinateur local.*

## Onglet Installer depuis le Web

Pour installer une extension directement depuis le Joomla Extension Directory (JED). Vous pouvez sélectionner des extensions à lister par catégorie ou vous pouvez rechercher par nom partiel.

![Onglet installer extension depuis le Web](../../../fr/images/extensions/install-from-web.png)

## Conseils

- Quatre méthodes d'installation alternatives sont disponibles, comme indiqué ci-dessus. La plus courante est la méthode "Télécharger le fichier du package".
- Si vous souhaitez installer un module ou un plugin tiers appartenant à un composant, vous devrez généralement installer le composant ainsi que le module ou le plugin pour pouvoir utiliser le module ou le plugin. Cela est généralement documenté dans les instructions d'installation de l'extension sur le site web de l'auteur.
- De même, si vous désinstallez un composant tiers qui possède également ses propres modules ou plugins, ces modules et plugins ne pourront plus être utilisés. Il est donc généralement recommandé de désinstaller ces modules et plugins dépendants également.
- Certains composants développés par des développeurs tiers peuvent inclure leurs propres modules ou plugins dans l'installateur. Dans ce cas, assurez-vous que les répertoires des modules ou plugins soient accessibles en écriture. Sinon, l'extension ne fonctionnera pas correctement.
- **AVERTISSEMENT DE SÉCURITÉ :** Il est recommandé d'utiliser uniquement les extensions tierces dont vous avez réellement besoin sur votre site. N'utilisez pas votre site en production à des fins de test, car cela pourrait compromettre votre site et votre serveur. Testez de nouvelles extensions sur un site de test local avant de les déployer sur votre site en production.
- N'installez pas d'extensions Joomla! téléchargées depuis des [sites Warez](https://fr.wikipedia.org/wiki/Warez) car elles pourraient être infectées par un virus ou un logiciel malveillant qui pourrait causer des dommages sur le serveur et contaminer l'ordinateur de vos visiteurs !
- Installer depuis une URL distante peut être dangereux. Pour cette raison, il est généralement recommandé d'utiliser les options "Installer depuis le Web", "Télécharger le fichier du package" ou "Installer depuis un dossier" lors de l'installation de nouvelles extensions.

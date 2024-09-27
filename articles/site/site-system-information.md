<!-- Filename: Help4.x:Site_System_Information  / Display title: Informations Système  -->

## Description

La page *Informations sur le système* fournit des informations sur l'environnement du serveur hôte. Il y a cinq panneaux d'onglets différents : Informations sur le système, Paramètres PHP, Fichier de configuration, Permissions des dossiers, et Informations PHP. Chaque panneau fournit des informations détaillées sur cet aspect du site. Cela est utile lors du dépannage des problèmes de configuration.

- Notez qu'aucun de ces paramètres ne peut être modifié depuis ces panneaux. Cela doit être fait dans différents endroits tout au long de l'installation de Joomla!, en fonction du paramètre spécifique.
- Certains paramètres peuvent être modifiés depuis la page Configuration globale. D'autres dépendent de la configuration du serveur hôte et ne peuvent pas être modifiés depuis Joomla!.

### Éléments communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).

## Comment accéder

- Sélectionnez **Système → Panneau d'information → Informations Système** dans le menu Administrateur.

## Capture d'écran

![tableau de bord d'accueil](../../../fr/images/site/system-information-tab.png)

## Onglets de Formulaire

### Onglet d'Information Système

- **PHP Built on** Fournit des détails sur le système d'exploitation principal
  sur lequel le serveur web exécutant Joomla fonctionne.
- **Type de Base de Données** Indique le type de base de données utilisé par
  l'installation de Joomla.
- **Version de la Base de Données** Indique la version actuelle de la base de 
  données MySQL utilisée par l'installation de Joomla.
- **Collation de la Base de Données** Explique comment la base de données MySQL
  est structurée pour les informations utilisées par Joomla!.
- **Collation de la Connexion à la Base de Données** Le jeu de caractères et la
  collation de la base de données.
- **Version de PHP** Indique la version actuelle du script serveur PHP
  utilisée pour cette installation de Joomla.
- **Serveur Web** Indique le type et la version actuels du serveur web
  sur lequel l'installation de Joomla! fonctionne.
- **Interface Serveur Web à PHP** Le script qui permet l'interaction 
  entre le serveur web (dans la plupart des cas, Apache) et le langage
  de script PHP.
- **Version de Joomla!** Indique la version actuelle de Joomla!. Il est
  recommandé de toujours utiliser la version stable la plus récente.
- **Agent Utilisateur** Résumé du système d'exploitation et des informations 
  de navigation de la machine locale de l'utilisateur actuel, utilisé pour
  créer un identifiant de session unique pour l'accès et la fonctionnalité
  au sein du site Joomla!.

### Onglet de Paramètres PHP

![tableau de bord accueil](../../../fr/images/site/php-settings-tab.png)

Cet écran affiche les informations des paramètres PHP. Si l'un d'entre eux
est mis en évidence comme incorrect, il doit être corrigé.

- **Mode Sécurisé** Paramètre recommandé : OFF
- **Open basedir** Paramètre recommandé : Dépendant du site
- **Afficher les Erreurs** Paramètre recommandé : OFF
- **Balises Courtes** Paramètre recommandé : ON
- **Téléchargements de Fichiers** Paramètre recommandé : ON
- **Guillemets Magiques** Paramètre recommandé : OFF
- **Inscription Globale** Paramètre recommandé : OFF
- **Tampon de Sortie** Paramètre recommandé : OFF
- **Chemin de Sauvegarde des Sessions** Paramètre recommandé : Dépendant du site
- **Démarrage Automatique des Sessions** Paramètre recommandé : 0
- **XML Activé** Paramètre recommandé : YES
- **Zlib Activé** Paramètre recommandé : YES
- **ZIP Natif Activé** Paramètre recommandé : YES
- **Fonctions Désactivées** Paramètre recommandé : Dépendant du site
- **Chaîne Multioctet (mbstring) Activée** Paramètre recommandé : YES
- **Iconv Disponible** Paramètre recommandé : YES
- **Variables d'Entrée Maximales** Paramètre recommandé : 2500

### Onglet Fichier de Configuration

![tableau de bord accueil](../../../fr/images/site/configuration-file-tab.png)

Cet onglet affiche le contenu du fichier *configuration.php* actuel de Joomla! 
qui est stocké dans le répertoire `path-to-joomla-root`. Ce fichier est créé automatiquement
lorsque vous installez Joomla! pour la première fois et c'est là que la plupart des
modifications de la section de Configuration Globale de Joomla! sont enregistrées.
Veuillez noter qu'aucun des paramètres ne peut être modifié à partir de cette page.
Utilisez la Configuration Globale pour voir plus d'informations sur ces paramètres et pour
apporter des modifications.

### Onglet Permissions des Dossiers

![tableau de bord accueil](../../../fr/images/site/folder-permissions-tab.png)

Cet onglet affiche une liste des répertoires auxquels le serveur web doit
avoir accès en écriture. Veuillez noter que tous les répertoires listés sur cette
page doivent être marqués comme **Writable**. Si ce n'est pas le cas, vous devrez peut-être 
modifier les permissions pour pouvoir installer et utiliser Joomla! avec succès. Le fichier 
configuration.php est inclus et affiché comme **Unwritable**.

### Onglet Information PHP

![tableau de bord accueil](../../../fr/images/site/php-information-tab.png)

Cet onglet affiche les paramètres de configuration du langage de script serveur PHP
utilisé par Joomla!, ainsi que toutes les informations système associées à la 
création du serveur web. Il s'agit de la sortie d'un script intégré php.info
intégré dans Joomla!.

PHP est installé et s'exécute sur le serveur (d'où "côté serveur" ci-dessus),
et donc tous les paramètres sont effectués sur le serveur. Le visiteur
du site web n'a pas besoin d'avoir de logiciel spécifique installé sur sa 
machine locale pour visualiser ou utiliser toutes les fonctionnalités 
supplémentaires que PHP offre au site web.

Tous les paramètres susceptibles d'être nécessaires sont affichés ici.
Tous les changements nécessaires doivent être apportés dans les fichiers 
de configuration *php.ini* et autres fichiers sur le serveur web.

La capacité du propriétaire du site web à contrôler ces informations dépend
de son niveau de contrôle sur le serveur ou de la flexibilité de l'hébergeur 
du serveur.

Il est bon de connaître les limitations d'une installation particulière du serveur.
La sortie de cet écran est utilisée pour trouver des informations détaillées sur 
la manière dont PHP est implémenté sur le serveur.

Pour des détails complets sur les informations contenues dans l'onglet Info PHP,
visitez : [http://php.net/phpinfo](http://php.net/phpinfo).

## Conseils

- Si vous avez des problèmes pour installer des extensions, télécharger des fichiers ou
  modifier les options de configuration, vérifiez l'onglet Permissions du Répertoire
  pour vous assurer que vous avez la permission d'écrire sur les fichiers de votre serveur web.
  Le *Statut* des répertoires devrait être *Accessible en écriture*. Sinon, vous pourriez
  être dans l'impossibilité de télécharger ou de modifier des fichiers dans ces répertoires.
- Lorsque vous cherchez de l'aide pour des problèmes de configuration, par exemple dans un
  forum Joomla!, il est très utile de publier des informations spécifiques
  sur votre installation Joomla!. Cette page est un moyen facile de trouver
  toutes ces informations en un seul endroit. Encore mieux, utilisez le
  **Forum Post Assistant** documenté en haut des pages de forum Joomla!, 
  comme le forum [Questions Générales](https://forum.joomla.org/viewforum.php?f=834).

*Traduit par openai.com*


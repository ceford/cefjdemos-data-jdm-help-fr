<!-- Filename: Help4.x:Joomla_Update / Display title: Mise à jour de Joomla -->

## Description

Cette page permet de mettre à jour Joomla! en utilisant un package de mise à jour provenant du référentiel de code Joomla!. Il est préférable et plus sûr de laisser Joomla se mettre à jour automatiquement en utilisant cette méthode.

## Comment y accéder

Dans le **Tableau de bord d'accueil → Panneau de notifications**, l'icône Joomla affichera l'un des deux messages suivants :
- **Joomla est à jour**
- **X.Y.Z Disponible - Mettez à jour maintenant !**

Sélectionnez l'icône.

De plus, dans le **Système → Panneau de mise à jour → Joomla**, une coche s'affichera pour indiquer que le site est à jour, ou un numéro de version s'affichera pour indiquer qu'une nouvelle version est disponible.

## Capture d'écran

Si votre site est à jour, vous verrez cet écran :

![Télécharger & Mettre à jour](../../../en/images/joomla-update/upload-update-up-to-date.png)

Si une mise à jour est disponible, vous verrez cet écran :

![Télécharger & Mettre à jour](../../../en/images/joomla-update/upload-update-available.png)

Si vous mettez à jour une version majeure ou mineure, vous verrez un écran de vérification avant mise à jour :

![Vérification avant mise à jour](../../../en/images/joomla-update/upload-update-pre-update-check.png)

Sélectionnez chacun des trois éléments du menu pour vérifier si des éléments nécessitent une attention particulière.

## Démarrer la mise à jour

Si vous n'êtes pas sur la dernière version de Joomla, vous pouvez installer la dernière mise à jour depuis cette page. Pour ce faire, assurez-vous d'avoir effectué une sauvegarde et cochez la case **Je suis conscient...** pour indiquer que vous avez pris une sauvegarde. Ensuite, sélectionnez le bouton **Démarrer la mise à jour** et Joomla installera la dernière version.

L'écran de mise à jour affichera une barre de progression pendant l'avancement de la mise à jour.

### Télécharger et mettre à jour

Vous pouvez utiliser ce bouton pour mettre à jour Joomla si votre serveur est derrière un pare-feu ou autrement incapable de contacter les serveurs de mise à jour. Commencez par télécharger le package de mise à jour de Joomla au format ZIP depuis la page officielle de téléchargement Joomla.

Vous devez avoir les paramètres PHP *upload_max_filesize* et *post_max_size* réglés à 64 Mo et votre limite de mémoire PHP réglée à 256 Mo. Sinon, la mise à jour pourrait échouer. Une bonne raison de faire une sauvegarde !

![télécharger et installer](../../../en/images/joomla-update/upload-update-upload-install.png)

## Options de mise à jour

Le bouton Options dans la barre d'outils vous permet de sélectionner le type de mise à jour :

- **Par défaut** : Utilisé pour les sites qui restent sur la version installée.
- **Joomla Next** : Utilisé pour les sites qui passent normalement à la prochaine version majeure dès qu'une version stable est publiée.
- **URL personnalisée** : Permet aux développeurs de sélectionner une source de mise à jour.

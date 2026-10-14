<!--
{
    "source": "https://docs.joomla.org/Help4.x:Joomla_Update",
    "title": "Mise \u00e0 jour de Joomla : introduction",
    "description": " ",
    "author": ""
}
-->

## Description

Cette page permet de mettre à jour Joomla! à l’aide d’un paquet de mise à jour provenant du dépôt de code de Joomla! Il est préférable et plus sûr de laisser Joomla se mettre à jour lui-même en utilisant cette méthode.

## Comment accéder

Dans le **Tableau de bord d’accueil → Panneau des notifications**, l’icône Joomla affichera l’un des deux messages suivants :
- **Joomla est à jour**
- **X.Y.Z disponible - Mettre à jour maintenant !**

Sélectionnez l’icône.

De plus, le **Système → Panneau de mise à jour → Joomla** affichera une coche, indiquant que Joomla est à jour, ou un numéro de version, indiquant qu’une nouvelle version est disponible.

## Capture d’écran

Si votre site est à jour, vous verrez cet écran :

![Téléversement et mise à jour : à jour](../../../en/images/joomla-update/joomla-update/01-upload-update-up-to-date.png)

Si une mise à jour est disponible, vous verrez cet écran :

![Téléversement et mise à jour : mise à jour disponible](../../../en/images/joomla-update/joomla-update/02-upload-update-available.png)

Si vous mettez à jour une version majeure ou mineure, vous verrez un écran de vérification préalable à la mise à jour :

![Téléversement et mise à jour : vérification préalable à la mise à jour](../../../en/images/joomla-update/joomla-update/03-upload-update-pre-update-check.png)

Sélectionnez chacun des trois éléments de menu pour vérifier si quelque chose nécessite votre attention.

## Démarrer la mise à jour

Si vous n’utilisez pas la dernière version de Joomla, vous pouvez installer la
dernière mise à jour depuis cette page. Pour ce faire, assurez-vous d’avoir effectué
une sauvegarde et cochez la case **Je suis conscient...** pour indiquer que vous
l’avez fait. Sélectionnez ensuite le bouton **Démarrer la mise à jour** et Joomla
installera la dernière version.

L’écran de mise à jour affiche une barre de progression pendant la mise à jour.

### Téléverser et mettre à jour

Vous pouvez utiliser ce bouton pour mettre à jour Joomla si votre serveur se trouve derrière un pare-feu ou s’il ne peut pas contacter les serveurs de mise à jour pour une autre raison. Commencez par télécharger le paquet de mise à niveau de Joomla au format ZIP depuis la page officielle de téléchargement de Joomla.

Vous devez avoir défini *upload_max_filesize* et *post_max_size* de PHP sur 64 Mo, ainsi que la limite de mémoire PHP sur 256 Mo. Sinon, la mise à jour peut échouer. Voilà une bonne raison d’effectuer cette sauvegarde !

![Téléverser et mettre à jour : téléverser et installer](../../../en/images/joomla-update/joomla-update/04-upload-update-upload-install.png)

## Options de mise à jour

Le bouton Options de la barre d’outils vous permet de sélectionner le type de mise à jour :

- **Par défaut** Cette option est utilisée pour les sites configurés pour conserver la version installée.
- **Joomla Next** Cette option est utilisée pour les sites qui passent normalement à la version majeure suivante dès qu’une version stable est publiée.
- **URL personnalisée** Pour permettre aux développeurs de sélectionner une source de mise à jour.

*Traduit par openai.com*
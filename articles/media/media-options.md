<!-- Filename: Help4.x:Media:_Options / Display title: Médias : Paramètres -->

## Description

La page *Média : Paramètres* est utilisée pour définir les paramètres globaux des médias.

### Éléments communs

Certains aspects de cette page sont abordés dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet des Permissions](jdocmanual?article=help/common-elements/edit-permissions).

## Comment y accéder

- Sélectionnez **Contenu → Médias** dans le menu de l'administrateur.
- Sélectionnez le bouton **Options** dans la barre d'outils.

## Capture d'écran

![Options des médias](../../../fr/images/media/media-options.png)

## Champs du formulaire

### Médias

- **Taille maximale (en MB)** Utilisez zéro pour aucune limite. Remarque : le serveur a une limite maximale.
- **Chemin vers le dossier de fichiers** Entrez le chemin vers le dossier de fichiers par rapport à la racine de votre espace web. Ne commencez pas le chemin par un slash. Changer de chemin par rapport à la valeur par défaut *images* peut casser vos liens.
- **Chemin vers le dossier d'images** Entrez le chemin vers le dossier d'images par rapport à la racine de votre espace web. Ne commencez pas le chemin par un slash.
- **Restreindre les téléchargements** Restreindre les téléchargements pour les utilisateurs de niveau inférieur à gestionnaire aux images si `Fileinfo` ou `MIME Magic` n'est pas installé.
  - **Extensions autorisées** Restreindre les téléchargements pour les utilisateurs de niveau inférieur à gestionnaire aux fichiers présents dans la liste.
  - **Vérifier les types MIME** Utilisez `Fileinfo` ou `MIME Magic` pour tenter de vérifier les fichiers. Essayez de désactiver cette option si vous obtenez des erreurs de type MIME invalide.
- **Extensions d'images légales (types de fichiers)** Extensions d'images (types de fichiers) que vous êtes autorisé à télécharger (séparées par des virgules). Elles sont utilisées pour vérifier les en-têtes d'images valides et pour sélectionner des images.
- **Extensions audio légales (types de fichiers)** Extensions audio (types de fichiers) que vous êtes autorisé à télécharger (séparées par des virgules). Elles sont utilisées pour vérifier les en-têtes audio valides et pour sélectionner des fichiers audio.
- **Extensions vidéo légales (types de fichiers)** Extensions vidéo (types de fichiers) que vous êtes autorisé à télécharger (séparées par des virgules). Elles sont utilisées pour vérifier les en-têtes vidéo valides et pour sélectionner des vidéos.
- **Extensions de documents légales (types de fichiers)** Extensions de documents (types de fichiers) que vous êtes autorisé à télécharger (séparées par des virgules). Elles sont utilisées pour vérifier les en-têtes de documents valides et pour sélectionner des documents.
- **Extensions ignorées** Extensions de fichiers ignorées pour la vérification des types MIME et les téléchargements restreints.
- **Types MIME légaux** Une liste de types MIME légaux à télécharger, séparés par des virgules.

## Conseils

- Si vous êtes un utilisateur débutant, vous pouvez conserver les valeurs par défaut jusqu'à ce que vous en sachiez plus sur l'utilisation des options globales.
- Si vous êtes un utilisateur avancé, vous pouvez gagner du temps en créant de bonnes valeurs par défaut ici.

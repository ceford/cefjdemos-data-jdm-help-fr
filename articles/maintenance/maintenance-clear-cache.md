<!-- Filename: Help4.x:Maintenance:_Clear_Cache / Display title: Maintenance: Vider le cache -->

## Description

Les fichiers de cache sont des fichiers temporaires créés pour améliorer les performances du site lorsqu'ils sont activés dans les paramètres de la configuration globale du site. Les fichiers de cache peuvent devenir obsolètes et causer des problèmes d'affichage, qui peuvent être corrigés en supprimant *tous* les fichiers de cache. Après la suppression, le site peut être un peu plus lent jusqu'à ce que les fichiers de cache soient recréés avec l'utilisation.

### Éléments communs

Certains aspects de cette page sont abordés dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonne de liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Pagination de liste](jdocmanual?article=help/common-elements/list-pagination).

## Comment y accéder

- Sélectionnez **Système → Panneau de maintenance → Vider le cache** dans le menu de l'administrateur.

## Capture d'écran

![Maintenance Vider le Cache](../../../fr/images/maintenance/maintenance-clear-cache.png)

## En-têtes de colonne

- **Groupe de cache** Le type d'élément mis en cache dans ce fichier. Il s'agit également du nom du sous-répertoire où ce type de fichier de cache est stocké. Les fichiers de cache sont stockés dans le répertoire `\<chemin-vers-Joomla!\>/cache/\<Nom du groupe de cache\>`.
- **Nombre de fichiers** Le nombre de fichiers actuellement dans ce groupe de cache.
- **Taille** La taille totale des fichiers de cache dans ce groupe.

## Conseils

- Normalement, vous souhaitez supprimer tous les fichiers de cache. Pour ce faire, cochez la case dans l'en-tête de colonne pour sélectionner tous les fichiers, puis cliquez sur l'icône Supprimer dans la barre d'outils.

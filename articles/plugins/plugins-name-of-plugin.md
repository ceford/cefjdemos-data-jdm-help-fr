<!-- Filename: Help4.x:Plugins:_Name_of_Plugin  / Display title: Plugins : Nom du Plugin -->

## Description

La page *Plugin* permet d’accéder à la modification des détails et options de tous les plugins. Les options communes à tous les plugins se trouvent dans la partie droite de l'*onglet Plugin* décrit ci-dessous.

### Groupes de Plugins

Il y a un grand nombre de plugins de base disponibles. Ils sont listés ici par groupe avec des liens vers une documentation séparée :

* [Groupe des journaux d'actions.](jdocmanual?article=help/plugins/plugin-group-action-logs) (1 Plugin)
* [Groupe d'authentification API.](jdocmanual?article=help/plugins/plugin-group-api-authentication) (2 Plugins)
* [Groupe d'authentification.](jdocmanual?article=help/plugins/plugin-group-authentication) (3 Plugins)
* [Groupe de comportement.](jdocmanual?article=help/plugins/plugin-group-behavior) (3 Plugins)
* [Groupe de contenu.](jdocmanual?article=help/plugins/plugin-group-content) (10 Plugins)
* [Groupe des éditeurs.](jdocmanual?article=help/plugins/plugin-group-editors) (3 Plugins)
* [Groupe des boutons Editor Xtd.](jdocmanual?article=help/plugins/plugin-group-editors-xtd) (8 Plugins)
* [Groupe des extensions.](jdocmanual?article=help/plugins/plugin-group-extensions) (3 Plugins)
* [Groupe des champs.](jdocmanual?article=help/plugins/plugin-group-fields) (16 Plugins)
* [Groupe des systèmes de fichiers.](jdocmanual?article=help/plugins/plugin-group-file-system) (1 Plugin)
* [Groupe Finder.](jdocmanual?article=help/plugins/plugin-group-finder) (5 Plugins)
* [Groupe d'installation.](jdocmanual?article=help/plugins/plugin-group-installer) (5 Plugins)
* [Groupe d'actions média.](jdocmanual?article=help/plugins/plugin-group-media-action) (3 Plugins)
* Groupe d'authentification multi-facteur (5 Plugins)
* [Groupe de confidentialité.](jdocmanual?article=help/plugins/plugin-group-privacy) (6 Plugins)
* [Groupe des icônes rapides.](jdocmanual?article=help/plugins/plugin-group-quick-icon) (7 Plugins)
* [Groupe des données d'exemple.](jdocmanual?article=help/plugins/plugin-group-sample-data) (2 Plugins, 3 Plugins pour les installations de développement)
* Groupe Schema.org (9 Plugins)
* [Groupe système.](jdocmanual?article=help/plugins/plugin-group-system) (24 Plugins)
* Groupe des tâches (9 Plugins)
* [Groupe utilisateur.](jdocmanual?article=help/plugins/plugin-group-user) (5 Plugins)
* [Groupe des services web.](jdocmanual?article=help/plugins/plugin-group-web-services) (17 Plugins)
* [Groupe de flux de travail.](jdocmanual?article=help/plugins/plugin-group-workflow) (3 Plugins)

La liste complète des plugins est disponible dans une
[longue liste unique](https://docs.joomla.org/Chunk4x:List_of_Plugins).

### Éléments communs

Certains éléments de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).

## Comment Accéder

À partir du menu Administrateur :

- Sélectionnez **Tableau de Bord Principal → Plugins** ou..
- Sélectionnez **Système → Gestion du panneau → Plugins** puis...
  - Sélectionnez le Nom du Plugin dans la liste des plugins.

## Capture d'écran

![Onglet du plugin Plugins](../../../fr/images/plugins/plugins-plugin-tab.png)

## Champs de Formulaire

### Onglet Plugin

#### Panneau de Gauche

**Titre du Plugin** défini comme un en-tête `<h2>`.

**type/fichier** défini comme des *badges* pour aider à localiser les fichiers du plugin dans le code source.

**Description** Une brève description de ce que fait ce Plugin. Elle ne peut pas être modifiée car elle est spécifiée par le développeur du plugin. Elle peut être vide si le développeur n'a pas spécifié de description pour le plugin.

Si le plugin a des options configurables, elles apparaîtront ici. De nombreux plugins n'ont aucune option configurable.

#### Panneau de Droite

Le panneau de droite est le même pour tous les plugins et comporte les champs suivants :

- **Statut** Indique si l'élément est activé ou non.
- **Accès** Les *niveaux d'accès* utilisateur pour ce plugin.
- **Ordre** Une liste déroulante des plugins du même Type. La liste des plugins est organisée par leur ordre actuel. Vous pouvez changer l'ordre de ce plugin par rapport aux autres en sélectionnant le plugin dans la liste déroulante sous lequel vous souhaitez que ce plugin soit ordonné.
- **Type de Plugin** Le Type du Plugin. Cette valeur ne peut pas être modifiée.
- **Fichier Plugin** Le nom du fichier du Plugin. Chaque Plugin a deux fichiers avec ce nom. L'un a l'extension de fichier '.php' et l'autre a l'extension de fichier '.xml'.

## Conseils

- Les paramètres configurables du plugin sont appelés *Options*. Vous pouvez voir les termes *Options* et *Paramètres* utilisés de manière interchangeable dans la documentation d'aide et les tutoriels que vous consultez.

*Traduit par openai.com*


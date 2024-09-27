<!-- Filename: Help4.x:Languages:_Content  / Display title: Langues : Contenu -->

## Description

La page Langues: Contenu affiche des informations sur les langues installées.

### Éléments Communes

Certains éléments de cette page sont détaillés dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonnes de liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Pagination de liste](jdocmanual?article=help/common-elements/list-pagination).

## Comment accéder

- Sélectionnez **Système → Gérer le Panneau → Langues de Contenu** dans le menu Administrateur.

## Capture d'écran

![Liste de contenu des langues](../../../fr/images/languages/languages-content.png)

## En-têtes de colonne

Informations sélectionnées :

- **Titre** Les noms des langues installées sur ce site web.
- **Titre natif** Titre de la langue dans la langue maternelle.
- **Balise de langue** La balise de langue - exemple : en-GB pour l'anglais (Royaume-Uni).
  Cela doit être le préfixe exact utilisé pour la langue installée ou à
  installer.
- **Code de langue dans l'URL** Le code de langue utilisé dans les URL du site multilingue.
- **Image** Nom du fichier image pour cette langue lors de l'utilisation de l'option de base 
  du sélecteur de langue *Utiliser des drapeaux d'image*. Exemple : Si *en* est 
  choisi, alors l'image sera *en.gif*. Les images et le CSS pour ce module 
  se trouvent dans media/mod_languages/
- **Accueil** Si une page par défaut est définie pour cette langue ou non.

## Conseils

- Les utilisateurs peuvent utiliser n'importe quelle langue de la liste des langues installées,
  soit en l'assignant dans la liste des utilisateurs, soit
  en remplissant un formulaire de menu - Nouveau/Éditer - Mise en page du formulaire utilisateur
  en front-end. Cela entraînera la génération des invites du système Joomla! dans cette langue uniquement pour cet utilisateur. Par exemple, si un utilisateur
  choisit l'espagnol comme langue, alors le module de recherche affichera
  des invites en espagnol.
- Ce choix de l'utilisateur n'est pas affecté par la langue par défaut définie pour le
  front-end.
- Changer la langue d'un utilisateur ou la langue par défaut n'affecte pas les
  articles et autres contenus du site web.
- **Important** : Ne supprimez pas les fichiers de langue par défaut (par exemple,
  avec FTP). Cela créera des erreurs tant en front-end qu'en back-end.
- Des langues supplémentaires peuvent être ajoutées en utilisant la page Installer des langues.
- Si désiré, vous pouvez afficher le site front-end dans une langue et montrer
  les pages d'administration du back-end dans une langue différente. De plus,
  les articles individuels peuvent être configurés pour utiliser une langue différente dans le
  volet de Paramètres avancés lors de l'édition de l'article.

*Traduit par openai.com*


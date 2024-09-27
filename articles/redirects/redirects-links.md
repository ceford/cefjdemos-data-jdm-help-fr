<!-- Filename: Help4.x:Redirects:_Links  / Display title: Redirections : Liens -->

## Description

La page *Redirections : Liens* affiche une liste des redirections actuelles du site web.

Le composant de redirection est utilisé pour rediriger des URL de pages web qui n'existent plus sur votre site web vers des pages web fonctionnelles. L'URL à partir de laquelle vous souhaitez rediriger ne doit pas être fonctionnelle et en train de charger une page web. Cela peut être l'URL d'une page web que vous avez désactivée.

L'*URL expirée* que vous spécifiez lorsque vous créez la redirection
doit être l'URL complète telle que vous la saisiriez dans votre navigateur web. Le
composant n'affichera que la dernière partie de l'URL source dans la
liste des redirections.

La *Nouvelle URL* que vous spécifiez lors de la création d'une redirection
doit également être l'URL complète. Vous devez avoir l'option *Utiliser la réécriture d'URL*
activée dans les options de *Configuration globale* de votre installation Joomla!
pour que les redirections que vous créez fonctionnent.

### Éléments communs

Certains éléments de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes des colonnes de la liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Pagination de liste](jdocmanual?article=help/common-elements/list-pagination).

## Comment accéder

- Sélectionnez **Système → Gérer le panneau → Redirections** dans le menu Administrateur.

## Capture d'écran

![Redirige les liens](../../../fr/images/redirects/redirects-links.png)

## En-têtes de colonne

- **URL expirée** L'URL qui est redirigée sur votre site web.
  Seule la partie de la page web de l'URL est affichée dans cette liste.
- **Nouvelle URL** L'URL de destination pour la redirection.
- **Page de référence** La page web de référence pour la redirection.
- **Date de création** Date à laquelle l'élément (Article, Catégorie, etc.) a été créé.
- **Erreurs 404** Nombre de fois que l'erreur 404 s'est produite sur cette URL.
- **Code de statut** Le code de statut de la page.

## Conseils

- Pour que vos redirections fonctionnent, vous devez activer l'option 
  **Utiliser la réécriture d'URL** dans les options de la **Configuration Globale** de votre
  installation Joomla!. Notez également que le simple fait d'activer l'option *Utiliser la
  réécriture d'URL* ne suffit pas. Vous devez effectuer l'étape supplémentaire de
  renommer le fichier `htaccess.txt` dans le répertoire du site web où vous
  avez installé Joomla! en `.htaccess` ou en tout autre nom de fichier requis par votre serveur web Apache pour des directives de configuration supplémentaires. Dans le
  fichier de configuration Apache, ce paramètre est nommé `AccessFileName` et
  par défaut, il est défini sur `.htaccess`. 

*Traduit par openai.com*


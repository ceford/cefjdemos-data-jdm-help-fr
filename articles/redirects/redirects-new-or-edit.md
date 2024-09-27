<!-- Filename: Help4.x:Redirects:_New_or_Edit  / Display title: Redirections : Nouveau ou Modifier -->

## Description

La page *Redirections : Nouveau ou Modifier* est utilisée pour ajouter une nouvelle redirection ou modifier une redirection existante. L'URL à partir de laquelle vous souhaitez rediriger ne doit pas être une URL fonctionnelle sur votre site web qui charge effectivement une page web. Il peut s'agir de l'URL d'une page web que vous avez désactivée dans l'interface d'administration de Joomla! L'URL Source que vous spécifiez lorsque vous créez la redirection doit être l'URL complète telle que vous la taperiez dans votre navigateur web. L'URL de Destination que vous spécifiez lorsque vous créez une redirection doit également être l'URL complète.

### Éléments Communs

Certains éléments de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).

## Comment accéder

- Sélectionnez **Système → Redirections** dans le menu Administrateur. Ensuite...
  - Pour créer une nouvelle redirection, cliquez sur le bouton **Nouveau** dans la barre d'outils. Ou...
  - Pour modifier une redirection existante, cliquez sur son lien dans la colonne **URL expirée**.

## Capture d'écran

![Redirige les liens](../../../fr/images/redirects/redirects-edit.png)

## Champs de formulaire

### Onglet Modifier/Nouveau Lien \#1

- **URL expirée** L'URL à rediriger.
- **Nouvelle URL** L'URL vers laquelle rediriger.
- **Statut** Statut de publication de l'élément. Les valeurs possibles sont :
  - *Activer* L'élément est activé. C'est le seul état qui permettra
    aux utilisateurs réguliers du site web de voir cet élément.
  - *Désactivé* L'élément est désactivé.
  - *Archivé* L'élément a été archivé.
  - *Mis à la corbeille* L'élément a été envoyé à la corbeille.
- **Commentaire** Un commentaire visible uniquement par un administrateur. Il est
  principalement destiné à la référence de l'administrateur uniquement.
- **ID** Il s'agit d'un numéro d'identification unique pour cet élément attribué
  automatiquement par Joomla. Il est utilisé pour identifier l'élément en interne,
  et vous ne pouvez pas modifier ce numéro. Lors de la création d'un nouvel élément, ce
  champ affiche "0" jusqu'à ce que vous enregistriez la nouvelle entrée, moment où un
  nouvel ID lui est assigné.
- **Date de création** Date de création de l'élément (Article, Catégorie, etc.).
- **Date de dernière mise à jour** Affiche la dernière date de modification de l'élément.

## Comment créer une redirection

1.  Tout d'abord, assurez-vous d'avoir activé l'option *Utiliser la réécriture d'URL* dans les options de Configuration Globale de votre installation Joomla!. Notez que le simple fait d'activer l'option *Utiliser la réécriture d'URL* ne suffit pas. Vous devez également prendre la mesure supplémentaire de renommer le fichier `htaccess.txt` dans le répertoire du serveur web où vous avez installé Joomla! en `.htaccess` ou en tout autre nom de fichier requis par votre serveur web Apache pour des directives de configuration supplémentaires. Dans le fichier de configuration d'Apache, ce paramètre est nommé `AccessFileName` et il est par défaut défini sur `.htaccess`.
2.  Ensuite, ouvrez la page *Redirection : Liens* et sélectionnez le bouton *Nouveau* de la barre d'outils.
3.  Dans la page *Redirections : Nouveau*, entrez les informations de redirection. Lors de l'entrée des URLs dans les champs *URL expirée* et *Nouvelle URL*, entrez l'URL complète comme vous la taperiez dans votre navigateur web pour la visualiser. L'*URL expirée* doit être une URL qui ne résout aucune page web valide sur votre site web. Vous pouvez spécifier une URL source pour une page web Joomla! que vous avez désactivée dans le backend de l'administrateur. Assurez-vous que l'option *État* est définie sur **Activé**.
4.  Sélectionnez le bouton **Enregistrer & Fermer** de la barre d'outils pour enregistrer votre nouvelle redirection et la mettre en vigueur.

## Conseils

- Lorsque vous saisissez des URL dans les champs *URL expirée/source* et *URL nouvelle/destination*, entrez l'URL complète telle que vous la taperiez dans votre navigateur web pour afficher la page web.

*Traduit par openai.com*


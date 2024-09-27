<!-- Filename: Help4.x:Banners:_New_or_Edit_Client  / Display title: Bannières : Modifier le client -->

## Description

Le formulaire Banners: Edit Client est utilisé pour entrer ou modifier les données du client de bannière.
Au moins un client de bannière est requis avant qu'une bannière puisse être créée.

### Éléments Communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Le Popup de l'historique des versions](jdocmanual?article=help/common-elements/edit-version-history).

## Comment accéder

- Sélectionnez **Composants → Bannières → Clients** dans le menu Administrateur.
  - Pour créer un nouveau client, sélectionnez le bouton **Nouveau** dans la barre d'outils.
  - Pour modifier un client existant, sélectionnez le **nom** dans la colonne Client.

## Capture d'écran

![Modifier les bannières du client](../../../fr/images/banners/banners-edit-client-details-tab.png)

## Champs de Formulaire

- **Nom** Le nom de ce client.

### Onglet Détails

- **Nom du Contact** Le nom de la personne de contact pour ce client.
- **E-mail du Contact** L'adresse e-mail du client de la bannière.
- **Type d'Achat** Le type d'achat de la bannière. Cela sert à indiquer comment le client de la bannière a acheté le temps d'affichage pour la bannière - mensuel, annuel, etc.
- **Suivre les Impressions** Indiquez si vous souhaitez suivre le nombre de fois que la bannière est affichée aux visiteurs du site web.
- **Suivre les Clics** Indiquez si vous souhaitez suivre le nombre de fois que la bannière est cliquée par les visiteurs du site web.
- **Informations Supplémentaires** Entrez toutes les informations supplémentaires que vous souhaitez enregistrer pour ce client.
- **Statut** Statut de publication de l'élément. Les valeurs possibles sont :
  - *Publié*: L'élément est publié. C'est le seul état qui permet aux utilisateurs réguliers du site de voir cet élément.
  - *Non publié*: L'élément n'est pas publié.
  - *Archivé*: L'élément a été archivé.
  - *Supprimé*: L'élément a été envoyé à la corbeille.
- **Note de Version** Champ facultatif pour identifier cette version de l'élément dans la fenêtre de l'Historique des Versions de l'élément.

### Onglet Métadonnées

![Onglet métadonnées de modification de client de bannières](../../../fr/images/banners/banners-edit-client-metadata-tab.png)

- **Mots-Clés** Entrée facultative pour les mots-clés. Ils doivent être saisis séparés par des virgules (par exemple, "chats, chiens, animaux domestiques") et peuvent être saisis en majuscules ou en minuscules. (Par exemple, "CHATS" correspondra à "chats" ou "Chats"). Les mots-clés peuvent être utilisés de plusieurs manières :
  1.  Pour aider les moteurs de recherche et d'autres systèmes à classer le contenu de l'article.
  2.  En combinaison avec les tags de la bannière, pour afficher des bannières spécifiques en fonction du contenu de l'article. Par exemple, disons que vous avez une bannière avec une publicité pour des produits pour chiens et une autre bannière pour des produits pour chats. Vous pouvez faire en sorte que votre bannière pour chiens s'affiche lorsqu'un utilisateur consulte un article relatif aux chiens et que votre bannière pour chats s'affiche pour un article relatif aux chats. Pour ce faire, vous devez :
      - Ajouter les mots-clés "chien" et "chat" aux articles appropriés.
      - Ajouter les tags "chien" et "chat" aux bannières appropriées dans Bannières : Modifier.
      - Définir le paramètre du module de bannière 'Recherche par tags' sur "Oui" dans la liste des modules du site : Bannières.
  3.  Pour les articles uniquement, en combinaison avec le module Articles - Connexes, pour afficher des articles partageant au moins un mot-clé en commun. Par exemple, si l'article actuel affiché comporte les mots-clés "chats, chiens, singes", tout autre article comportant au moins un de ces mots-clés apparaîtra dans le module 'Articles - Connexes'.
- **Utiliser son propre préfixe** Indiquez si vous souhaitez utiliser le préfixe de la bannière ou celui du client. Sélectionnez *Non* si vous souhaitez utiliser le préfixe du client de la bannière.
- **Préfixe des Mots-Clés Méta** Lors de la correspondance des mots-clés méta, ne recherchez que des mots-clés méta avec ces préfixes facultatifs. Cela améliore les performances.


<!-- Filename: Help4.x:Contacts:_New_or_Edit  / Display title: Contacts: Modifier -->

## Description

Le *Formulaire de Modification des Contacts* est utilisé pour ajouter un nouveau Contact ou éditer un Contact existant.

**Attention :** Si un contact a un élément de menu, alors les Paramètres du Menu de Contact remplacent certains paramètres disponibles ici. Faites attention à ne pas divulguer d'informations personnelles par erreur !

### Éléments Communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Schéma](jdocmanual?article=help/common-elements/edit-schema).
* [L'onglet Publication](jdocmanual?article=help/common-elements/edit-publishing).
* [L'onglet Associations](jdocmanual?article=help/common-elements/edit-associations).
* [La fenêtre contextuelle d'historique des versions](jdocmanual?article=help/common-elements/edit-version-history).

## Comment Accéder

- Sélectionnez **Composants → Contacts → Contacts** dans le menu Administrateur.
- Pour **Ajouter** un nouveau Contact :
  - Sélectionnez le bouton **Nouveau** dans la barre d'outils.
- Pour **Modifier** un Contact existant :
  - Sélectionnez un titre de contact dans la colonne **Titre**.

## Capture d'écran

![Contacts modifier l'onglet contact](../../../fr/images/contacts/contacts-edit-contact-tab.png)

## Champs de Formulaire

Dans cette section, vous pouvez entrer des informations sur le Contact, telles que son nom, son adresse, son e-mail, etc. Les options vous permettent de contrôler les paramètres tels que les informations affichées pour chaque Contact.

- **Nom** Le nom complet du Contact.
- **Alias** Le nom interne de l'élément. Normalement, vous pouvez laisser ce champ vide et Joomla remplira une valeur par défaut avec le Titre en minuscules et des tirets à la place des espaces.

### Onglet Modifier le Contact

Ici, vous entrez les informations de base concernant le contact.

- **Utilisateur Lié** Si ce Contact est lié à un utilisateur, sélectionnez l'icône *Sélectionner un Utilisateur* pour révéler un formulaire contextuel permettant de sélectionner l'un des utilisateurs enregistrés. Un utilisateur lié peut être supprimé avec le bouton *- Aucun Utilisateur -* dans le formulaire contextuel Sélectionner un Utilisateur.
- **Image** Image à afficher pour ce Contact. Sélectionnez un fichier image dans la liste déroulante. Ceci liste les images dans le dossier 'images/stories'. Les images peuvent être téléchargées en utilisant le composant Média.
- **Position** La position actuelle du Contact.
- **E-mail** L'adresse e-mail du Contact. Notez que les adresses e-mail dans Joomla! peuvent être protégées des "robots spammeurs" en activant le Plugin "Content-Email Cloaking". Celui-ci est activé par défaut.
- **Adresse** L'adresse de rue du Contact.
- **Ville ou Banlieue** La ville ou la banlieue du Contact.
- **État ou Province** L'état ou le département du Contact.
- **Code Postal / ZIP** Le code postal du Contact.
- **Pays** Le pays du Contact.
- **Téléphone** Le numéro de téléphone du Contact.
- **Mobile** Le numéro de téléphone portable du Contact.
- **Fax** Le numéro de fax du Contact.
- **Site Web** L'adresse du site web du Contact.
- **Champs de Tri** Pour activer les champs de tri pour les listes de catégories, allez à l'écran **Contacts → Options** et réglez **List Layouts → Sort By** sur **Sort Name**. Ensuite, vous devez utiliser des mots réels pour le tri. Par exemple, définissez le premier champ de tri sur **Doe**, le deuxième champ sur **John** pour le premier contact; puis définissez le premier champ de tri sur **Doe**, le deuxième champ sur **Jane** pour le deuxième contact. Le troisième champ n'est pas utilisé dans ce cas. Les champs de tri sont des champs de caractères donc si vous voulez trier par âge, vous devez entrer 0x pour les âges inférieurs à 10, donc 08 par exemple.
  - **Premier Champ de Tri** Le nom à utiliser comme premier champ de tri.
  - **Deuxième Champ de Tri** Le nom à utiliser comme deuxième champ de tri.
  - **Troisième Champ de Tri** Le nom à utiliser comme troisième champ de tri.
- **Statut** Statut de publication de l'élément. Les valeurs possibles sont :
  - *Publié* : L'élément est publié. C'est le seul état qui permettra aux utilisateurs réguliers du site web de voir cet élément.
  - *Non Publié* : L'élément n'est pas publié.
  - *Archivé* : L'élément a été archivé.
  - *Supprimé* : L'élément a été envoyé à la Corbeille.
- **Catégorie** La Catégorie à laquelle cet élément appartient.
- **Mis en avant** Indique si l'élément sera affiché en vue mise en avant.
- **Accès** Le niveau d'accès de visualisation pour cet élément.
- **Langue** Langue de l'élément.
- **Tags** Entrez un ou plusieurs tags optionnels pour cet élément. Vous pouvez sélectionner des tags existants en tapant les premières lettres. Vous pouvez également créer de nouveaux tags en les entrant ici. Les tags vous permettent de voir des listes d'éléments liés à travers différents types de contenu (par exemple, articles, contacts et catégories).
- **Note de Version** Champ optionnel pour identifier cette version de l'élément dans la fenêtre Historique des Versions de l'élément.

### Onglet Informations Diverses

![Onglet Modifier Contact](../../../fr/images/contacts/contacts-edit-miscellaneous-tab.png)

D'autres informations sur ce Contact peuvent être entrées en utilisant l'éditeur.

### Onglet Affichage

![Onglet Modifier Contact](../../../fr/images/contacts/contacts-edit-display-tab.png)

- **Afficher la Catégorie** Afficher ou masquer la catégorie du Contact.
- **Afficher la Liste des Contacts** Afficher ou masquer la liste des Contacts.
- **Format d'Affichage** Détermine le style utilisé pour afficher les sections du formulaire de contact.
- **Tags** Afficher ou masquer les tags pour cet élément.
- **Informations de Contact** Afficher ou masquer les informations de Contact.
- **Informations Diverses** Afficher ou masquer les informations diverses.
- **vCard** Afficher ou masquer le lien vCard pour ce Contact.
- **Afficher les Articles de l'Utilisateur** Si ce contact est lié à un utilisateur, et si cette option est réglée sur Afficher, une liste des articles créés par cet utilisateur s'affichera.
- **\# Articles à Lister** Nombre d'articles à lister.
- **Profil de l'Utilisateur** Si ce contact est lié à un utilisateur, et si cela est réglé sur Afficher, le profil de cet utilisateur s'affichera.
- **Afficher les Groupes de Champs Personnalisés de l'Utilisateur** Afficher les champs personnalisés de l'utilisateur qui appartiennent à tous les groupes ou à des groupes de champs sélectionnés uniquement.
- **Liens de Contact** Afficher ou masquer les liens de contact.
- **Libellé du Lien A** Libellé pour un lien supplémentaire pour ce contact.
- **URL du Lien A** L'URL du lien supplémentaire pour ce contact.
- **Libellé du Lien B** Libellé pour un lien supplémentaire pour ce contact.
- **URL du Lien B** L'URL du lien supplémentaire pour ce contact.
- **Libellé du Lien C** Libellé pour un lien supplémentaire pour ce contact.
- **URL du Lien C** L'URL du lien supplémentaire pour ce contact.
- **Libellé du Lien D** Libellé pour un lien supplémentaire pour ce contact.
- **URL du Lien D** L'URL du lien supplémentaire pour ce contact.
- **Libellé du Lien E** Libellé pour un lien supplémentaire pour ce contact.
- **URL du Lien E** L'URL du lien supplémentaire pour ce contact.
- **Disposition** Utiliser une disposition différente de la vue de composant fournie ou des remplacements dans les modèles.

### Onglet Formulaire

![Onglet Modifier Contact](../../../fr/images/contacts/contacts-edit-form-tab.png)

- **Formulaire de Contact** Afficher ou masquer le formulaire d'e-mail. Si Afficher est sélectionné, un formulaire s'affiche permettant à l'utilisateur d'envoyer un e-mail au Contact depuis le site web.
- **Envoyer une Copie à l'Expéditeur** Afficher ou masquer la case à cocher : *Envoyer une copie de ce message à votre propre adresse*.
- **Vérification de la Session** Vérifiez l'existence du cookie de session. Cela signifie que les utilisateurs sans cookies activés ne pourront pas envoyer des e-mails.
- **Réponse Personnalisée** Désactive la réponse automatique, permettant aux Plugins de gérer l'intégration avec d'autres systèmes.
- **Redirection de Contact** Entrez une URL alternative, où l'utilisateur sera redirigé après l'envoi de l'e-mail.

*Traduit par openai.com*


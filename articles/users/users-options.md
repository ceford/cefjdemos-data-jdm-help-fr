<!-- Filename: Help4.x:Users:_Options / Display title: Utilisateurs : Paramètres -->

## Description

La page *Utilisateurs : Options* est utilisée pour définir des options globales pour tous les utilisateurs, y compris :

- Captcha,
- inscription autorisée et type d'inscription,
- groupe d'utilisateurs par défaut pour les nouveaux utilisateurs,
- compteur de réinitialisation du mot de passe ou du nom d'utilisateur,
- notification par email à l'administration lors de l'inscription d'un nouvel utilisateur, et plus encore.

## Comment accéder

* Sélectionnez **Site → Utilisateurs** depuis le *Tableau de bord d'accueil*. Ou...
* Sélectionnez **Utilisateurs → Gérer** dans le menu Administrateur. Ensuite...
* Sélectionnez le bouton **Options** dans la barre d'outils.

## Capture d'écran

![options des utilisateurs onglet options utilisateurs](../../../fr/images/users/users-options-user-options-tab.png)

## Champs de formulaire

### Onglet Options Utilisateurs

- **Autoriser l'inscription des utilisateurs**
  - *Oui* Les utilisateurs peuvent s'inscrire depuis le Frontend du site via le lien *Créer un compte* fourni dans le formulaire de connexion.
  - *Non* Le lien *Créer un compte* ne sera pas affiché.
- **Groupe d'inscription des nouveaux utilisateurs** Le groupe auquel les utilisateurs sont attribués par défaut lorsqu'ils s'inscrivent sur le site. Par défaut, *Inscrit*.
- **Groupe d'utilisateurs invités** Le groupe auquel les invités sont assignés (les invités sont les visiteurs du site qui ne sont pas connectés). Il est possible de créer du contenu visible uniquement par les invités et non par les utilisateurs connectés.
- **Envoyer le mot de passe** Si cette option est activée (*Oui*), le premier mot de passe de l'utilisateur sera envoyé par email dans le mail d'inscription.
- **Activation du compte utilisateur**
  - *Aucune* Le compte utilisateur sera activé immédiatement sans aucune action requise.
  - *Auto* L'utilisateur recevra un email avec un lien d'activation. Le compte sera activé lorsque l'utilisateur cliquera sur le lien d'activation.
  - *Administrateur* L'utilisateur recevra un email avec un lien d'activation. Lorsque l'utilisateur cliquera sur ce lien, l'administrateur du site sera notifié par email et devra activer le compte de l'utilisateur.
- **Envoyer un email aux administrateurs** Envoyer une notification par email aux administrateurs avec l'option *Activation du compte utilisateur* réglée sur *Aucune* ou *Auto*.
- **Captcha** Le plugin Captcha pour l'inscription des comptes utilisateurs, le rappel de mot de passe et le rappel du nom d'utilisateur.
- **Paramètres utilisateur Frontend**
  - *Afficher* Les utilisateurs pourront modifier les paramètres de base depuis le Frontend du site.
  - *Masquer* Les utilisateurs ne pourront pas modifier ces paramètres.
- **Langue du Frontend** Afficher ou masquer la langue du site...
- **Modifier le nom d'utilisateur** Permettre aux utilisateurs de modifier leur nom d'utilisateur.

### Onglet Options de domaine d'email

![options des utilisateurs onglet domaines d'email](../../../fr/images/users/users-options-email-domain-options-tab.png)

- **Nom de domaine** Saisissez une liste de domaines d'email autorisés ou interdits. Par défaut, tous les domaines sont autorisés. Les jokers (\*) sont pris en charge. Par exemple :
  - \* (Astérisque) : Autorise ou interdit tous les domaines.
  - \*.com : Autorise ou interdit tous les domaines en '.com'.
  - \*.joomla.org : Autorise ou interdit tous les sous-domaines 'joomla.org'.
- **Règle** Sélectionnez si le domaine doit être autorisé ou interdit.

### Onglet Options de mot de passe

![options des utilisateurs onglet options de mot de passe](../../../fr/images/users/users-options-password-options-tab.png)

- **Nombre maximum de réinitialisations** Le nombre maximum de réinitialisations de mot de passe autorisées pendant une période donnée. Zéro indique qu'il n'y a pas de limite.
- **Durée de réinitialisation** La période, en heures, pour le compteur de réinitialisation.
- **Longueur minimale** Définir la longueur minimale d'un mot de passe.
- **Nombre minimal d'entiers** Définir le nombre minimum d'entiers à inclure dans un mot de passe.
- **Nombre minimal de symboles** Définir le nombre minimum de symboles (par exemple !@#\$) requis dans un mot de passe.
- **Nombre minimal de majuscules** Définir le nombre minimum de lettres majuscules requises dans un mot de passe.
- **Nombre minimal de minuscules** Définir le nombre minimum de lettres minuscules requises dans un mot de passe.

### Onglet Authentification multi-facteurs

![options des utilisateurs onglet authentification multi-facteurs](../../../fr/images/users/users-options-multi-factor-authentication-tab.png)

- **Positions de modules autorisées en frontend** Lors de l'affichage de la page d'authentification multi-facteurs en frontend, tous les modules seront masqués, sauf ceux dans les positions sélectionnées ici.
- **Afficher le titre en frontend** Afficher un titre sur la page de vérification de l'authentification multi-facteurs en frontend ? Le titre est toujours affiché en backend. Si vous avez besoin de modifier le titre, remplacez la clé de langue `COM_USERS_HEADING_MFA` en utilisant l'option *Langues : Remplacements*.
- **Positions de modules autorisées en backend** Lors de l'affichage de la page d'authentification multi-facteurs en backend, tous les modules seront masqués, sauf ceux dans les positions sélectionnées ici. Notez que les modules dans la position `title` sont toujours affichés : cela est nécessaire pour afficher l'icône et le titre de la page backend.
- **Désactiver l'authentification multi-facteurs** Tout utilisateur appartenant à *l'un* des groupes d'utilisateurs sélectionnés sera exempté de l'authentification multi-facteurs. Même s'ils ont configuré des méthodes d'authentification multi-facteurs, ils ne seront pas invités à les utiliser lors de la connexion et ne pourront pas les voir, les supprimer ou changer leur configuration.
- **Imposer l'authentification multi-facteurs** Tout utilisateur appartenant à *l'un* des groupes d'utilisateurs sélectionnés devra activer l'authentification multi-facteurs avant de pouvoir utiliser le site.
- **Style de template frontend** Choisissez le style de template frontend à utiliser sur la page d'authentification multi-facteurs. Sélectionnez *Utiliser le style par défaut* pour utiliser le style de template par défaut du site.
- **Authentification multi-facteurs après une connexion silencieuse** L'utilisateur devra-t-il passer par l'authentification multi-facteurs après une connexion silencieuse ? Les connexions silencieuses sont celles qui ne nécessitent pas de nom d'utilisateur ni de mot de passe, comme la fonctionnalité *Se souvenir de moi*, WebAuthn, etc.
- **Types de réponse d'authentification de connexion silencieuse (pour les experts)** Pour les experts. Une liste séparée par des virgules des types de réponse d'authentification Joomla considérés comme des connexions silencieuses. Par défaut, `cookie` (la fonctionnalité Se souvenir de moi) et `passwordless` (WebAuthn).
- **Intégration de nouveaux utilisateurs** Si l'utilisateur n'a pas encore configuré l'authentification multi-facteurs et que cette option est activée, il sera redirigé vers la page de configuration de l'authentification multi-facteurs ou l'URL personnalisée que vous définissez ci-dessous. Cela est conçu pour permettre à vos utilisateurs de savoir que l'authentification multi-facteurs est disponible sur votre site.
- **URL de redirection personnalisée** Si ce champ n'est pas vide, redirige vers cette URL au lieu de la page de configuration de l'authentification multi-facteurs lorsque l'option ci-dessus est activée. Attention : cela doit être une URL à l'intérieur de votre site. Vous ne pouvez pas vous connecter à un lien externe ou à un sous-domaine différent.

### Onglet Historique des notes utilisateur

![options des utilisateurs onglet historique des notes utilisateur](../../../fr/images/users/users-options-user-notes-history-tab.png)

- **Activer les versions** Enregistrer l'historique des versions des notes utilisateur.
- **Nombre maximum de versions** Le nombre maximum de versions à stocker pour une note utilisateur. Si une note utilisateur est enregistrée et que le nombre maximum de versions a été atteint, la version la plus ancienne sera supprimée automatiquement. Si réglé à 0, les versions ne seront jamais supprimées automatiquement.

### Onglet Email de masse aux utilisateurs

![options des utilisateurs onglet email de masse aux utilisateurs](../../../fr/images/users/users-options-mass-mail-users-tab.png)

- **Préfixe de sujet** Saisissez du texte optionnel à insérer automatiquement avant le sujet de l'email de masse.
- **Suffixe du corps du mail** Saisissez du texte optionnel à insérer automatiquement après le corps de l'email (par exemple, une signature).

### Onglet Intégration

![onglet d'intégration des options utilisateurs](../../../fr/images/users/users-options-integration-tab.png)

- **Activer les champs personnalisés** Activer la création de champs personnalisés.

## Conseils

Si vous êtes un utilisateur novice, conservez les valeurs par défaut ici jusqu'à ce que vous en sachiez plus sur l'utilisation des options globales.
<!-- Filename: Help4.x:Users:_Options / Display title: Utilisateurs : Paramètres -->

## Description

User Options set globally for all users include

- Captcha,
- registration allowed and type of registration,
- default user group for new users,
- reset password or username counter,
- new user registration email notice to administration and more.

## Comment y accéder ?
Sélectionner **Utilisateurs → Gestion**

- Cliquez sur le bouton **Paramètres** dans la barre d'outils.

## Capture d'écran

<img
src="https://docs.joomla.org/images/thumb/a/a4/Help-4x-Users-Options-screen-fr.png/800px-Help-4x-Users-Options-screen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/a4/Help-4x-Users-Options-screen-fr.png/1200px-Help-4x-Users-Options-screen-fr.png 1.5x, https://docs.joomla.org/images/thumb/a/a4/Help-4x-Users-Options-screen-fr.png/1600px-Help-4x-Users-Options-screen-fr.png 2x"
data-file-width="2400" data-file-height="1500" width="800" height="500"
alt="Users Options screen" />

## Champs de formulaire

### Utilisateurs

- **Autoriser l'inscription**.
  - Oui: Users can register from the Frontend of the site using the
    'Create an Account' link provided on the
    <a href="https://docs.joomla.org/Help4.x:Site_Modules:_Login/fr"
    class="new"
    title="Special:MyLanguage/Help4.x:Site Modules: Login/fr (page does not exist)">Login
    module</a>.
  - Non: The 'Create an Account' link will not show.
- **Groupe des inscrits**. The
  group
  that users are assigned to by default when they register on the site.
  Defaults to 'Registered'.
- **Groupe des visiteurs**. The group that guests are assigned to
  (Guests are visitors to the site who are not logged in). It is
  possible to create content on the site that is visible to guests but
  not visible to logged in users.
- **Envoyer le mot de passe**. Si 'Oui' est coché, le mot de passe
  initial de l'utilisateur sera inclus dans le mail envoyé lors de
  l'inscription.
- **Activation des comptes**.
  - Aucun: le nouvel inscrit est enregistré sans confirmation de la
    demande.
  - Auto activation: l'utilisateur reçoit un e-mail de confirmation de
    la demande d'inscription avec un lien sur lequel il doit cliquer
    pour activer son compte avant de se connecter.
  - Administration: l'utilisateur reçoit un e-mail de confirmation de la
    demande d'inscription avec un lien sur lequel il doit cliquer pour
    la valider. Puis, un message est envoyé aux utilisateurs des groupes
    ayant un droit de création de compte en administration du site pour
    qu'ils activent ce compte.
- **Notification administrateurs**. Send email notification to
  administrators with 'New User Account Activation' set to 'None' or
  'Self'.
- **Système Captcha**. Use
  Captcha
  for User Account Registration, User Password reminder and Username
  reminder.
- **Paramètres dans le profil**.
  - Afficher: Users will be able to modify their
    <a href="https://docs.joomla.org/Help4.x:Users:_Edit_Profile/fr"
    class="new"
    title="Special:MyLanguage/Help4.x:Users: Edit Profile/fr (page does not exist)">Basic
    Settings</a> from the Frontend of the site.
  - Masquer: User will not be able to change these settings.
  - Langue espace frontal (Site). Default site language.
- **Modification de l'identifiant**. Allow user to change Username.

### Domaine d'e-mail

<img
src="https://docs.joomla.org/images/thumb/0/05/Help-4x-Users-Options-email-domain-subscreen-fr.png/600px-Help-4x-Users-Options-email-domain-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/05/Help-4x-Users-Options-email-domain-subscreen-fr.png/900px-Help-4x-Users-Options-email-domain-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/0/05/Help-4x-Users-Options-email-domain-subscreen-fr.png/1200px-Help-4x-Users-Options-email-domain-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="998" width="600" height="299"
alt="Users Options email domain subscreen" />

- **Nom de domaine**. Vous pouvez saisir une liste de domaines d'e-mail
  autorisés et non autorisés. Par défaut tous les domaines sont
  autorisés.Les caractères génériques (\*) sont pris en charge. Par
  exemple :
  - \* (Astérisque): autorise ou interdit tous les domaines ,
  - \*.com: autorise ou interdit tous les domaines en '.com' ,
  - \*.joomla.org: autorise ou interdit tous les sous-domaines de
    'joomla.org'.
- **Règle** Autoriser ou non le domaine.

### Mots de passe

<img
src="https://docs.joomla.org/images/thumb/0/05/Help-4x-Users-Options-password-subscreen-fr.png/600px-Help-4x-Users-Options-password-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/05/Help-4x-Users-Options-password-subscreen-fr.png/900px-Help-4x-Users-Options-password-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/0/05/Help-4x-Users-Options-password-subscreen-fr.png/1200px-Help-4x-Users-Options-password-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="1181" width="600" height="354"
alt="Users Options password subscreen" />

- **Nbr de réinitialisations**. The maximum number of password resets
  allowed within the time period. Zero indicates no limit.
- **Temps de réinitialisation (heures)**. The time period, in hours, for
  the reset counter.
- **Longueur minimale du mot de passe**. Set the minimum lenght for a
  password.
- **Nbr minimum de chiffres**. Set the minimum number of integers that
  must be included in a password.
- **Nbr minimum de symboles**. Set the minimum number of symbols (such
  as !@#\$) required in a password.
- **Nbr minimum de majuscules**. Set the minimum number of upper case
  alphabetical characters required for a password.
- **Nbr minimum de minuscules**. Set the minimum number of lower case
  alphabetical characters required for a password.

### Authentification multifacteurs

<img
src="https://docs.joomla.org/images/thumb/0/03/Help-4x-Users-Options-multi-factor-authentication-subscreen-fr.png/600px-Help-4x-Users-Options-multi-factor-authentication-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/03/Help-4x-Users-Options-multi-factor-authentication-subscreen-fr.png/900px-Help-4x-Users-Options-multi-factor-authentication-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/0/03/Help-4x-Users-Options-multi-factor-authentication-subscreen-fr.png/1200px-Help-4x-Users-Options-multi-factor-authentication-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="1518" width="600" height="455"
alt="Users Options multi factor authentication subscreen" />

- **Positions autorisées des modules en frontal du site**. Lors de
  l'affichage de la page d'authentification multifacteurs en frontal du
  site, tous les modules seront masqués sauf ceux qui se trouvent dans
  les positions sélectionnées ici.
- **Afficher le titre en frontal**. Devrais-je afficher un titre dans la
  page de vérification de l'authentification multifacteurs ? Notes : en
  administration le titre est toujours affiché. Si vous devez changer le
  titre, veuillez remplacer la clé de langue 'COM_USERS_HEADING_MFA' en
  utilisant le système de
  <a href="https://docs.joomla.org/Help4.x:Languages:_Overrides/fr"
  class="new"
  title="Special:MyLanguage/Help4.x:Languages: Overrides/fr (page does not exist)">Langues :
  Substitutions de traduction</a> côté administration.
- **Positions autorisées des modules en administration**. Lors de
  l'affichage de la page d'authentification multi-facteurs, tous les
  modules seront masqués sauf ceux des positions sélectionnées ici.
  Veuillez noter que les modules de la position 'title' sont toujours
  affichés : ceci est nécessaire pour afficher l'icône et le titre de la
  page d'administration.
- **Désactiver l'authentification multifacteurs**. N'importe quel
  utilisateur qui appartient à *n'importe lequel* des groupes
  d'utilisateurs suivants sera exempté de l'authentification
  multifacteurs. Même s'ils ont mis en place des méthodes
  d'authentification multifacteurs, il ne leur sera pas demandé de les
  utiliser lorsqu'ils se connecteront, ils ne seront pas non plus en
  mesure de les consulter, de les supprimer, ou de modifier leur
  configuration.
- **Imposer l'authentification multifacteurs**. N'importe quel
  utilisateur qui appartient à *n'importe quel* des groupes
  d'utilisateurs suivants sera requis pour activer l'authentification
  multifacteurs avant d'être en mesure d'utiliser le site.
- **Style du template du site**. Choisissez le style de template du site
  à utiliser dans la page d'authentification multifacteurs. 'Valeur par
  défaut' sélectionne le style de template par défaut.
- **Authentification multifacteurs après connexion silencieuse**.
  L'utilisateur doit-il passer par l'authentification multifacteurs
  après une connexion silencieuse ? La connexion silencieuse est celle
  qui ne nécessitent pas de nom d'utilisateur et mot de passe telle les
  fonctions 'Se souvenir de moi', 'WebAuthn', etc.
- **Types de réponse d'authentification en connexion silencieuse (pour
  les experts)**. Une liste séparée par des virgules des types de
  réponses d'authentification Joomla qui sont considérés comme des
  connexions silencieuses. La valeur par défaut est 'cookie'
  (fonctionnalité 'Se souvenir de moi') et 'passwordless' (WebAuthn).
- **Nouveaux utilisateurs intégrés**. Si l'utilisateur n'a pas encore
  configuré l'authentification multifacteurs et que cette option est
  activée, il sera redirigé vers la page de configuration de
  l'authentification multifacteurs ou l'URL personnalisée ci-dessous.
  Ceci est conçu pour être un moyen simple de faire savoir à vos
  utilisateurs que l'authentification multifacteurs est une option
  disponible sur votre site.
- **URL de redirection personnalisée**. Si indiquée, redirige vers l'URL
  au lieu de la page de configuration d'authentification multifacteurs
  lorsque l'option ci-dessus est activée.Attention !: Ceci doit être une
  URL interne au site, vous ne pouvez pas connecter un lien externe ou
  un sous-domaine.

### Versions

<img
src="https://docs.joomla.org/images/thumb/7/7e/Help-4x-Users-Options-user-notes-history-subscreen-fr.png/600px-Help-4x-Users-Options-user-notes-history-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/7e/Help-4x-Users-Options-user-notes-history-subscreen-fr.png/900px-Help-4x-Users-Options-user-notes-history-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/7/7e/Help-4x-Users-Options-user-notes-history-subscreen-fr.png/1200px-Help-4x-Users-Options-user-notes-history-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="516" width="600" height="155"
alt="Users Options user notes history subscreen" />

- **Activer l'historique**. Save version history for User Notes.
- **Nombre maximum de versions à conserver**.
  The maximum number of versions to store for a User Note. If a User
  Note is saved and the maximum number of versions has been reached, the
  oldest version will be deleted automatically. If set to 0, then
  versions will never be deleted automatically.Pour en savoir plus.

### Envoi en nombre

<img
src="https://docs.joomla.org/images/thumb/c/ce/Help-4x-Users-Options-mass-mail-users-subscreen-fr.png/600px-Help-4x-Users-Options-mass-mail-users-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/ce/Help-4x-Users-Options-mass-mail-users-subscreen-fr.png/900px-Help-4x-Users-Options-mass-mail-users-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/c/ce/Help-4x-Users-Options-mass-mail-users-subscreen-fr.png/1200px-Help-4x-Users-Options-mass-mail-users-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="803" width="600" height="241"
alt="Users Options mass mail users subscreen" />

- **Préfixe de l'objet**. Saisir un texte à insérer automatiquement
  avant l'objet des e-mails en masse (facultatif).
- **Suffixe du message**. Saisir un texte à insérer automatiquement à la
  fin du corps du message (par exemple, une signature) (facultatif).

### Intégration

<img
src="https://docs.joomla.org/images/thumb/0/09/Help-4x-Users-Options-integration-subscreen-fr.png/600px-Help-4x-Users-Options-integration-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/09/Help-4x-Users-Options-integration-subscreen-fr.png/900px-Help-4x-Users-Options-integration-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/0/09/Help-4x-Users-Options-integration-subscreen-fr.png/1200px-Help-4x-Users-Options-integration-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="517" width="600" height="155"
alt="Users Options integration subscreen" />

- **Intégration des champs**. Enable the creation of custom fields.

### Droits

This section lets you set up the default Access Control List
permissions for all users.

<img
src="https://docs.joomla.org/images/thumb/a/a2/Help-4x-Users-Options-permissions-subscreen-fr.png/600px-Help-4x-Users-Options-permissions-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/a2/Help-4x-Users-Options-permissions-subscreen-fr.png/900px-Help-4x-Users-Options-permissions-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/a/a2/Help-4x-Users-Options-permissions-subscreen-fr.png/1200px-Help-4x-Users-Options-permissions-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="1449" width="600" height="434"
alt="Users Options permissions subscreen" />

To change the permissions for users, do the following.

1.  Sélectionnez le groupe en cliquant sur son titre.
2.  Trouvez l'action souhaitée.
    - **Configurer les droits et paramètres**. Users can edit the
      options and permissions.
    - **Ne configurer que les paramètres**. Users can edit the options
      exept the permissions.
    - **Accès à l'interface d'administration**. Users can access user
      administration interface.
    - **Créer**. Users can create users.
    - **Supprimer**. Users can delete users.
    - **Modifier**. Users can edit users.
    - **Modifier le statut**. User can change the published state and
      related information.
    - **Modifier les valeurs des champs personnalisés**. Users can edit
      any value of custom fields submitted in users.
3.  Sélectionnez l'autorisation souhaitée pour l'action que vous
    souhaitez modifier.
    - **Hérité**. Inherited for users in this Group from the Global Configuration
      permissions.
    - **Autorisé**. Allowed for users in this Group.Note: If this action
      is Denied at one of the higher levels, the Allowed permission here
      will not take effect. A Denied setting cannot be overridden.
    - **Refusé**. Denied for users in this Group.
4.  Cliquez sur **Enregistrer** dans la barre d'outils située en haut à
    gauche. Lors de l'actualisation de l'écran, la colonne des Droits
    appliqués affichera les droits effectifs pour ce groupe et action.

## Barre d'outils

En haut de la page, vous verrez la barre d'outils présentée dans la
capture d'écran ci-dessus.

- **Enregistrer**. Saves the users options and stays in the current
  screen.
- **Enregistrer & Fermer**. Saves the users options and closes the
  current screen.
- **Fermer**. Ferme l'écran et retourne à l'écran précédent sans
  enregistrer les modifications que vous auriez faites.
- **Afficher/Masquer l'aide**. Show help text below some options.
- **Aide**. Ouvre l'écran d'aide.

## Astuces

Si vous êtes un utilisateur débutant, vous pouvez simplement conserver
les valeurs par défaut ici jusqu'à en savoir plus sur l'utilisation des
paramètres globaux.

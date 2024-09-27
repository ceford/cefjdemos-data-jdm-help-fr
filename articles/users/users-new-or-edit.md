<!-- Filename: Help4.x:Users:_Edit_Profile  / Display title: Utilisateurs : Nouveau ou Modifier  -->

## Description

La page *Utilisateurs : Nouveau ou Modifier* est utilisée pour créer un nouvel utilisateur ou modifier un utilisateur existant.

### Éléments Communs

Certains éléments de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=aide/elements-communs/barres-d-outils).

## Comment accéder

Pour modifier un utilisateur existant :

- Sélectionnez **Utilisateurs → Gérer** dans le menu Administrateur. Puis...
  - Recherchez l'utilisateur requis et sélectionnez le lien du nom dans la
    colonne **Nom**.

Pour créer un nouvel utilisateur :

- Sélectionnez **Utilisateurs → Gérer** dans le menu Administrateur. Puis...
  - Sélectionnez le bouton **Nouveau** dans la barre d'outils.
- Ou... Sélectionnez **Utilisateurs → Gérer → Icône Plus** dans le menu
  Administrateur.
- Ou... Sélectionnez **Utilisateurs → Icône de tableau de bord** dans le menu
  Administrateur. Puis...
  - Sélectionnez l'icône **Plus** dans le panneau Utilisateurs.
- Ou... Sélectionnez **Tableau de bord Accueil → Panneau du site → Icône plus des utilisateurs** à partir du menu Administrateur.

## Capture d'écran

![modifier les détails de l'utilisateur](../../../fr/images/users/users-edit-account-details-tab.png)

## Champs de formulaire

### Détails du compte

- **Nom** Entrez le nom de l'utilisateur.
- **Nom de connexion** Entrez le nom de connexion (Nom d'utilisateur) pour l'utilisateur.
- **Mot de passe** Saisissez un (nouveau) mot de passe. Bien que ce champ ne soit pas obligatoire, l'utilisateur ne pourra pas se connecter si aucun mot de passe n'est défini.
- **Confirmer le mot de passe** Saisissez à nouveau le mot de passe du champ ci-dessus pour le vérifier. Ce champ est obligatoire lorsque vous avez rempli le champ Nouveau mot de passe.
- **Email** Entrez une adresse email pour l'utilisateur.
- **Date d'inscription** Date d'inscription de l'utilisateur.
- **Date de dernière visite** Date de la dernière visite de l'utilisateur sur le site.
- **Date de dernier réinitialisation** Date et heure de la dernière réinitialisation du mot de passe.
- **Nombre de réinitialisations de mot de passe** Nombre de réinitialisations de mot de passe depuis la dernière réinitialisation.
- **Recevoir les emails système** (*Oui*/*Non*) Si défini sur oui, l'utilisateur recevra les emails système.
- **Statut de l'utilisateur** (*Bloqué*/*Activé*) Activez ou bloquez cet utilisateur.
- **Exiger la réinitialisation du mot de passe** (*Oui*/*Non*) Si défini sur oui, l'utilisateur devra réinitialiser son mot de passe lors de sa prochaine connexion sur le site.
- **ID** Numéro d'enregistrement dans la base de données.

### Onglet Groupes d'utilisateurs assignés

![user edit assigned user groups tab](../../../fr/images/users/users-edit-assigned-user-groups-tab.png)

La valeur par défaut est *Enregistré* mais peut être modifiée dans la page *Utilisateur : Options*.

### Paramètres de base

![user edit basic settings tab](../../../fr/images/users/users-edit-basic-settings-tab.png)

- **Style de modèle Backend** Sélectionnez un style de modèle pour l'interface Backend de l'administrateur. Cela n'affectera que cet utilisateur.
- **Langue Backend** Sélectionnez la langue pour l'interface Backend de l'administrateur. Cela n'affectera que cet utilisateur.
- **Langue Frontend** Sélectionnez la langue pour l'interface frontend. Cela n'affectera que cet utilisateur.
- **Éditeur** Sélectionnez un éditeur pour cet utilisateur. Le défaut est TinyMCE sauf modifié dans la Configuration Globale.
- **Fuseau horaire** Il existe une longue liste de fuseaux horaires organisés par continent, avec l'Europe vers la fin. Le fuseau horaire par défaut du site est défini dans la Configuration Globale.

### Paramètres d'accessibilité

![user edit accessibility settings tab](../../../fr/images/users/users-edit-accessibility-settings-tab.png)

- **Monochrome** Oui/Non
- **Contraste élevé** Oui/Non
- **Surligner les liens** Oui/Non
- **Augmenter la taille de la police** Oui/Non

### Options du journal des actions de l'utilisateur

Cet onglet est disponible uniquement pour les Super Utilisateurs !

- **Envoyer des notifications pour le journal des actions de l'utilisateur** Si défini sur oui, l'utilisateur recevra des notifications du journal des actions par email.
- **Sélectionner les événements à notifier** Sélectionnez les notifications du journal des actions de l'utilisateur à envoyer par email.

### Authentification Web du W3C (WebAuthn)

Cet onglet est présent uniquement lorsque le site est accessible via HTTPS. Pour configurer une connexion sans mot de passe, vous aurez besoin d'un appareil matériel, disponible sur Amazon et autres commerces pour environ 15 £, ou d'un appareil avec reconnaissance d'empreintes digitales, de visage ou similaire. Vous pouvez ajouter plusieurs authentificateurs. Une fois configuré, vous pouvez vous connecter en cliquant sur le bouton d'authentification Web dans le formulaire de connexion et en appuyant sur le bouton de l'appareil lorsque cela est demandé.

Cet onglet est présent mais ne peut pas être utilisé dans le formulaire d'édition de l'utilisateur car la connexion sans mot de passe ne peut être configurée que par l'utilisateur individuel via le formulaire d'édition du profil.

### Jeton API Joomla

Cet onglet est utilisé pour gérer les jetons de sécurité utilisés pour authentifier à l'application API Joomla (accès distant à votre site). Si vous ne savez pas ce que cela fait, il y a de fortes chances que vous n'en ayez pas besoin et pouvez ignorer ces paramètres en toute sécurité.

Le jeton n'est visible que pour votre propre compte.

### Authentification multi-facteurs

![user edit multi factor authentication tab](../../../fr/images/users/users-edit-multi-factor-authentication-tab.png)

Cet onglet vous permet de configurer une ou plusieurs méthodes pour permettre l'accès à votre compte après connexion avec le nom d'utilisateur et le mot de passe. Il n'est présent que lorsque vous éditez votre propre profil. Plusieurs méthodes sont disponibles. Si vous perdez l'accès à une méthode pour une raison quelconque, vous pouvez choisir une autre méthode à partir de l'écran de vérification post-connexion. Les méthodes alternatives doivent avoir été configurées à l'avance !

#### Codes de secours

Cette méthode génère un ensemble de numéros que vous pouvez enregistrer ou imprimer. Chaque numéro ne peut être utilisé qu'une seule fois, alors n'oubliez pas de mettre à jour votre liste après utilisation.

#### Code de vérification

Un formulaire supplémentaire à remplir avec des méthodes alternatives de configuration du code. Jetez un coup d'œil et cliquez sur le bouton Annuler si vous décidez de ne pas procéder.

#### Clé Yubi

Ceci est pour un autre type de clé matérielle qui fournit un code sur un écran d'affichage. Jetez un coup d'œil et sélectionnez Annuler si vous décidez de ne pas procéder.

#### Authentification Web

Pour un dispositif matériel avec un bouton à presser. Jetez un coup d'œil et sélectionnez Annuler si vous décidez de ne pas procéder. Notez que cette méthode sera contournée si vous utilisez la méthode de connexion WebAuthn séparée.

#### Code par email

Avec cette méthode, un code est envoyé à votre adresse email. Vous serez invité à entrer ce code pour accéder au site. C'est un code à usage unique. Un nouveau est envoyé pour chaque connexion. Jetez un coup d'œil et sélectionnez Annuler si vous décidez de ne pas procéder.

## Conseils

- Le nom, le nom de connexion et l'email sont obligatoires.
- Si vous n'avez pas rempli une langue particulière, un éditeur, un site d'aide et/ou
  un fuseau horaire, les paramètres par défaut de la configuration globale,
  du gestionnaire de langue et/ou du gestionnaire de modèles sont utilisés.

*Traduit par openai.com*


<!-- Filename: Help4.x:Mass_Mail_Users  / Display title: Envoi en masse aux utilisateurs -->


## Description

La page *Mass Mail Users* permet aux membres du groupe *Super Users* d'envoyer un message
par e-mail aux utilisateurs enregistrés du site. Les destinataires peuvent être sélectionnés
en fonction des groupes d'utilisateurs.

### Éléments communs

Certains éléments de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).

## Comment accéder

Sélectionnez **Utilisateurs → Utilisateurs de courriers en masse** dans le menu Administrateur.

## Capture d'écran

![utilisateurs de courrier de masse](../../../fr/images/users/mass-mail-users.png)

## Détails et Message

- **Envoyer aux groupes enfants** Définir si l'Email doit être envoyé aux membres de tous les groupes enfants du groupe sélectionné. Par exemple, si cette case est cochée et que le groupe *Public* est sélectionné, l'Email serait envoyé à presque tous les utilisateurs, puisque la plupart des groupes sont des groupes enfants de *Public*.
- **Envoyer en mode HTML** Définir si l'Email doit être envoyé avec des en-têtes qui l'identifient comme document HTML. Les clients de messagerie qui supportent cela afficheront tous les codes HTML.
- **Envoyer aux utilisateurs désactivés** Si coché, les utilisateurs désactivés seront inclus lors de l'envoi du mail.
- **Destinataires en BCC** Si coché, tous les destinataires seront inclus en tant qu'entrées BCC, de sorte qu'aucun ne verra les adresses Email des autres destinataires. Comme de nombreux routeurs de messagerie traitent les Emails sans entrée *A:* comme du spam, l'Email du site sera utilisé pour l'entrée *A:*.
- **Groupe** Sélectionnez les groupes auxquels vous souhaitez envoyer l'Email.
- **Sujet** Entrez l'objet de l'Email. Essayez de le rendre aussi descriptif que possible. Tout texte saisi dans le paramètre *Préfixe Objet* dans Options (Options Utilisateurs → Mass Mail) sera placé devant l'objet que voussaisissez ici.
- **Message** Entrez le corps de l'Email. Tout texte saisi dans le paramètre *Suffixe Corps du Mail* dans Options (Options Utilisateurs → Mass Mail) sera ajouté au texte que vous saisissez ici.

*Traduit par openai.com*


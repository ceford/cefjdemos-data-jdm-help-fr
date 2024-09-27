<!-- Filename: Help4.x:Privacy_Dashboard  / Display title: Tableau de bord de confidentialité -->

## Description

La page du *Tableau de bord de la confidentialité* liste le type de demande de confidentialité de l'utilisateur, le statut et le nombre de demandes.

### Tutoriels

- [Aperçu de la conformité - Contenu et flux de travail](https://docs.joomla.org/Help4.x:Components_Privacy_Outline/en)
- [La suite d'outils de confidentialité](https://docs.joomla.org/J3.x:Privacy/en)
  (Tutoriel détaillé de Joomla 3)
- [Flux de travail des demandes d'information](https://docs.joomla.org/J3.x:Information_Request_Workflow_in_Privacy_Component/en)
  (Tutoriel détaillé de Joomla 3)

## Comment accéder

- Sélectionnez **Utilisateur → Icône du tableau de bord de confidentialité** dans le menu Administrateur.

## Capture d'écran

![tableau de bord de confidentialité](../../../fr/images/privacy/privacy-dashboard.png)

## Panneaux de Tableau de Bord

### État de Confidentialité

- **Politique de Confidentialité Publiée** Indique si une Politique de Confidentialité est disponible. Naviguez vers *Extensions → Système - Consentement à la Confidentialité* et sélectionnez votre article de Confidentialité. Une fois publié, vous pouvez modifier votre article de Politique de Confidentialité à partir de cette page.
- **Élément de Menu du Formulaire de Demande Publié** Indique si l'Élément de Menu (qui permet aux utilisateurs d'envoyer des demandes) est publié ou non publié. Pour le créer, naviguez vers votre Menu → Ajouter un nouvel élément de menu → Type d'élément de menu : Créer une demande. Une fois publié, vous pouvez modifier votre élément de menu depuis cet écran.
- **Demandes Urgentes en Attente** Nombre de demandes urgentes plus anciennes que le nombre de jours définis dans les Options du Composant (de 10 à 29 jours).
- **Envoi d'E-mails Activé**
- **Chiffrement de la connexion à la base de données**

### Demandes de Confidentialité

- **Type de Demande** Affiche les deux types de demandes différents
  - *Exporter* lorsqu'un utilisateur a envoyé une demande d'exportation de ses données
  - *Supprimer* lorsqu'un utilisateur a envoyé une demande de suppression.
- **Statut** Affiche le statut de la demande
  - *Invalide* un Super Utilisateur a invalidé la demande
  - *En attente* lorsqu'un utilisateur a envoyé une demande mais n'a pas encore confirmé sa demande. Les utilisateurs ont 2 façons de confirmer : en visitant l'URL mentionnée dans l'e-mail envoyé à l'utilisateur ou en copiant le jeton de l'e-mail et en le collant dans le formulaire à l'URL donnée. Le jeton est valable pendant 24 heures.
  - *Confirmée* l'utilisateur a confirmé sa demande.
  - *Terminée* un Super Utilisateur a complété la demande
- **\# de demandes** Affiche le nombre de demandes pour chaque type. Ce bloc affiche également le nombre total de demandes et le nombre de demandes actives.

## Conseils

- Sélectionnez un type de demande pour voir la liste des demandes de ce type.

*Traduit par openai.com*


<!-- Filename: Help5.x:Scheduled_Tasks:_Edit / Display title: Modifier la tâche -->

## Description

Chaque tâche a ses propres paramètres liés à la tâche situés dans l'onglet *Nouvelle ou Modifier la tâche* du formulaire Modifier la tâche. Les champs devraient être explicites. Les onglets supplémentaires du formulaire sont communs à toutes les tâches.

### Éléments Communs

Certains aspects de cette page sont couverts dans des articles d'aide distincts :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet Permissions](jdocmanual?article=help/common-elements/edit-permissions).

## Comment accéder

- Sélectionnez **Système → Gérer → Tâches planifiées** et appuyez sur le bouton *+ Nouveau* dans la barre d'outils. Ou...
- Sélectionnez **Système → Gérer → Tâches planifiées** et choisissez une tâche dans la liste.

## Notification de mise à jour de Joomla!

Cette tâche vérifie périodiquement la disponibilité de nouvelles versions de Joomla!. Lorsqu'une est trouvée, elle vous envoie un email, vous rappelant de mettre à jour. Vous pouvez personnaliser l'email dans Système → Modèles d'e-mail.

![joomla update notification parameters](../../../fr/images/maintenance/scheduled-tasks-types-joomla-update-notofication.png)

### Onglet Avancé

![joomla update notification advanced tab parameters](../../../fr/images/maintenance/scheduled-tasks-types-advanced-tab.png)

### Onglet Historique d'exécution

![joomla update notification execution history tab parameters](../../../fr/images/maintenance/scheduled-tasks-types-exec-history-tab.png)

### Onglet Détails

![joomla update notification details tab parameters](../../../fr/images/maintenance/scheduled-tasks-types-details-tab.png)

## Supprimer les journaux d'action

Supprimer les journaux d'actions après un nombre de jours spécifié.

![joomla update notification parameters](../../../fr/images/maintenance/scheduled-tasks-types-delete-action-logs.png)

## Expiration des consentements de confidentialité

Gérer l'expiration des consentements de confidentialité.

![joomla update notification parameters](../../../fr/images/maintenance/scheduled-tasks-types-privacy-consent.png)

## Requête GET

Effectuer des requêtes GET à un serveur. Prend en charge un délai d'attente personnalisé et des en-têtes d'autorisation.

![joomla update notification parameters](../../../fr/images/maintenance/scheduled-tasks-types-get-request.png)

## Enregistrement Global

Vérifier les articles empruntés.

![joomla update notification parameters](../../../fr/images/maintenance/scheduled-tasks-types-global-check-in.png)

## Vérification de la taille de l'image

Vérifiez les images, redimensionnez si elles sont plus grandes que la taille autorisée. Attention : Le fichier original sera écrasé !

![joomla update notification parameters](../../../fr/images/maintenance/scheduled-tasks-types-image-size-check.png)

- **Répertoire** Le répertoire de l'image à vérifier, peut-être sampledata, bannières ou en-têtes.

- ** Dimension** La dimension de l'image à vérifier, largeur et hauteur.

## Faire tourner les journaux

Fait pivoter périodiquement les fichiers journaux.

![joomla update notification parameters](../../../fr/images/maintenance/scheduled-tasks-types-rotate-logs.png)

## Purge des données de session

Plugin de tâche qui purge les données et métadonnées expirées en fonction du gestionnaire de session défini dans la Configuration Globale.

![joomla update notification parameters](../../../fr/images/maintenance/scheduled-tasks-types-session-data-purge.png)

## Mettre le site hors ligne

Définit le statut du site sur hors ligne à chaque exécution.

![joomla update notification parameters](../../../fr/images/maintenance/scheduled-tasks-types-set-site-offline.png)

## Mettre le site en ligne

Définit l'état du site sur en ligne à chaque exécution.

![joomla update notification parameters](../../../fr/images/maintenance/scheduled-tasks-types-set-site-online.png)

## Activer/Désactiver Hors-ligne

Bascule le statut du site à chaque exécution.

![joomla update notification parameters](../../../fr/images/maintenance/scheduled-tasks-types-toggle-offline.png)

*Traduit par openai.com*


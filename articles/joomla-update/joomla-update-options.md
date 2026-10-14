<!--
{
    "source": "https://docs.joomla.org/Help4.x:Joomla_Update:_Options",
    "title": "Mise \u00e0 jour de Joomla : options",
    "description": " ",
    "author": ""
}
-->

## Description

La page Mise à jour de Joomla : options est utilisée pour définir les paramètres 
qui contrôlent le processus de mise à jour du cœur de Joomla.

### Éléments courants

Certains aspects de cette page sont présentés dans des articles d’aide distincts :

* [Barres d’outils](jdocmanual?article=help/common-elements/toolbars)

## Comment y accéder

- Sélectionnez **Système → Panneau de mise à jour → Joomla** dans le menu d’administration. Ensuite...
  - Sélectionnez le bouton **Options** dans la barre d’outils.

## Capture d’écran

![Options de mise à jour de Joomla - Source de mise à jour](../../../fr/images/joomla-update/joomla-update-options/01-update-source.png)

## Champs du formulaire

### Onglet Source de mise à jour

- **Canal de mise à jour**
  - **Par défaut** Ce paramètre permet à Joomla d’afficher une notification lorsqu’une nouvelle version mineure ou corrective est disponible pour la version majeure actuelle. 
  - **Joomla Next** Ce paramètre permet à Joomla d’afficher une notification lorsqu’une nouvelle version majeure stable est disponible et que toutes les versions mineures et extensions existantes sont à jour.
  - **URL personnalisée** Pour les développeurs Joomla. D’autres champs apparaîtront.
- **Stabilité minimale** Niveau minimal de stabilité des mises à jour d’extensions que vous souhaitez voir. Development est le niveau le moins stable, tandis que Stable correspond à une qualité de production. Si une extension ne spécifie pas de niveau, elle est considérée comme Stable.
  - **Development** Pour les sites des développeurs Joomla.
  - **Alpha** Pour les sites de test Alpha.
  - **Beta** Pour les sites de test Beta.
  - **Release Candidate** Pour les sites de test des versions candidates.
  - **Stable** Pour les sites de production.
- **URL personnalisée** Si une URL personnalisée a été sélectionnée dans le canal de mise à jour, un champ permettant de saisir l’URL apparaît ici.
- **Case à cocher des extensions potentiellement incompatibles** Affiche la case à cocher lors de la vérification préalable à la mise à jour si l’une des extensions installées sur votre site est potentiellement incompatible avec la version de Joomla vers laquelle vous effectuez la mise à niveau. 
  *Remarque :* la case à cocher est affichée lors de la mise à niveau vers une nouvelle famille de versions de Joomla (version mineure ou majeure).
- **Case à cocher de confirmation de sauvegarde** Affiche la case à cocher permettant de confirmer que vous avez effectué une sauvegarde et que vous êtes prêt à mettre à jour lors de la dernière étape, avant que la mise à jour ne soit réellement appliquée. 

### Onglet Mises à jour automatisées

*Les mises à jour automatisées sont disponibles à partir de Joomla 5.4 pour les sites qui sont accessibles publiquement sur Internet. Si votre site se trouve derrière un pare-feu ou n’est pas accessible publiquement, par exemple dans un environnement de test local, vous devrez effectuer la mise à jour manuellement.*

![Options de mise à jour de Joomla - Source de mise à jour](../../../fr/images/joomla-update/joomla-update-options/02-automated-updates.png)

- **Mise à jour automatisée** Lorsque cette option est définie sur *Oui*, votre site est automatiquement mis à jour vers la dernière version mineure ou corrective (y compris les correctifs de sécurité) dès qu’elle devient disponible. Les versions majeures ne sont pas incluses.
- **Jeton de mise à jour** Il s’agit d’un jeton qui identifie ce site. Il est créé par le serveur distant de mise à jour de Joomla et ne peut pas être modifié par l’utilisateur.
- **Dernière vérification** Date la plus récente à laquelle votre site a contacté le serveur de mise à jour.
- **Envoyer un e-mail aux groupes d’utilisateurs** Tous les utilisateurs des groupes sélectionnés recevront des e-mails concernant les mises à jour automatisées réussies ou échouées. Si aucun utilisateur n’est trouvé, les e-mails sont envoyés à tous les super utilisateurs. Les destinataires doivent avoir activé l’option Recevoir les e-mails système.

Veuillez utiliser le bouton *Afficher l’aide en ligne* pour plus de détails.

*Traduit par openai.com*
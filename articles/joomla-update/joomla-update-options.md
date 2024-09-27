```markdown
<!-- Filename: Help4.x:Joomla_Update:_Options  / Display title: Mise à jour Joomla : Options -->
```

## Description

La page Options de mise à jour de Joomla est utilisée pour définir les paramètres afin de contrôler le processus de mise à jour du noyau de Joomla.

### Éléments Communes

Certains aspects de cette page sont abordés dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars)

## Comment accéder

- Sélectionnez **Système → Panneau de mise à jour → Joomla** depuis le menu Administrateur. Ensuite...
  - Sélectionnez le bouton **Options** dans la barre d’outils.

## Capture d'écran

![Options de mise à jour de Joomla](../../../fr/images/joomla-update/joomla-update-options.png)

## Champs de Formulaire

### Onglet Source de Mise à Jour

- **Canal de Mise à Jour**
  - **Par Défaut** Ce paramètre permet à Joomla d'afficher une notification lorsqu'une nouvelle version mineure ou corrective est disponible pour la version majeure actuelle. 
  - **Joomla Prochain** Ce paramètre permet à Joomla d'afficher une notification lorsqu'une nouvelle version majeure stable est disponible et que toutes les versions mineures et extensions existantes sont à jour.
  - **Test** Pour les testeurs Joomla. Plus de champs apparaîtront.
  - **URL Personnalisée** Pour les développeurs Joomla. Plus de champs apparaîtront.
- **Stabilité Minimale** La stabilité minimale des mises à jour d'extension que vous souhaitez voir. Développement est le moins stable, Stable est de qualité production. Si une extension ne spécifie pas de niveau, elle est supposée être Stable.
  - **Développement** Pour les sites de développeurs Joomla.
  - **Alpha** Pour les sites de test Alpha.
  - **Beta** Pour les sites de test Beta.
  - **Release Candidate** Pour les sites Release Candidate.
  - **Stable** Pour les sites de production.
- **Case à cocher extensions potentiellement incompatibles** Affiche la case à cocher dans la vérification pré-mise à jour si l'une des extensions installées sur votre site est potentiellement incompatible avec la version de Joomla vers laquelle vous effectuez la mise à niveau. *Remarque:* la case à cocher s'affiche lors de la mise à niveau vers une nouvelle famille de versions Joomla (version mineure ou majeure).
- **Case à cocher de confirmation de sauvegarde** Affiche la case à cocher pour confirmer que vous avez effectué une sauvegarde et que vous êtes prêt à mettre à jour à l'étape finale avant que la mise à jour ne soit effectivement appliquée.

*Traduit par openai.com*


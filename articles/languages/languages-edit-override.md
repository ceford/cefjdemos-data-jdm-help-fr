<!-- Filename: Help4.x:Languages:_Edit_Override / Display title: Langues : Substitutions de traduction -->

## Description

Dans le code Joomla, les chaînes de texte qui doivent apparaître dans l'Interface Utilisateur, que ce soit l'interface du Site ou l'interface de l'Administrateur, sont exprimées sous forme de constantes de chaîne. Par exemple, la chaîne *Votre session a expiré. Veuillez vous reconnecter.* est exprimée par
`JLIB_ENVIRONMENT_SESSION_EXPIRED`. La chaîne de texte peut être traduite dans n'importe quelle langue. La langue par défaut est l'anglais britannique. Il y a des milliers de telles chaînes dans une installation Joomla.

Si une chaîne ne convient pas à votre site, vous pouvez utiliser la fonctionnalité de remplacement de langue pour remplacer l'originale. La page *Langues : Remplacements* affiche une liste des remplacements existants, elle est donc vide initialement.

### Éléments Communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).

## Comment Accéder

- Sélectionnez **Système → Gérer le Panneau → Remplacements de Langue**. Ensuite...
  - Sélectionnez une **Langue et Client** dans la liste déroulante. Ensuite...
    - Sélectionnez le bouton **Nouveau** dans la barre d'outils pour créer un nouveau remplacement.
      Ou...
    - Sélectionnez le lien constant dans la colonne **Constante** pour modifier un remplacement existant.

## Capture d'écran

![Substitution de l'édition des langues](../../../fr/images/languages/languages-edit-override.png)

## Champs de Formulaire

### Panneau de Droite : Recherchez le texte que vous souhaitez modifier

- **Rechercher** Commencez ici ! Vous êtes plus susceptible de connaître la Valeur
  (expiré) que la Constante (`_EXPIRED`). Dans tous les cas, la recherche est
  insensible à la casse pour une partie du texte.
- **Texte de Recherche** Entrez le texte à rechercher et sélectionnez le bouton *Rechercher*.
- **Résultats de Recherche** Une liste de chaînes contenant le terme recherché
  apparaît dans un panneau de résultats séparé sous le Panneau de Droite. Sélectionnez 
  celui que vous recherchez. La constante et le texte seront copiés dans le
  *panneau de gauche* pour être mis à jour et sauvegardés.

### Panneau de Gauche : Créer une Nouvelle Substitution ou Modifier cette Substitution

- **Langue** et **Emplacement** Ces éléments ont été sélectionnés avant d'ouvrir ce
  formulaire d'édition et ne peuvent pas être modifiés.
- **Constante de Langue** C'est la chaîne utilisée dans le code par le
  développeur. Si la valeur n'existe pas dans le code, la chaîne ne sera
  jamais utilisée.
- **Texte** C'est ici que vous remplacez le terme par défaut par votre
  version.
- **Pour les Deux Emplacements** Sélectionnez pour appliquer la substitution à la fois au front end et
  au back end.
- **Fichier** Cela indique où se trouve le fichier de substitution dans le système de fichiers. Vous pourriez avoir besoin de connaître cette information pour le dépannage.

*Traduit par openai.com*


<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Content_Group  / Display title: Groupe de Contenu -->

## Description du Groupe

### Contenu - Confirmer le Consentement

![Plugin de confirmation du consentement du contenu](../../../en/images/plugins/plugin-group-content-confirm-consent.png)

- **Courte Politique de Confidentialité** Bref avis du texte qui sera affiché au-dessus de la case à cocher de consentement de confidentialité.
- **Article de Confidentialité** Si nécessaire, sélectionnez/créez votre article de confidentialié pour le lier à votre formulaire.

Pour plus d’informations, consultez le guide de configuration du plugin de consentement de confidentialité.

### Contenu - Contact

![Plugin de contact du contenu](../../../en/images/plugins/plugin-group-content-contact.png)

- **Redirection** Vous pouvez lier le nom de l’auteur à :
  - La page de contact associée.
  - La page Web spécifiée dans le profil de contact associé.
  - L’email spécifié dans le profil de contact associé.
- **Appliquer le lien également au nom d’alias** Lier les données utilisateur réelles même si un alias d’auteur est défini dans les options de l’article.

### Contenu - Masquage des Emails

Ce plugin masque tous les e-mails dans le contenu en utilisant JavaScript pour déjouer les spambots. Cela aide à empêcher les e-mails contenus dans les articles d'être ajoutés aux listes de spam. Vous pouvez désactiver le masquage des e-mails dans un article en insérant {emailcloak=off} n'importe où dans le texte de l'article. Dans ce cas, aucune adresse e-mail dans l'article ne sera masquée par ce plugin.

![Plugin de masquage des emails du contenu](../../../en/images/plugins/plugin-group-content-email-cloaking.png)

- **Mode** Comment les e-mails seront affichés. Les options sont *Comme adresse mailto cliquable* ou comme *Texte non cliquable*.

### Contenu - Champs

Ce plugin vous permet d’afficher un champ personnalisé qui a été inséré avec le plugin *Bouton - Champs* ou en utilisant la syntaxe : `{field #}` directement dans la zone de l’éditeur. Syntaxe :

- **`{field 1}`** affichera le champ avec l’ID 1.
- **`{field 1,foo}`** affichera le champ sélectionné en utilisant la mise en page alternative `foo`.
- **`{fieldgroup 2}`** affichera tous les champs dans le groupe de champs avec l’ID 2.

### Contenu - Joomla

![Plugin de contenu Joomla](../../../en/images/plugins/plugin-group-content-joomla.png)

- **Vérifier la Suppression de Catégorie** Vérifiez que les catégories sont complètement vides avant qu'elles ne soient supprimées.
- **Email à la Création d’un Nouvel Article sur le Site** Envoyez un e-mail aux utilisateurs si *Envoyer un e-mail* est *Activé* lorsqu'un nouvel article est soumis via le Frontend.

### Contenu - Modules de Chargement

Ce plugin vous permet de placer un Module à l’intérieur d’un Article avec la syntaxe : `{loadposition xx}`, où `xx` est un code de position défini par l'utilisateur. Par exemple, si vous créez un Module avec la valeur de position `myposition1`, alors taper le texte `{loadposition myposition1}` dans un Article affichera ce Module à cet endroit dans l'Article.

![Plugin de chargement des modules de contenu](../../../en/images/plugins/plugin-group-content-load-modules.png)

- **Style** Le Style pour le Module chargé.

### Contenu - Saut de Page

Ce plugin ajoute une fonctionnalité de table des matières à un Article paginé. Cela se fait automatiquement à l’aide du bouton Saut de Page ajouté à la partie inférieure du panneau de texte dans un Article. Le code HTML est inclus ici en référence à ce qui est disponible. Le saut de page s’affichera lui-même dans la fenêtre de texte sous forme de simple ligne horizontale.

![Plugin de saut de page du contenu](../../../en/images/plugins/plugin-group-content-page-break.png)

- **Afficher le Titre du Site** Indiquer si le titre et les attributs de titre provenant du plug-in seront ajoutés à la balise Titre du Site.
- **Titre de l'Index des Articles** Afficher ou masquer le titre de l’index des articles. Le titre s'affiche en haut de la table des matières.
- **Titre Personnalisé de l'Index des Articles** Entrez un texte personnalisé pour le titre de l'index des articles. Si vide, le standard sera utilisé.
- **Table des Matières** Indiquer si une table des matières pour les Articles multipages doit être masquée ou affichée.
- **Afficher Tout** Indiquer si les Utilisateurs ont l’option d’afficher toutes les pages d’un Article.
- **Style de Présentation** Afficher l'article avec des pages séparées, des onglets ou des curseurs.

![Description du plugin de saut de page](../../../en/images/plugins/plugin-group-content-page-break-description.png)

### Contenu - Navigation de Page

Ce plugin vous permet d’ajouter des liens de navigation Suivant & Précédent aux Articles, par exemple en utilisant une disposition de blog ou de liste. Cette fonctionnalité peut être contrôlée avec les paramètres Joomla! ci-dessous :

- **Afficher la Navigation** dans l'Article - Écran de Configuration Globale
- **Afficher la Navigation** dans les paramètres - Section composant de l'élément de menu - Nouveau/Modifier - Paramètres - Composant pour l’écran des dispositions des Articles.

Notez que, si le plugin de navigation de page est désactivé dans cet écran, aucune navigation de page ne sera affichée et les paramètres ci-dessus n'auront aucun effet.

![Plugin de navigation de page du contenu](../../../en/images/plugins/plugin-group-content-page-navigation.png)

- **Position** Position du lien de navigation. Les options sont *Au-dessus* de l’Article ou *En-dessous* de l’Article.
- **Relatif à** Assigne l’emplacement relatif pour les paramètres de Position. Text le placera directement au-dessus ou en-dessous du contenu de l'article. Full Article le placera au-dessus ou en-dessous de l'affichage complet, y compris le titre et lire la suite.
- **Texte du Lien** Choisissez ce qui sera affiché comme texte du lien.

### Contenu - Recherche Intelligente

Les modifications apportées au contenu ne mettront pas à jour l’index de Recherche Intelligente si vous n’activez pas ce plugin.

### Contenu - Vote

![Plugin de vote du contenu](../../../en/images/plugins/plugin-group-content-vote.png)

- **Position** Position du vote.

*Translated by openai.com*


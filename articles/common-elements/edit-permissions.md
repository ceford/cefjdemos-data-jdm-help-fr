<!-- Filename: Help4.x:Edit_Permissions  / Display title: Modifier les autorisations  -->

## Objectif

De nombreuses extensions ont des écrans de modification avec un onglet Permissions qui est utilisé pour changer les permissions allouées aux Groupes d'Utilisateurs. Le nombre de Groupes d'Utilisateurs peut varier car des Groupes d'Utilisateurs personnalisés peuvent être ajoutés pour des finalités spéciales. Le nombre d'Actions pouvant être modifiées varie également selon l'extension. Cet article est une brève description des écrans de permissions pour de telles finalités spéciales.

Imaginez qu'il y a un utilisateur qui s'occupe des Médias (images et fichiers) mais qui n'a aucune autre responsabilité. Un groupe nommé Oddjob a été créé et assigné au niveau d'accès Spécial. Un utilisateur également nommé Oddjob a été créé et assigné au groupe Oddjob.

Pour plus d'informations détaillées sur les Groupes d'Utilisateurs, les Niveaux d'Accès et les Permissions, il existe un tutoriel séparé sur [Contrôle d'Accès](jdocmanual?article=user/users/access-control).

## Autorisations de Configuration Globale

Dans cet exemple, les utilisateurs du groupe Oddjob ont reçu l'autorisation
globale de se connecter à l'interface Administrateur, mais rien d'autre.

![Capture d'écran des Autorisations](../../../fr/images/common-elements/global-configuration-permissions-tab.png)

## Configuration des Permissions des Composants

Pour accéder à un composant spécifique, les permissions doivent être définies dans les options du composant. Dans cet exemple, les options du composant Média.

![Capture d'écran Média](../../../fr/images/common-elements/media-options-permissions-tab.png)

Vous remarquerez que ce composant dispose de moins d'actions disponibles et que le groupe Oddjob a juste assez de permissions pour faire le travail.

Pour changer les permissions pour ce composant :

* Sélectionnez le Groupe en cliquant sur son titre situé à gauche.<br>
    Trouvez l'action désirée.
    * Supprimer. Les utilisateurs peuvent supprimer cet article.
    * Modifier. Les utilisateurs peuvent modifier cet article.
    * Modifier l'état. L'utilisateur peut changer l'état publié et les informations connexes pour cet article.
* Sélectionnez la permission désirée pour l'action que vous souhaitez modifier.
    * Hérité. Héritée pour les utilisateurs de ce groupe à partir de la Configuration Globale, des Options des Articles, ou de la Catégorie des Articles.
    * Autorisé. Autorisé pour les utilisateurs de ce groupe. Remarque : Si cette action est Refusée à un des niveaux supérieurs, la permission Autorisée ici n'aura pas d'effet. Un paramètre Refusé ne peut pas être outrepassé.
    * Refusé. Refusé pour les utilisateurs de ce groupe.
* Cliquez sur Enregistrer dans la barre d'outils en haut. Lorsque l'écran se rafraîchit, la colonne Paramètre Calculé affichera la permission effective pour ce groupe et cette action.

## L'Expérience Utilisateur

Après la connexion, un utilisateur dans le groupe Oddjob verra les modules du Tableau de Bord Accueil qui ont l'accès **Spécial** défini et un lien vers l'élément de menu du composant Média.

![Tableau de Bord Accueil pour Oddjob](../../../fr/images/common-elements/home-dashboard-for-oddjob.png)

Et l'écran Média pour l'utilisateur Oddjob est comme prévu :

![Écran Média pour Oddjob](../../../fr/images/common-elements/media-screen-for-oddjob.png)

*Traduit par openai.com*


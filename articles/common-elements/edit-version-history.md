<!-- Filename: Help4.x:Components_Version_History  / Display title: Modifier l'historique des versions -->

## Description

Un popup de l'historique des versions affiche les versions précédentes de l'élément en cours de modification. Il est disponible pour les Articles, Bannières, Clients, Contacts, Flux d'actualités, Notes utilisateur et toutes les Catégories.

Chaque fois qu'un élément est sauvegardé, une nouvelle version est créée automatiquement. Le nombre de versions à conserver pour chaque élément est défini dans les Options du composant. Une ou plusieurs versions peuvent être marquées pour être conservées indéfiniment. Ces versions ne seront pas supprimées automatiquement même si le nombre maximal de versions indiqué dans les options est dépassé.

**Note :** Si la gestion des versions est utilisée, les champs personnalisés ne sont pas stockés dans différentes versions.

## Comment accéder

Sélectionnez le bouton **Versions** dans la barre d'outils d'une page de modification d'élément.

## Capture d'écran

![Popup de l'historique des versions](../../../fr/images/common-elements/articles-edit-versions.png)

## En-têtes de Colonne

- **Case à Cocher** Cochez cette case pour sélectionner un ou plusieurs articles. Pour sélectionner tous les articles, cochez la case dans l'en-tête de la colonne. Une fois les cases cochées, sélectionnez un bouton de la barre d'outils pour effectuer une action sur les éléments sélectionnés.
- **Date** L'heure et la date auxquelles la version a été sauvegardée. En sélectionnant ce lien, vous ouvrez l'Aperçu de cette version dans une fenêtre pop-up. Notez qu'une des dates sera suivie d'un symbole étoile. Cela indique que cette version est actuellement sauvegardée et en cours d'édition.
- **Note de Version** Une Note de Version peut être utilisée pour aider à identifier la nature des changements d'une version à l'autre. Une Note de Version saisie avant de sauvegarder un article apparaîtra dans cette colonne.
- **Conserver Pour Toujours** Cette colonne montre si la version a été marquée pour être Conservée Pour Toujours. Normalement, chaque version sera conservée selon les paramètres de la page des options du composant. Les paramètres par défaut sont de conserver un maximum de 10 versions antérieures pour un article. Lorsqu'un article est sauvegardé et qu'il a déjà 10 versions sauvegardées, la plus ancienne version est supprimée. Si une version est marquée comme Conserver Pour Toujours, elle ne sera pas comptée parmi les versions sauvegardées et ne sera pas supprimée lorsque le nombre maximum sera atteint.
  - Pour basculer l'état Conserver Pour Toujours, sélectionnez un bouton *Non* ou *Oui*, ou cochez la case de la version puis sélectionnez le bouton Conserver Activé/Désactivé dans la barre d'outils.
- **Auteur** L'utilisateur qui a sauvegardé cette version.
- **Nombre de Caractères** Le nombre total de caractères sauvegardés dans cette version. Notez que cela inclut les noms des colonnes de la base de données ainsi que les caractères effectivement tapés.

## Barre d'outils

- **Restaurer** La version actuelle de l'élément est marquée d'une étoile à droite de la Date. Pour restaurer l'une des autres versions sauvegardées, cochez la case correspondant à la version souhaitée et sélectionnez le bouton Restaurer. La version actuelle de l'élément sera remplacée par la version sélectionnée, et l'écran d'édition sera rechargé avec la version restaurée chargée dans l'éditeur.
- **Aperçu** Pour prévisualiser une version, sélectionnez soit la colonne Date de la version souhaitée, soit cochez la case et ensuite le bouton Aperçu. Une fenêtre popup distincte s'ouvrira montrant la version sélectionnée de l'élément.
- **Comparer** Pour comparer deux versions afin de voir ce qui a été modifié, cochez les cases de chacune des versions et ensuite le bouton Comparer. Une nouvelle fenêtre du navigateur s'ouvrira montrant une liste des champs modifiés et les changements effectués dans ces champs. 
  - La première colonne est le nom du champ, la deuxième est l'ancienne version, la troisième est la nouvelle version, et la dernière colonne met en évidence les différences entre les deux versions.
- **Garder On/Off** Ce bouton active ou désactive la fonction Garder pour toujours pour une version. Normalement, la plus ancienne version d'un élément sera supprimée automatiquement lorsque le nombre maximal de versions (défini dans les Options du composant) aura été dépassé. Si vous définissez la propriété Garder pour toujours pour une version, elle ne sera jamais supprimée automatiquement.
- **Supprimer** Ce bouton permet la suppression manuelle d'une ou plusieurs versions. Cochez la case pour les versions à supprimer et ensuite sélectionnez le bouton Supprimer. Notez que cela ne supprime *pas* l'élément en cours d'édition. Cela supprime uniquement l'historique des versions de l'élément.

*Traduit par openai.com*



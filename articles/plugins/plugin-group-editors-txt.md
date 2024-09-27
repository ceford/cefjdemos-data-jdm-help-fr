<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Editor_Group  / Display title: Groupe des éditeurs -->

## Description du groupe

Les plugins de l'éditeur aident les utilisateurs à entrer du texte avec des balises ou des mises en page pour des usages spécifiques, tels que des fragments de HTML ou de code. Pour utiliser un éditeur, le développeur de logiciel marque le champ de saisie de données comme type `Editor`. Si aucun plugin de l'éditeur n'est activé, cela est affiché comme une simple zone de texte. Avec un ou plusieurs plugins d'éditeur activés, le plugin par défaut du site est utilisé, défini dans la configuration globale, sauf s'il est remplacé par le plugin préféré de l'utilisateur, défini dans le profil de l'utilisateur. Joomla dispose des trois plugins d'éditeur de base listés ci-dessous. D'autres plugins d'éditeur tiers peuvent être disponibles. Certains éditeurs disposent d'une très grande sélection d'options.

### Éditeur - CodeMirror

L'éditeur CodeMirror est un éditeur de code qui offre un éditeur plus adapté au code source. Il propose une coloration syntaxique pour de nombreux langages de programmation. Il peut afficher les balises non appariées et aide également à maintenir une indentations cohérente du code.

![Options de CodeMirror](../../../en/images/plugins/plugin-group-editor-codemirror.png)

- **Numéros de liste** Afficher les numéros de ligne dans l'éditeur.
- **Repli de code** Permettre le repli des blocs de code.
- **Gouttières** Marqueurs de code et repli de code.
- **Surligner la ligne active** Ajoute une surbrillance à la ligne où se trouve le curseur.
- **Surligner les correspondances de sélection** Surligner les instances du mot sélectionné dans tout le document.
- **Correspondance des balises** Surligner les balises correspondantes.
- **Correspondance des crochets** Surligner les crochets correspondants.
- **Complétion des balises** Complétion automatique des balises.
- **Complétion des crochets** Complétion automatique des crochets.
- **Carte de touches** Faire fonctionner CodeMirror comme d'autres éditeurs populaires.
- **Basculer en plein écran** Sélectionner la touche de fonction à utiliser pour basculer en mode plein écran.
- **Utiliser des modificateurs** Sélectionner les touches de modification à utiliser avec la touche de bascule en plein écran.

![Options avancées de CodeMirror](../../../en/images/plugins/plugin-group-editor-codemirror-advanced.png)

- **Thème** Définit les couleurs pour l'éditeur.
- **Couleur de la ligne active** La couleur à utiliser pour surligner la ligne active. Sera affichée à 50% d'opacité.
- **Couleur des balises correspondantes** La couleur de fond à utiliser pour surligner les balises correspondantes. Sera affichée à 50% d'opacité.
- **Police** La police à utiliser dans l'éditeur. Si elle n'est pas installée, elle sera chargée depuis https://www.google.com/fonts/.
- **Taille de la police (px)** La taille de la police dans l'éditeur.
- **Hauteur de ligne (em)** La hauteur d'une ligne de texte. Cette valeur est en ems, ce qui signifie que 1,0 est égale à la taille de la police et 2,0 est égale à 2 fois la taille de la police.
- **Style de barre de défilement** Sélectionnez le style de barre de défilement que vous souhaitez que CodeMirror utilise.
- **Aperçu** Un exemple de ce à quoi ressembleront vos champs de l'éditeur CodeMirror avec les paramètres actuels (enregistrez pour mettre à jour).

### Éditeur - Aucun

Ce plugin charge un éditeur de texte de base. Cette option peut être utilisée lorsque vous collez du code HTML provenant d'une autre source et que vous ne souhaitez pas que le HTML soit altéré par un éditeur WYSIWYG. Ce plugin n'a aucune option.

### Éditeur - TinyMCE

L'éditeur TinyMCE est un éditeur WYSIWYG et est l'éditeur par défaut pour la saisie de HTML dans Joomla!.

![Options du plugin TinyMCE](../../../en/images/plugins/plugin-group-editor-tinymce.png)

- **Sélectionner l'onglet de sélection** Sélectionnez la fonctionnalité *Set 2*, *Set 1* ou *Set 0*. Avec *Set 2* sélectionné, vous voyez l'éditeur pour l'utilisation *Public*. *Set 1* est sélectionné par défaut pour les Managers et les Inscrits, *Set 0* est sélectionné par défaut pour les Administrateurs, les Éditeurs et les Super Utilisateurs.

Chaque onglet a une longue liste d'options qui ne sont pas illustrées ici. La liste suivante est une sélection.

- **Apparence du site** Choisissez l'apparence qui sera appliquée à l'éditeur TinyMCE lorsque celui-ci sera affiché sur votre site web.
- **Apparence de l'administrateur** Choisissez l'apparence qui sera appliquée à l'éditeur TinyMCE lorsque celui-ci sera affiché dans votre interface d'administration.
- **Mode de la barre d'outils** Contrôle la façon dont les boutons de la barre d'outils qui ne sont pas sur la première ligne seront affichés.
- **Glisser-déposer des images** Activer le glisser-déposer pour télécharger des images.
- **Répertoire des images** Le répertoire contenant les fichiers d'images, à lister par rapport au dossier d'images par défaut (défini dans Média > Options).
- **Encodage des entités** Contrôle comment les entités HTML sont encodées. Le réglage recommandé est `raw`. `named` = utilise l'encodage d'entité nommé (par exemple, `<`). `numeric` = utilise l'encodage HTML numérique (par exemple, `%03c`). raw = Ne pas encoder les entités HTML. Notez que la recherche de contenu peut ne pas fonctionner correctement si le réglage n'est pas `raw`.
- **Sélection automatique de la langue** Si Oui, la langue de l'éditeur correspondra automatiquement à la langue de l'interface utilisateur sélectionnée. Si la langue de TinyMCE n'existe pas, la langue de l'éditeur sera par défaut l'anglais.
- **Direction du texte** La langue se lit-elle de *Gauche à Droite* ou de *Droite à Gauche* (par exemple, comme l'arabe). La valeur par défaut est *Gauche à Droite*.
- **Classes CSS du modèle** Détermine s'il faut ou non charger le fichier *editor.css*. Si ce fichier n'est pas trouvé pour le modèle par défaut, le fichier *editor.css* du modèle système est utilisé. La valeur par défaut est *Oui*.
- **Classes CSS personnalisées** Chemin URL complet optionnel vers un fichier CSS personnalisé. Si ce champ est rempli, il remplace le paramètre Classes CSS du modèle.
- **URLs** Détermine s'il faut utiliser des URL relatives ou absolues pour les liens. La valeur par défaut est *Relative*.
- **Nouvelles lignes** Détermine si les nouvelles lignes doivent être interprétées comme des *Éléments P* ou des *Éléments BR*. La valeur par défaut est *Éléments P*.
- **Utiliser le filtre de texte Joomla** Si activé, le filtre de texte de la configuration globale de Joomla est appliqué pour chaque groupe d'utilisateurs. Si désactivé, les filtres définis ici sont utilisés pour tous les groupes d'utilisateurs.
- **Éléments interdits** Les éléments qui seront nettoyés du texte. La valeur par défaut est *applet*, ce qui supprimera les éléments applet du texte.
- **Éléments valides** Définit quels éléments resteront dans le texte édité lorsque l'éditeur sauvegarde (l'ensemble de règles par défaut pour cette option est un mélange des spécifications complètes HTML5 et HTML4).
- **Éléments valides étendus** Liste optionnelle des éléments HTML valides à ajouter à l'ensemble de règles existant.
- **Redimensionnement** Activer/désactiver le redimensionnement de la zone de l'éditeur (à la fois verticalement et horizontalement si le *Redimensionnement horizontal* est activé).
- **Redimensionnement horizontal** Activer/désactiver le redimensionnement horizontal.
- **Chemin de l'élément** Si activé, affiche les classes définies pour le texte marqué.
- **Nombre de mots** Activer/désactiver le comptage des mots.
- **Markdown** Permet l'utilisation de la syntaxe Markdown pour créer des liens, des listes et d'autres styles. Cette syntaxe spéciale est convertie et enregistrée en HTML régulier. Par exemple, l'utilisateur peut taper # texte pour produire un en-tête ou **texte** pour mettre le texte en gras.
- **Image avancée** Activer/désactiver une boîte de dialogue d'image avancée.
- **Liste avancée** Activer/désactiver la possibilité de définir des formats de numéros et des types de puces dans les listes ordonnées et non ordonnées.
- **Menu contextuel** Activer/désactiver le menu contextuel.
- **Plugin personnalisé** Ajouter des plugins TinyMCE personnalisés à l'éditeur en les spécifiant ici.
- **Bouton personnalisé** Ajouter des boutons TinyMCE personnalisés à l'éditeur en les spécifiant ici.

#### Onglet Avancé de TinyMCE

![Options avancées de TinyMCE](../../../en/images/plugins/plugin-group-editor-tinymce-advanced.png)

- **Nombre de jeux** Nombre de jeux pouvant être créés. Minimum 3.
- **Hauteur en HTML** La hauteur, en pixels, de la fenêtre contextuelle en mode HTML.
- **Largeur en HTML** La largeur, en pixels, de la fenêtre contextuelle en mode HTML.

*Traduit par openai.com*


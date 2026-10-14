<!--
{
    "source": "https://docs.joomla.org/Help4.x:Editors",
    "title": "\u00c9diteurs : introduction",
    "description": " ",
    "author": ""
}
-->

## TinyMCE

TinyMCE est l’éditeur par défaut pour les utilisateurs du site et de
l’administration. L’éditeur offre aux utilisateurs une interface familière
de traitement de texte à utiliser lors de la modification du
contenu.

TinyMCE peut être configuré avec 3 ensembles différents de boutons de barre d’outils. Cette
configuration s’effectue dans le plug-in Éditeur - TinyMCE.

### Barres d’outils

#### Préréglage simple

L’ensemble de barre d’outils 2 fournit une ligne de boutons, comme illustré ci-dessous. Cet ensemble est
attribué par défaut au groupe d’utilisateurs Public.

![Barre d’outils TinyMCE, ensemble 2](../../../fr/images/editors/editors/01-set-2.png)

- Les boutons permettent de mettre le texte en gras, de le souligner ou de le barrer.
- Annuler et rétablir.
- Liste non ordonnée, liste ordonnée.
- Coller en tant que texte : lors de la copie et du collage de texte provenant d’autres sources,
  telles que des fichiers PDF, des documents texte ou des pages web, le texte sélectionné
  contient des informations de mise en forme qui ne sont ni nécessaires ni souhaitées. L’utilisation de
  « Coller en tant que texte » supprime toute la mise en forme du texte.

#### Préréglage moyen

L’ensemble de barre d’outils 1 fournit deux lignes de boutons, comme illustré ci-dessous. Cet ensemble
est attribué par défaut aux groupes d’utilisateurs Gestionnaire et Enregistré.

![Barre d’outils TinyMCE, ensemble 1](../../../fr/images/editors/editors/02-set-1.png)

Cette option fournit tous les mêmes boutons que ceux décrits ci-dessus dans la barre d’outils de l’ensemble 2.
En outre, les options suivantes sont disponibles.

#### Moyen : ligne supérieure

- Contenu CMS : la liste déroulante permet de créer un lien vers un article,
  un contact, un champ, un média, un menu ou un module.

Article : cet exemple montre comment créer facilement un lien vers n’importe quel article du
site actuel.

![Boîte de dialogue de sélection de lien TinyMCE](../../../fr/images/editors/editors/03-link-button.png)

Pour créer un lien vers l’article souhaité :

- Placez le curseur à l’endroit de l’article où vous souhaitez insérer le
  titre de l’article lié.
- Cliquez sur le bouton Article pour ouvrir la fenêtre.
- Cliquez sur le titre pour sélectionner l’article souhaité dans la fenêtre. Vous
  pouvez utiliser la recherche et les filtres pour trouver l’article souhaité.
- Un lien portant le titre de l’article est inséré à l’emplacement actuel du curseur.
- Si nécessaire, vous pouvez modifier le texte du lien.

De la même manière, vous pouvez lier d’autres éléments tels que des médias, des modules, etc.

Saut de page : ce bouton permet d’insérer un saut de page dans un
article. Un saut de page permet la navigation entre les pages lorsque l’article est
affiché dans une mise en page. Cela est utile pour les articles longs. Lorsque ce
bouton est activé, une fenêtre s’affiche comme illustré ci-dessous :

![Formulaire de saut de page TinyMCE](../../../fr/images/editors/editors/04-pagebreak-button.png)

- **Titre de la page**. Saisissez le titre à afficher pour la nouvelle page (par
  exemple, « Page 2 »).
- **Alias de la table des matières**. Champ facultatif à afficher dans la table des
  matières de cette page. Dans un article multipage, Joomla affiche une
  « table des matières » pour la page, qui permet à l’utilisateur de sélectionner n’importe quelle
  page. Si ce champ est vide, le titre de la page sera utilisé. Si vous souhaitez un titre
  différent dans la table des matières, saisissez-le ici.
- **Insérer un saut de page**. Cliquez sur ce bouton pour insérer le saut de page avec
  les champs renseignés. Le saut de page s’affiche sous la forme d’une ligne grise en pointillés
  sur toute la largeur de l’article. Notez qu’un saut de page ne peut pas être modifié. Si vous
  devez modifier un champ du saut de page, cliquez dans l’article juste
  après le saut de page, appuyez sur Retour arrière jusqu’à ce que le saut de page soit supprimé,
  puis insérez un nouveau saut de page avec les informations souhaitées.
- La configuration s’effectue dans le plug-in Contenu - Saut de page.

Lire la suite : ce bouton insère une coupure « Lire la suite » dans l’article. Celle-ci
s’affiche sous la forme d’une ligne rouge en pointillés sur toute la largeur de l’article.

- Si un article comporte une coupure « Lire la suite », seul le texte situé avant la coupure,
  appelé texte d’introduction, s’affiche initialement, avec un lien Lire la suite. Si l’utilisateur
  clique sur ce lien, l’intégralité de l’article ou uniquement
  la partie située après le lien Lire la suite s’affiche. Cela dépend du
  réglage des paramètres du
  texte
  d’introduction pour l’article.
- La coupure « Lire la suite » permet d’économiser de l’espace sur les pages en affichant uniquement
  le texte d’introduction.
- Si vous souhaitez insérer des coupures dans un article affiché dans une mise en page d’article,
  utilisez le bouton Saut de page.

Les boutons de la liste déroulante de contenu CMS peuvent être désactivés dans
Plug-ins - editors-xtd.

- Les boutons en haut à gauche permettent de mettre le texte en italique. À côté se trouvent
  les boutons d’alignement à gauche, à droite, centré et justifié.
- Formats : sélectionnez des formats prédéfinis pour les titres, les éléments en ligne, les blocs, etc.
- Diminuer le retrait (déplacer vers la gauche) et augmenter le retrait (décaler vers la droite).
- 3 points : afficher la deuxième ligne de la barre d’outils.

#### Moyen : deuxième ligne

- Insérer/modifier un lien : pour insérer ou modifier un lien, sélectionnez le texte lié et
  appuyez sur ce bouton. Une boîte de dialogue contextuelle s’affiche et vous permet de saisir les
  détails du lien.
- Supprimer le lien : pour supprimer un lien, sélectionnez le texte lié et appuyez sur
  ce bouton.
- Ancre : une ancre est un signet à l’intérieur d’un article qui vous permet de créer un lien
  directement vers cet emplacement dans l’article.
- Code source : une fenêtre contextuelle s’affiche avec le code source HTML, ce qui vous permet de
  modifier le code source HTML.
- Insérer une ligne horizontale : pour insérer une ligne horizontale, placez le curseur
  à l’emplacement souhaité dans l’article et cliquez sur ce bouton.
- Tableau : insérer un nouveau tableau, propriétés de ligne du tableau, propriétés de cellule du tableau,
  insérer une ligne avant, insérer une ligne après, supprimer une ligne, insérer une colonne avant,
  insérer une colonne après, supprimer une colonne, scinder les cellules fusionnées du tableau, fusionner
  les cellules du tableau.
- Indice, exposant, caractère spécial.
- Prévisualiser le texte dans une fenêtre contextuelle.

#### Préréglage avancé

L’ensemble de barres d’outils 0 fournit les options de modification les plus complètes, comme indiqué
ci-dessous. Cet ensemble est attribué par défaut aux groupes d’utilisateurs Administrateur, Éditeur et
Super utilisateurs.

![Ensemble de données TinyMCE 0](../../../fr/images/editors/editors/05-set-0.png)

Cette option fournit tous les mêmes boutons que ceux documentés ci-dessus dans la barre d’outils de
l’ensemble 1. En outre, les options suivantes sont disponibles.

#### Avancé : première ligne

- Blocs : paragraphe, titres, préformaté.
- Polices : sélectionnez la police souhaitée.
- Taille de police : sélectionnez la taille de police souhaitée.
- Rechercher et remplacer.
- Insérer/modifier une image : pour insérer une image, placez le curseur à l’emplacement
  souhaité et appuyez sur ce bouton. Une boîte de dialogue contextuelle s’affiche et vous permet
  de saisir la source, la largeur ou la hauteur, ainsi que d’autres informations
  sur l’image.

#### Avancé : deuxième ligne

- Sélectionner la couleur du texte ou la couleur d’arrière-plan.
- Plein écran.
- Émoticônes.
- Insérer un média : pour insérer un média, placez le curseur à l’emplacement
  souhaité et appuyez sur ce bouton. Une boîte de dialogue contextuelle s’affiche et vous permet
  de saisir le type, le fichier ou l’URL, ainsi que d’autres informations
  sur le média.
- Orientation de gauche à droite ou orientation de droite à gauche : ces boutons
  vous permettent de saisir ou de modifier le sens du texte, par exemple pour les
  langues qui se lisent de droite à gauche.
- Couper, copier, coller.
- Afficher les caractères invisibles (comme les fins de paragraphe).
- Afficher les blocs.
- Espace insécable.
- Citation.
- Insérer un modèle.

#### Avancé : troisième ligne

- Imprimer le texte de l’article.
- Insérer/modifier un exemple de code.
- Insérer la date/l’heure.
- Effacer la mise en forme.

### Accessibilité

TinyMCE est compatible avec des lecteurs d’écran tels que
<a href="https://www.freedomscientific.com/products/software/jaws/"
rel="nofollow noreferrer noopener">JAWS</a> et
<a href="https://www.nvaccess.org/"
rel="nofollow noreferrer noopener">NVDA</a>. Vous pouvez l’utiliser
efficacement même si vous n’utilisez pas la souris.

#### Raccourcis clavier

| Tâche                                      | PC                     | macOS                  |
|--------------------------------------------|------------------------|------------------------|
| Activer/accéder à la barre de menus        | Alt+F9                 | ⌥+F9                 |
| Activer/accéder à la barre d’outils        | Alt+F10                | ⌥+F10                |
| Activer/accéder au chemin d’éléments       | Alt+F11                | ⌥+F11                |
| Fermer le menu/sous-menu/la boîte de dialogue | Échap                  | esc                    |
| Revenir à la zone de contenu de l’éditeur  | Échap                  | esc                    |
| Naviguer vers la gauche/droite dans le menu/la barre d’outils | Tabulation et touches fléchées | Tabulation et touches fléchées |

Pour plus d’informations, consultez :

- <a href="https://www.tiny.cloud/docs/advanced/accessibility/"
  rel="nofollow noreferrer noopener">TinyMCE - Accessibilité</a>
- Une liste des
  <a href="https://www.tiny.cloud/docs/advanced/keyboard-shortcuts/"
  rel="nofollow noreferrer noopener">raccourcis clavier</a> disponibles (PC, Mac)
  dans le corps de l’éditeur.

## CodeMirror

L’« éditeur - CodeMirror » est conçu pour faciliter la saisie de code HTML
dans un article ou une description. CodeMirror prend en charge la coloration syntaxique
et la complétion automatique, comme indiqué dans cette capture d’écran.

![formulaire de modification CodeMirror](../../../fr/images/editors/editors/06-codemirror.png)

- Les boutons affichés sous la fenêtre de modification permettent d’accéder à un lien vers n’importe quel
  élément du site.
- CodeMirror offre certains des mêmes avantages que l’utilisation de l’« éditeur -
  Aucun », mais facilite quelque peu l’utilisation du code HTML brut.
- La configuration est définie dans l’extension
  Éditeur -
  CodeMirror.

## Aucun

Si « Éditeur - Aucun » est sélectionné pour un utilisateur, un éditeur de texte simple
s’affiche. Cela vous permet de saisir du code HTML brut et non formaté. Vous pouvez utiliser
le bouton « Aperçu » de la barre d’outils pour prévisualiser l’affichage du code HTML.

Notez que l’option « Aucun » peut être utile si vous saisissez du code HTML
« passe-partout » ou personnalisé, par exemple pour créer un lien PayPal.
TinyMCE reformate et supprime automatiquement certains éléments HTML lors de l’enregistrement d’un fichier.
Cela peut empêcher du code HTML complexe de fonctionner correctement.

Si cela se produit, vous pouvez temporairement remplacer l’éditeur par « Aucun » et
créer le contenu souhaité. Notez que si vous souhaitez modifier ce contenu
ultérieurement, vous devez veiller à définir votre éditeur sur « Aucun ».
Sinon, si vous ouvrez et enregistrez le contenu avec TinyMCE, vous risquez de perdre
votre code HTML personnalisé.

Le plug-in « Éditeur - Aucun » ne possède aucune configuration.

*Traduit par openai.com*
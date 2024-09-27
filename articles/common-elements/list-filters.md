<!-- Filename: Help6.x:List_Filters  / Display title: Filtres de Liste -->

## Objectif

La plupart des composants ont des vues en liste qui affichent des éléments de la base de données. Il peut y avoir des centaines, des milliers, ou même des millions d'éléments. Ainsi, les filtres de liste sont utilisés pour réduire la liste affichée à ceux susceptibles de contenir celui sur lequel vous devez travailler.

Par exemple, les éléments mis à la corbeille ne sont généralement pas affichés par défaut. Si vous souhaitez voir vos éléments mis à la corbeille, vous devez configurer le filtre **- Sélectionner le statut -** sur **Mis à la corbeille**. La capture d'écran suivante montre les filtres pour la page des articles.

## Options de Filtrage de la Liste des Articles

![Liste des articles](../../../fr/images/common-elements/articles-list-filter-options.png)

Pour **afficher** ou **masquer** les options, sélectionnez le bouton **Options de Filtre**. Notez que les Options sont toujours affichées lorsque vous revenez sur une page dans laquelle une Option a été sélectionnée.

Le nombre d'options affichées varie en fonction du composant. Même le composant Contenu, qui affiche la liste des articles, peut avoir des filtres supplémentaires. Par exemple, un filtre **- Sélectionner un Étape -** est affiché si le composant Contenu a les **Flux de Travail** activés.

## La Barre de Recherche

### Rechercher par Texte

*Survolez* ou *sélectionnez* le champ de *recherche* pour voir une *infobulle* ou entendre un équivalent *audio* indiquant les champs qui seront recherchés. Le comportement par défaut est de rechercher le texte saisi dans le titre.

Le composant de contenu permet un préfixe pour rechercher dans l'ID, l'auteur ou le contenu. Chacun de ces termes nécessite un deux-points mais peut être en n'importe quelle *casse*. Par exemple *ID:19* ou *Author:John* ou *content:lorem ipsum*.

Pour effectuer une recherche, saisissez une partie du terme de recherche et sélectionnez l'icône **Recherche** (<span class="filter-search-bar__button-icon icon-search" aria-hidden="true"></span>).

### Options de Filtrage et Réinitialisation

Le bouton **Options de Filtrage** est utilisé pour basculer l'affichage des divers filtres. S'il n'y a pas de filtres pour un composant, ce bouton sera absent.

Le bouton **Réinitialiser** est utilisé pour supprimer tous les filtres et restaurer la liste à son état non filtré. S'il n'y a pas de filtres pour un composant, ce bouton sera absent.

### Ordre des Résultats

L'ordre dans lequel les résultats sont présentés est sélectionnable par l'utilisateur. Pour les articles, l'ordre par défaut est *ID Descendant*, ce qui place les articles les plus récents en haut de la liste. Mais vous pouvez souhaiter rechercher des articles par le nombre de hits, *Hits descendant*, ou les articles qui disparaîtront bientôt, *Fin de publication ascendant*.

L'ordre des résultats peut être modifié en sélectionnant une icône d'ordre dans les en-têtes de colonne de la liste. L'icône par défaut *ID Descendant* est représentée par un caret vers le bas (<span class="ms-1 icon-caret-down" aria-hidden="true"></span>). Il change en caret vers le haut si l'ordre de tri est inversé, *ID Ascendant*.

### Nombre de Résultats

Le nombre de résultats dans une liste est défini dans la page de Configuration Globale, onglet Site, champ Limite de Liste par Défaut. La valeur par défaut pour une nouvelle installation est de 20.

Il y a des occasions où cela n'est pas pratique. Vous pouvez souhaiter voir *50* ou *100*. Attention si vous choisissez *Tout*. Il peut falloir beaucoup de temps pour récupérer les résultats et rendre la page. Le serveur peut manquer de mémoire ou de temps et déclencher une erreur fatale. Et votre navigateur peut prendre beaucoup de temps pour afficher la page.

La valeur par défaut pour cet ensemble de documentation a été fixée à 5 car cela suffit pour les captures d'écran illustratives.


## Comment Utiliser les Filtres

L'objectif de chaque filtre devrait être évident à partir de son étiquette de sélection non filtrée. Par exemple, le filtre Articles **- Sélectionner le Statut -** propose cinq choix : *Supprimé*, *Non publié*, *Publié*, *Archivé* et *Tous*. Le dernier est fonctionnellement équivalent à non filtré (*- Sélectionner le Statut -*).

Lorsqu'une option de filtre est modifiée, la page se recharge automatiquement avec les nouveaux résultats filtrés par la nouvelle option de filtre.

## Masquer des colonnes

Certaines listes de composants comportent de nombreuses colonnes et peuvent être trop larges pour votre écran. Cela est particulièrement vrai pour certaines traductions du texte d'en-tête de colonne. Le résultat le plus agaçant est que les titres peuvent se chevaucher et être difficiles à lire.

Pour faire plus de place pour le titre, vous pouvez ouvrir la liste déroulante des colonnes et sélectionner les colonnes moins importantes à masquer. Ensuite, fermez à nouveau la liste des colonnes. L'effet est immédiat, car il utilise JavaScript pour masquer les colonnes sélectionnées dans la mise en page. Elles sont toujours présentes dans la page.

Vos paramètres sont sauvegardés par votre navigateur, ils seront donc utilisés jusqu'à ce que vous les modifiiez de nouveau, même si vous vous déconnectez puis reconnectez.

*Traduit par openai.com*


<!-- Filename: Help4.x:Smart_Search:_Indexed_Content  / Display title: Recherche intelligente : Contenu indexé -->

## Description

La page *Recherche intelligente : Contenu indexé* affiche une liste de tous les éléments de contenu qui ont été indexés dans la recherche intelligente.

### Éléments communs

Certains éléments de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonne de liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordre des éléments de liste](jdocmanual?article=help/common-elements/list-ordering).
* [Pagination de liste](jdocmanual?article=help/common-elements/list-pagination).

### Tutoriel

* Si vous êtes nouveau dans Recherche intelligente, vous devriez lire le 
  [guide de démarrage rapide de Recherche intelligente](https://docs.joomla.org/Smart_Search_quickstart_guide).

## Comment accéder

- Sélectionnez **Composants → Recherche intelligente → Index** dans le menu Administrateur.

## Capture d'écran

![recherche intelligente contenu indexé](../../../fr/images/smart-search/smart-search-indexed-content.png)

## Créer un Index

Sélectionnez le bouton **Index** dans la barre d'outils. Cela ouvrira une fenêtre pour afficher
l'avancement de l'opération d'indexation. L'opération d'indexation peut prendre un certain
temps en fonction du nombre d'éléments de contenu du site et du
nombre de mots et de phrases de recherche contenus dans chaque élément de contenu. Une
barre de progression indiquera combien du processus d'indexation a été
complété jusqu'à présent. Ne fermez pas cette fenêtre avant que l'indexation
soit terminée. Sur les sites avec une grande quantité de contenu, cela peut prendre beaucoup de
temps (quelques dizaines de minutes).

Vous devriez lancer l'indexeur après l'introduction de nouveaux contenus sur le site
que la fonction Recherche intelligente ne détecte pas automatiquement. Par exemple,
l'importation par lots de nouveaux contenus, où l'importateur ne déclenche pas automatiquement
la Recherche intelligente pour indexer chaque nouvel élément de contenu. REMARQUE : L'indexeur
Recherche intelligente peut également être exécuté depuis l'interface en ligne de commande (CLI)
si nécessaire. Voir Configuration de l'indexation Recherche intelligente automatique.

## Barre d'outils

- **Index** Lance l'indexeur de recherche intelligente. Une petite fenêtre contextuelle apparaîtra avec une barre de progression qui avance à mesure que le processus d'indexation travaille sur le contenu du site.
- **Actions** Sélectionnez une case à cocher pour activer la liste déroulante.
  - **Publier** Rend les éléments sélectionnés accessibles aux visiteurs du site web.
  - **Dépublier** Rend les éléments sélectionnés indisponibles pour les visiteurs du site web.
- **Supprimer** Supprime les éléments de contenu sélectionnés. Fonctionne avec un ou plusieurs éléments de contenu sélectionnés. La suppression d'un élément de contenu de la Recherche intelligente ne le supprime que de l'index et n'affecte pas l'élément de contenu lui-même.
- **Maintenance**
  - **Optimiser**
  - **Effacer l'index** Purge l'index de la Recherche intelligente en vidant toutes les tables d'index. Pour continuer à utiliser la Recherche intelligente, sélectionnez le bouton Index dans la barre d'outils après la purge. ATTENTION : La purge de l'index vide également les filtres de contenu. Ils doivent être réintroduits manuellement après un cycle de Purge-Index.
- **Statistiques** Affiche quelques statistiques de base sur la Recherche intelligente.

## Conseils

- Si vous exécutez l'indexeur et obtenez une erreur *undefined null*, vérifiez alors
  les permissions sur le répertoire `/logs` de Joomla. Le serveur web doit
  avoir la permission d'écriture sur ce répertoire pour que l'indexeur fonctionne.
- Si la liste est vide, assurez-vous que le plug-in Smart Search a
  été activé.

*Traduit par openai.com*


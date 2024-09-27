<!-- Filename: Help4.x:Component:_Fields  / Display title: Composant : Champs  -->

## Description

Les champs sont utilisés pour afficher des attributs supplémentaires d'Articles, de Contacts ou d'Utilisateurs. 
Les données sont saisies dans un formulaire de modification de l'administrateur et affichées sur le site.
Un exemple :

Supposons que vous écriviez des articles sur différents aspects de la nature, parfois des Fleurs, parfois des Animaux. Un champ que vous pourriez souhaiter enregistrer et afficher pour les deux est le Nom Latin, nécessitant un champ de texte. Un autre pourrait être Habitat : Forêt, Étang, Prairie, etc., nécessitant une liste déroulante. Pour les fleurs, vous voudrez peut-être enregistrer la Saison de Floraison en utilisant 4 cases à cocher, une pour chaque saison, ou 12 cases à cocher, une pour chaque mois.

Les champs vides dans le formulaire de saisie ne sont pas affichés dans la sortie du site, vous pourriez donc conserver tous les champs dans une longue liste. Cependant, il est généralement préférable d'utiliser des catégories pour vos Articles, disons Fleurs et Animaux. Les champs peuvent être assignés à plus d'une Catégorie. Ainsi, les champs Nom Latin et Habitat seraient assignés aux deux mais la Saison de Floraison serait uniquement assignée à la catégorie Fleurs.

Si un champ n'est pas assigné à un groupe, il apparaîtra dans le formulaire de modification dans un onglet Champs. Si un champ est assigné à un groupe, il apparaîtra dans un onglet portant ce nom. Ainsi, pour le groupe Fleurs, il semble approprié de créer un groupe nommé Données sur les Fleurs (ou simplement Fleurs, bien que l'utilisation du même nom pour différentes choses puisse prêter à confusion). Et pour les autres champs communs, vous pourriez utiliser un groupe Nature.

### Éléments Communs

Certains éléments de cette page sont abordés dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [Filtres de liste](jdocmanual?article=help/common-elements/list-filters).
* [En-têtes de colonnes de liste](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordre des éléments de la liste](jdocmanual?article=help/common-elements/list-ordering).
* [Pagination de liste](jdocmanual?article=help/common-elements/list-pagination).
* [Traitement en lot de la liste](jdocmanual?article=help/common-elements/list-batch-process).

### Article Connexe

* Il existe un exemple plus long de l'utilisation des [Champs et Groupes de Champs](jdocmanual?article=user/fields/fields-and-field-groups).
* Il y a un article dans le magazine communautaire qui inclut l'utilisation de champs personnalisés dans une catégorie pour [Créer une bannière à partir de la description de la catégorie de Joomla](https://magazine.joomla.org/all-issues/july-2024/create-a-banner-from-joomla-s-category-description).

## Comment accéder

* Sélectionnez **Contenu → Champs** dans le menu Administrateur.
* Sélectionnez **Articles** dans la liste déroulante *Articles/Catégorie*.
  * Sélectionnez le bouton **Nouveau** dans la *Barre d’outils* pour ajouter un nouveau champ.
  * Sélectionnez un **Titre** dans la liste pour modifier un champ existant.

**Remarque :** Il existe une liste déroulante qui permet de créer des champs pour une
Catégorie, et Mail dans le composant Contact. Ils nécessitent quelques connaissances en codage 
pour préparer les substitutions de modèles appropriées.

## Capture d'écran

![Liste des champs des articles](../../../fr/images/fields/articles-fields-list.png)

Il y a 16 types de champs disponibles, chacun implémenté sous forme de plugin. D'autres sont 
susceptibles de devenir disponibles à l'avenir.


*Traduit par openai.com*


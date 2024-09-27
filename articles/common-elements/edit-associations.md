<!-- Filename: Help4.x:Edit_Associations  / Display title: Modifier les associations  -->

## Objectif

Dans les sites multilingues, il est possible de créer un élément dans une langue et de le lier à un élément équivalent dans une ou plusieurs autres langues. Ce lien est connu sous le nom d'**Association**. Il doit être effectué manuellement.

L'onglet Associations permet de faire cela dans le formulaire de modification de divers composants : article, catégorie, contact, élément de menu et flux d'actualités.

## Exemple : Articles : Onglet Modifier les Associations

![Onglet modifier les associations de l'article](../../../fr/images/common-elements/articles-edit-association-tab.png)

Dans cette illustration, un article a été créé en allemand. C'est celui qui est en cours de modification. La liste des associations montre les langues disponibles autres que l'allemand. Une association avec le même article en anglais a été faite. Elle peut être éditée ou effacée. Des associations avec le même article dans d'autres langues peuvent être faites en choisissant un article parmi ceux déjà disponibles ou en créant un nouvel article.

Le bouton **Sélectionner** ouvre une boîte de dialogue modale contenant une liste d'articles dans la langue sélectionnée à choisir.

Le bouton **Créer** ouvre une boîte de dialogue modale contenant un formulaire **Nouvel Article** avec la langue déjà définie.

Le bouton **Modifier** ouvre une boîte de dialogue modale contenant un formulaire **Modifier l'Article**.

Le bouton **Propager** est un peu difficile à comprendre. Supposons que vous ayez deux articles nommés *Lorem Ipsum (fr-FR)* et *Lorem Ipsum (en-GB)* qui sont déjà associés. Vous décidez d'ajouter un troisième article et de l'associer aux deux déjà associés.

* Sélectionnez le bouton **Nouveau** dans la barre d'outils de la liste des articles.
* Entrez un titre et sélectionnez une **Langue**. Le paramètre par défaut *Tous* ne fonctionne pas pour les associations multilingues.
* Sélectionnez l'onglet **Associations**.
* Pour une **langue** dont vous savez qu'elle a une association existante que vous souhaitez associer à votre nouvel article :
    * Utilisez le bouton **Sélectionner** pour la trouver et la sélectionner. Par exemple, *Lorem Ipsum (fr-FR)*. L'association nouvellement sélectionnée aura un bouton *Propager*.
* Sélectionnez le bouton **Propager**.
* Tous les autres éléments associés à *Lorem Ipsum (fr-FR)* seront associés à votre nouvel élément, dans cet exemple *Lorem Ipsum (de-DE)* sera également sélectionné et aura un bouton *Propager*.
* Sélectionnez le bouton **Enregistrer & Fermer**.


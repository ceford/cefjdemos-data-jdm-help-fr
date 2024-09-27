<!-- Filename: Help6.x:List_Ordering  / Display title: Ordre des listes  -->

## Où l'Ordre a de l'Importance

L'ordre des éléments dans une liste commence à avoir de l'importance lorsqu'on les visualise depuis le frontend du site. Par exemple, supposons que vous avez un certain nombre d'articles en vedette que vous présentez dans une disposition *Article en Vedette*. Le formulaire de saisie de données de menu pour cette disposition offre plusieurs alternatives d'*Ordre des Articles*, dont l'une est **Ordre des Articles en Vedette**. L'ordre par défaut est celui dans lequel les articles sont ajoutés. Mais que faire si vous voulez qu'un article particulier soit en tête de liste ? Si vous avez une commission avec des articles sur chaque membre, vous pourriez vouloir que le président soit en première position dans la disposition de la page d'accueil.

Le même principe s'applique aux dispositions de Blog de Catégorie. Vous pouvez avoir plusieurs commissions, chacune dans une catégorie différente. Dans ce cas, vous filtrez la liste des articles par catégorie et vous placez l'article sur le président en premier dans la liste.

## La Colonne de Classement

Dans une vue de liste de composants, la colonne de classement est généralement la deuxième en partant de la gauche (dans les langues s’écrivant de gauche à droite) juste à côté de la colonne de case à cocher. Si la liste n’est pas triée par la colonne de classement, celle-ci sera vide. Dans ce cas, vous devez sélectionner l’icône de la colonne de classement, un double chevron (<span class="ms-1 icon-sort"></span>). À chaque sélection de l'icône, l'ordre bascule entre ordre croissant et décroissant. Vous avez besoin de l'ordre croissant (<span class="ms-1 icon-caret-up"></span>) pour faire glisser un élément vers le haut de la liste. Cela est indiqué dans le champ de l'ordre de tri de la barre de recherche.

## Glisser-Déposer

Avec la colonne de tri configurée pour l'utilisation, chaque élément contiendra une icône d'ellipsis verticale (<span class="icon-ellipsis-v"></span>). Cette icône peut être glissée vers le haut ou vers le bas pour changer l'ordre de la liste. Le nouvel ordre de la liste est défini dans la base de données par un appel JavaScript. Il n'y a pas de rechargement de la page.

C'est délicat ! Vous devez vous entraîner. Et c'est l'une des occasions où vous pourriez souhaiter définir la limite de la liste à *Tout*.

*Traduit par openai.com*


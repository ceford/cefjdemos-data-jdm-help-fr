<!-- Filename: Help4.x:Glossary / Display title: Glossaire -->

Le glossaire Joomla! est utile pour expliquer les termes courants utilisés dans les tutoriels Joomla!, les écrans d'aide et la documentation avancée.

## Liste de contrôle d'accès (ACL)

## Alias

## Ancre

Une ancre est créée en utilisant la balise `<a>` en HTML. Une ancre vous permet de placer un marqueur à l'intérieur d'une page HTML. Dans Joomla!, vous pouvez insérer une ancre dans un article (par exemple, en utilisant l'éditeur TinyMCE). Cela vous permet de créer un lien qui vous conduira directement à cet endroit dans l'article.

Le code source HTML pour une ancre ressemble à ceci :

```html
<a name="mon_ancre" title="Mon Ancre"></a>
```

Vous pouvez créer un lien vers une ancre dans la même page en utilisant ce code HTML :

```html
<a href="#mon_ancre"></a>
```

Cliquer sur ce lien vous amènera directement à l'endroit où se trouve l'ancre.

Vous pouvez également lier une ancre sur une page différente en ajoutant "#" suivi du nom de l'ancre à la fin de l'URL. Dans l'exemple ci-dessus, si l'URL de l'article était `http://www.monsite.com/mon_article.html`, vous pourriez lier directement à l'ancre sur cette page avec l'URL `http://www.monsite.com/mon_article.html#mon_ancre`.

## Article

## Feuille de style en cascade (CSS)

Une feuille de style en cascade, ou CSS, est utilisée pour contrôler la présentation d'une page XHTML. Par exemple, un fichier CSS contrôle souvent la police, les marges, la couleur, les images de fond, et d'autres aspects de l'apparence d'une page web. Le CSS permet de séparer le contenu d'une page XHTML de son apparence. Dans Joomla!, les fichiers CSS (par exemple, template.css) font normalement partie du template.

**Voir aussi :** Template, Suffixe de classe de page, Suffixe de classe de module

## Catégorie

Chaque partie d'un site web alimenté par Joomla! ou tout autre CMS nécessite une méthode pour afficher et stocker son contenu de manière logique. La méthode habituelle consiste à utiliser des catégories et sous-catégories. Joomla! permet plusieurs façons d'afficher et d'utiliser le contenu, contrôlées par la catégorisation. Certains types de contenu ayant une catégorisation incluent les articles (le contenu principal des pages web), les bannières et les contacts.

Une catégorie nommée *Non classé* est la catégorie par défaut assignée à la plupart des types de contenu. La catégorie *Non classé* n'est pas descriptive et devrait être utilisée avec parcimonie pour les types de contenu qui ne relèvent d'aucune catégorie spécifique.

Lorsque vous créez et assignez des catégories, vous devriez avoir une structure planifiée. Par exemple, voici une façon de catégoriser plusieurs articles sur les oiseaux :

- Créez deux catégories d'articles principales appelées *Animaux* et *Plantes*.
- Sous la catégorie *Animaux*, créez des sous-catégories appelées *Oiseaux* et *Mammifères*.
- Sous la sous-catégorie *Oiseaux*, créez des catégories intitulées *Rapaces*, *Perroquets* et *Moineaux*. Voici la structure résultante des catégories :

```
- Animaux
  - Oiseaux
    - Rapaces
    - Perroquets
    - Moineaux
  - Mammifères
```

Vous pouvez ensuite créer plusieurs articles dans les sous-catégories *Rapaces*, *Perroquets* et *Moineaux* en utilisant les noms de genre ou les noms communs spécifiques à ces types d'oiseaux.

## Chrome

Les éléments d'interface graphique visibles d'une application sont parfois appelés *chrome*.

## Composant

## Noyau

Le terme *noyau* dans Joomla! fait référence aux fichiers distribués qui sont nécessaires pour créer et administrer un site web alimenté par Joomla! Le noyau Joomla contient toutes les fonctionnalités essentielles pour créer et gérer rapidement et facilement un nouveau site web.

## Préfixe des tables de base de données

Le préfixe des tables de la base de données est une chaîne de caractères (quelques lettres) placée au début du nom des tables Joomla! Utiliser un préfixe permet d'exécuter plusieurs installations de Joomla! en utilisant une seule base de données.

Le préfixe des tables peut être défini lors de l'installation. Il est possible de le modifier plus tard, mais cela nécessite un accès à la base de données via un moyen externe à Joomla! ou une extension Joomla! comme Akeeba Admin Tools, et entraînera une interruption temporaire du site.

Les développeurs d'extensions doivent utiliser la chaîne `#__` pour représenter le préfixe. Celle-ci sera remplacée par le véritable préfixe à l'exécution.

## Extension

## LDAP

## Langue

Les langues sont peut-être le type d'extension le plus basique et le plus critique. Les langues sont regroupées sous forme de packs linguistiques de base ou de packs linguistiques d'extension. Ces packs contiennent des fichiers INI qui comportent des paires clé/valeur fournissant la traduction des chaînes de texte statiques dans le code source Joomla!. Cela permet d'internationaliser à la fois le noyau de Joomla! et les composants et modules tiers. Les packs de langues de base incluent également un fichier méta XML décrivant la langue et fournissant des informations sur les polices à utiliser pour la génération de contenu en PDF.

## Menu

Dans Joomla!, un **menu** est un module contenant un ensemble d'**éléments de menu** utilisés pour la navigation. Chaque élément de menu définit une URL vers une page du site et contient des paramètres qui contrôlent l'affichage du contenu de la page et son style.

## Modèle-Vue-Contrôleur (MVC)

Joomla fait un usage intensif du
<a href="http://fr.wikipedia.org/wiki/Modèle-vue-contrôleur"
class="external text" target="_blank"
rel="nofollow noreferrer noopener">Modèle-Vue-Contrôleur</a> comme modèle de conception.

Lorsque Joomla est lancé pour traiter une requête d'un utilisateur, comme une requête GET pour une page particulière ou un POST contenant des données de formulaire, l'une des premières choses que fait Joomla est d'analyser l'URL pour déterminer quel composant sera responsable du traitement de la demande, puis de transférer le contrôle à ce composant.

Si le composant est conçu selon le modèle MVC, il transmettra le contrôle au contrôleur. Le contrôleur est responsable de l'analyse de la demande et de la détermination des modèles nécessaires pour satisfaire la requête, ainsi que de la vue qui sera utilisée pour renvoyer les résultats à l'utilisateur.

Le modèle encapsule les données utilisées par le composant. Dans la plupart des cas, ces données proviennent d'une base de données, soit la base de données Joomla, soit une base de données externe. Le modèle est aussi responsable de la mise à jour de la base de données lorsque cela est nécessaire. Le but du modèle est d'isoler le contrôleur et la vue des détails relatifs à la manière dont les données sont obtenues ou modifiées.

La vue est responsable de la génération de la sortie envoyée au navigateur par le composant. Elle fait appel au modèle pour toute information nécessaire et la formate correctement. Par exemple, une liste d'éléments de données extraites du modèle peut être enveloppée dans une table HTML par la vue.

Puisque Joomla est conçu pour être hautement modulaire, la sortie d'un composant constitue généralement une partie seulement de la page web complète que l'utilisateur verra finalement. Une fois que la vue a généré la sortie, le composant rend le contrôle au framework Joomla qui charge ensuite le template et l'exécute. Le template combine la sortie du composant et tous les modules actifs sur la page en cours, de sorte qu'elle puisse être livrée au navigateur sous forme de page unique.

Pour offrir plus de puissance et de flexibilité aux web designers, qui pourraient ne s'intéresser qu'à la création de nouveaux designs plutôt qu'à la manipulation du code sous-jacent, Joomla sépare la vue traditionnelle en une vue distincte et une mise en page. La vue extrait les données du modèle, comme dans un modèle MVC traditionnel, puis rend simplement ces données disponibles à la mise en page, qui est responsable de formater les données pour leur présentation à l'utilisateur. L'avantage de cette séparation est que le système de templates de Joomla fournit un mécanisme simple pour que les mises en page soient remplacées dans le template. Ces remplacements de mise en page (souvent appelés "surcharges de template" car ils font partie du template, bien que ce soit en réalité la mise en page qui est remplacée) sont intégrés au template et offrent au designer un contrôle complet sur toute la sortie du noyau Joomla et de toute extension tierce conforme au modèle de conception MVC.

## Module

## Suffixe de classe de module

Un suffixe de classe de module est un paramètre utilisé dans les modules pour ajouter une nouvelle classe CSS à un module. Il est utilisé conjointement avec des styles définis dans un fichier user.css pour modifier l'apparence standard d'un module.

Le nouveau nom de classe peut être utilisé pour ajouter toute mise en forme souhaitée au module sans avoir besoin de recréer tout le code CSS existant. Notez que si vous créez un nouveau nom de classe, assurez-vous qu

'il est unique et qu'il ne rentre pas en conflit avec des noms de classes existants.

## Position de module

## Chrome de module

## PHP

PHP est un langage de script informatique conçu pour créer des pages web dynamiques. PHP est largement utilisé pour le développement web et peut être intégré dans le HTML. Il s'exécute généralement sur un serveur web, prenant le code PHP en entrée et générant des pages web en sortie. Joomla! est principalement écrit en PHP.

## Suffixe de classe de page

Un suffixe de classe de page est un paramètre utilisé dans les éléments de menu de contenu pour ajouter une nouvelle classe CSS à la mise en page de la page. Il est utilisé avec des styles définis dans un fichier user.css pour modifier l'apparence standard d'un module.

Le nouveau nom de classe peut être utilisé pour ajouter tout style souhaité à la page sans avoir besoin de recréer tout le code CSS existant. Assurez-vous que le nouveau nom de classe est unique et ne rentre pas en conflit avec des noms de classes existants.

## Correctif

## Plugin

## URL conviviales pour les moteurs de recherche (SEF)

Les URL conviviales pour les moteurs de recherche, souvent abrégées en SEF URLs ou SEF, sont des URL formatées de manière à être plus faciles à lire et mieux indexées par les moteurs de recherche. Une URL Joomla! normale peut ressembler à ceci :

```html
http://www.votresite.org/index.php?option=com_content&view=section&id=3&Itemid=41
```

Vous pouvez optionnellement avoir des URLs qui ressemblent à des pages HTML statiques comme ceci :

```html
http://www.votresite.org/faq.html
```

Des options intégrées permettent de générer des URL SEF. Celles-ci peuvent être activées dans les *Paramètres SEO* (Optimisation pour les moteurs de recherche) dans l'onglet Site de la page de Configuration Globale. Il existe également des extensions tierces qui créent des URL SEF pour Joomla!.

## Menus fractionnés

Un menu fractionné est un menu où différents niveaux d'un même menu sont affichés à deux ou plusieurs emplacements sur une même page web.

Par exemple, un besoin fréquent est d'avoir un menu d'éléments de premier niveau en haut de la page. Lorsqu'un de ces éléments est cliqué, l'utilisateur est dirigé vers une page où un menu secondaire, par exemple sur la gauche, montre les éléments de deuxième niveau associés à l'élément de premier niveau sélectionné.

Les menus apparaissent à des emplacements séparés sur la page, mais sont liés car l'un montre uniquement les éléments de premier niveau, tandis que l'autre montre les éléments de deuxième niveau. Cette idée peut être étendue pour inclure des menus pour les éléments de troisième niveau et au-delà.

Cela peut être implémenté dans Joomla en utilisant un seul menu multi-niveaux, puis en créant plusieurs modules de menu, chacun faisant référence à un niveau différent.

## Template

Un template est un type d'extension Joomla! qui contrôle l'apparence de la page.
- Un template de Site contrôle l'apparence publique du contenu du site.
- Un template Administrateur contrôle l'apparence du site pour les tâches administratives telles que : gestion des utilisateurs, menus, articles, catégories, modules, composants, plugins et templates.

## Style de template

## Package de mise à jour

Un package de mise à jour dans Joomla! est un ensemble de fichiers contenant les fichiers modifiés entre les versions de Joomla!. Lorsqu'il est décompressé, il remplace l'ancienne version des fichiers modifiés par la nouvelle version. Par exemple, si cinquante fichiers ont été modifiés entre la version 5.1 et 5.2, le package de mise à jour contiendra ces cinquante fichiers et les instructions nécessaires pour exécuter la mise à jour. Parfois, cela inclut des mises à jour de la base de données et la suppression de fichiers qui ne sont plus utilisés.

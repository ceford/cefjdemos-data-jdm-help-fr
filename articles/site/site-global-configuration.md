<!-- Filename: Help4.x:Site_Global_Configuration / Display title: Configuration globale -->

## Description

L'écran de configuration globale permet de configurer le site Joomla avec vos paramètres personnels. Les paramètres définis dans cet écran s'appliquent à l'ensemble du site.

### Éléments communs

Certains aspects de cette page sont couverts dans des articles d'aide séparés :

* [Barres d'outils](jdocmanual?article=help/common-elements/toolbars).
* [L'onglet des permissions](jdocmanual?article=help/common-elements/edit-permissions).

## Comment y accéder

- Sélectionnez **Panneau Système → Configuration Globale** depuis le tableau de bord. Ou...
- Sélectionnez **Système → Panneau de Configuration → Configuration Globale** dans le menu Administrateur.

## Capture d'écran

![onglet site de la configuration globale](../../../fr/images/site/global-configuration-site-tab.png)

## Champs du formulaire

### Onglet Site

#### Panneau Site

- **Nom du site** Entrez le nom du site Web. Celui-ci sera utilisé à divers endroits (par exemple dans la barre de titre du navigateur Backend et sur les pages Hors ligne du site).
- **Site hors ligne** Sélectionnez si l'accès au Frontend est disponible.
- **Message hors ligne**
    - *Masquer*
    - *Utiliser un message personnalisé* Le message utilise la valeur définie dans le champ *Message personnalisé*.
    - *Utiliser le message par défaut de la langue du site* Le message utilise la valeur définie dans le fichier ini de la langue du site.
- **Image hors ligne** Sélectionnez une image à afficher sur la page hors ligne. Assurez-vous que l'image fait moins de 400px de large.
- **Édition du Frontend** Sélectionnez l'édition pour les modules et les éléments de menu.
- **Éditeur par défaut** Sélectionnez l'éditeur de texte par défaut. Les utilisateurs enregistrés pourront modifier leur préférence dans leurs détails personnels.
- **Captcha par défaut** Sélectionnez le captcha par défaut pour votre site. Vous devrez peut-être entrer des informations dans le plugin captcha.
- **Niveau d'accès par défaut** Sélectionnez le niveau d'accès par défaut pour les nouveaux éléments.
- **Limite de liste par défaut** Définit la longueur par défaut des listes dans le Backend pour tous les utilisateurs.
- **Limite de flux par défaut** Sélectionnez le nombre d'articles à afficher dans les flux.
- **Adresse email du flux** Les flux RSS et Atom incluent l'adresse email de l'auteur.
  - *Email de l'auteur* Inclure l'email de l'auteur de l'article provenant du profil utilisateur dans le flux.
  - *Email du site* Inclure l'adresse *Email de l'expéditeur* du site pour chaque article.

#### Panneau Métadonnées

- **Description méta du site** Entrez une description globale du site Web qui sera utilisée par les moteurs de recherche.
- **Robots** Instructions pour les robots.
  - *index, follow* Indexer cette page et suivre les liens sur cette page.
  - *noindex, follow* Ne pas indexer cette page, mais suivre les liens de la page.
  - *index, nofollow* Indexer cette page, mais ne pas suivre les liens de la page.
  - *noindex, nofollow* Ne pas indexer cette page ni suivre les liens de la page.
- **Droits sur le contenu** Décrivez les droits d'utilisation du contenu par d'autres. Cela est transmis aux moteurs de recherche via la balise méta `rights` dans l'en-tête HTML.
- **Balise méta de l'auteur** Affichez la balise méta de l'auteur lors de la consultation des articles.
- **Version de Joomla** Contrôle si la balise méta `generator` dans l'en-tête HTML inclut la version exacte du site Joomla. Il est recommandé de la masquer pour des raisons de sécurité.

#### Panneau SEO

- **URLs optimisées pour les moteurs de recherche (SEF)** Sélectionnez si les URLs sont optimisées pour les moteurs de recherche.
- **Utiliser la réécriture d'URL**
  - *Apache et Litespeed* Renommez `htaccess.txt` en `.htaccess`.
  - *IIS* Renommez `web.config.txt` en `web.config`.
  - *NginX* Vous devez configurer votre serveur.
  - *Autre* Si vous n'êtes pas sûr, consultez votre hébergeur.
- **Ajouter un suffixe à l'URL** Si oui, le système ajoutera un suffixe à l'URL basé sur le type de document.
- **Alias Unicode** Choisissez entre la translittération et les alias Unicode. La translittération est la valeur par défaut.
- **Nom du site dans les titres de page** Débuter ou terminer tous les titres de page par le nom du site (par exemple, *Nom de mon site - Nom de mon article*).

#### Panneau Cookies

- **Domaine des cookies** Domaine à utiliser lors de la définition des cookies de session. Précédez le domaine d'un '.' si le cookie doit être valide pour tous les sous-domaines.
- **Chemin des cookies** Chemin où le cookie doit être valide.

### Onglet Système

![onglet système de la configuration globale](../../../fr/images/site/global-configuration-system-tab.png)

#### Panneau Débogage

- **Débogage du système** Si activé, des informations de diagnostic, de traduction de langue et des erreurs SQL (le cas échéant) seront affichées. Ces informations apparaîtront en bas de chaque page que vous visualisez dans le Backend et le Frontend. Il est déconseillé de laisser le mode débogage activé sur un site en production.
- **Débogage de la langue** Activez pour voir les indicateurs de débogage `**...**` ou `??...??` dans la sortie de la page où les fichiers de langue de Joomla sont utilisés pour traduire les clés de chaîne. Le premier format indique que la chaîne a été traduite avec succès. Le second indique que le texte a été saisi en langage clair et ne peut pas être traduit.
  - **Affichage de la langue** Sélectionnez si vous devez afficher la constante de langue ou la valeur de langue lors du débogage des chaînes de langue.

#### Panneau Cache

- **Cache du système** Activez le cache et définissez le niveau de cache.
  - *Niveau conservateur* Cache système plus petit.
  - *Niveau progressif* Cache système plus rapide et plus grand, inclut le cache des modules. Inapproprié pour les très grands sites.
  - **Gestionnaire de cache**
    - *Fichier* Le mécanisme de cache natif est basé sur des fichiers. Assurez-vous que les dossiers de cache sont accessibles en écriture.
  - **Cache spécifique à la plateforme** Activez lorsque la sortie HTML sur mobile diffère des autres appareils.
  - **Durée du cache (en minutes)** La durée maximale en minutes pendant laquelle un fichier de cache est stocké avant d'être actualisé.
  - **Chemin vers le dossier de cache** Spécifiez un dossier accessible en écriture pour stocker les fichiers de cache si vous ne souhaitez pas utiliser le dossier par défaut.

#### Panneau Session

- **Gestionnaire de session** Le mécanisme par lequel Joomla identifie un utilisateur une fois qu'il est connecté au site à l'aide de cookies non persistants.
  - *Base de données* Le gestionnaire de session par défaut car Joomla peut le configurer et le contrôler entièrement.
  - *Système de fichiers* Le gestionnaire de système de fichiers sera légèrement plus performant que le gestionnaire de base de données, mais il nécessite une bonne configuration de PHP, sinon il entraînera des plantages et Joomla sera inutilisable.
    - *Chemin d'enregistrement de session* Entrez un chemin complet du système de fichiers. Assurez-vous que le chemin dispose des autorisations appropriées pour que PHP puisse lire et écrire des fichiers, et si la `session garbage collection` est activée, supprimer des fichiers. Si ce chemin n'est pas défini, Joomla utilisera la configuration `session.save_path INI` de PHP ou se basera sur le répertoire temporaire du système (défini par la fonction PHP sys_get_temp_dir()). Si aucun de ces chemins n'est configuré ou si les autorisations sont incorrectes, le site sera inutilisable. Pour récupérer la situation, modifiez le fichier configuration.php et définissez `$session_handler = 'database'`.
  - *Autres gestionnaires* APCu, Memcached, Redis, et WinCache dépendent tous d'extensions PHP facultatives et peuvent être disponibles si votre système les prend en charge. APCu ou WinCache ne sont pas nécessairement meilleurs que l'option *fichier*. Les gestionnaires Memcached et Redis sont excessifs pour Joomla dans un environnement d'hébergement mutualisé typique, mais sont utiles dans un environnement équilibré où plusieurs serveurs sont impliqués et où les données de session doivent être disponibles sur tous les serveurs.
- **Durée de session (en minutes)** Déconnecte automatiquement un utilisateur après une période d'inactivité définie. Ne pas définir une valeur trop élevée.
- **Sessions partagées** Lorsque cette option est activée, la session de l'utilisateur est partagée entre les sections Frontend et Backend du site. Notez que changer cette valeur invalidera toutes les sessions existantes sur le site. Cette option n'est pas disponible lorsque l'option *Forcer HTTPS* est réglée sur *Administrateur uniquement*.
- **Suivi des métadonnées de session**
  - *Oui* Des métadonnées supplémentaires concernant la session d'un utilisateur (y compris son nom d'utilisateur, son identifiant et l'application à laquelle il est connecté) seront enregistrées dans la table des sessions de la base de données.
  - *Non* Les fonctionnalités dépendantes de ces données ne seront pas disponibles.

### Onglet Serveur

![onglet serveur de la configuration globale](../../../fr/images/site/global-configuration-server-tab.png)

#### Panneau Serveur

- **Chemin vers le dossier temporaire** Veuillez spécifier un dossier accessible en écriture pour stocker les fichiers temporaires.
- **Compression des pages Gzip**
  - *Oui* Comprime automatiquement les pages HTML générées avec Gzip, ce qui les rend plus petites et améliore la vitesse du site.
  - *Non* Si votre serveur le fait déjà ou si cela entre en conflit avec des extensions tierces.
- **Rapport d'erreurs** Ce paramètre définit le niveau de rapport d'erreurs utilisé par PHP sur le site Joomla.
  - *Défaut du système* Laisse le niveau de rapport d'erreurs tel que défini sur le serveur.
  - *Aucun* Désactive le rapport d'erreurs.
  - *Simple* Remplace le paramètre du serveur pour donner un niveau de rapport d'erreurs basique.
  - *Maximum* Remplace le paramètre du serveur pour permettre le rapport de toutes les erreurs. Si votre site Joomla échoue à un tel point qu'il n'est plus possible d'utiliser la page administrateur pour activer le rapport d'erreurs, vous pouvez activer le rapport d'erreurs complet en modifiant le fichier `configuration.php`. Régler `$error_reporting = 'maximum'` équivaut à régler *Rapport d'erreurs* sur *Maximum*.
- **Forcer HTTPS** Force l'accès au site dans les zones sélectionnées à se faire uniquement via HTTPS (connexions HTTP cryptées avec le préfixe du protocole https://) et force également l'utilisation de cookies sécurisés. Notez que vous devez avoir activé HTTPS sur votre serveur pour utiliser cette option.

#### Panneau Localisation

- **Fuseau horaire du site Web** Choisissez une ville dans la liste pour configurer la date et l'heure à afficher.

#### Panneau Services Web

- **Activer CORS** Le partage de ressources entre origines ou [CORS](https://developer.mozilla.org/fr/docs/Web/HTTP/CORS) permet aux scripts exécutés dans un navigateur d'interagir avec des ressources provenant d'une autre origine.
  - **Access-Control-Allow-Origin** Spécifie l'origine autorisée à accéder aux services Web sur ce site, renvoyée en réponse à une requête préliminaire. Par défaut : `*` (=toutes).
  - **Access-Control-Allow-Headers** Spécifie les en-têtes renvoyés en réponse à une requête préliminaire. Par défaut : `Content-Type,X-Joomla-Token`.
  - **Access-Control-Allow-Methods** Spécifie les méthodes de services Web autorisées pour l'accès sur ce site, renvoyées en réponse à une requête préliminaire. Par défaut : toutes les méthodes disponibles pour la route demandée.

#### Panneau Proxy

- **Derrière un équilibrage de charge** Si votre site est derrière un équilibrage de charge ou un proxy inverse, activez ce paramètre pour que les adresses IP et autres configurations dans Joomla en tiennent compte automatiquement.
- **Activer le proxy sortant** Certains hébergeurs n'autorisent pas par défaut l'accès réseau de votre site vers l'extérieur et nécessitent une configuration manuelle d'un proxy sortant.
  - **Hôte du proxy sortant** Nom de domaine ou adresse IP de l'hôte.
  - **Port du proxy sortant**
  - **Nom d'utilisateur du proxy sortant** Laissez vide si votre proxy sortant ne nécessite pas d'authentification.
  - **Mot de passe du proxy sortant**

#### Panneau Base de données

- **Type de base de données** Le type de base de données utilisé, sélectionné lors du processus d'installation. Ne modifiez pas ce champ, sauf si nécessaire (par exemple lors du transfert de la base de données vers un nouvel hébergeur).
- **Hôte** Le nom de l'hôte de votre base de données, saisi lors de l'installation. Ne modifiez pas ce champ, sauf si nécessaire (par exemple lors du transfert de la base de données vers un nouvel hébergeur).
- **Nom d'utilisateur de la base de données** Le nom d'utilisateur pour accéder à votre base de données, saisi lors de l'installation. Ne modifiez pas ce champ, sauf si nécessaire (par exemple lors du transfert de la base de données vers un nouvel hébergeur).
- **Mot de passe de la base de données** Le mot de passe à utiliser pour accéder à la base de données. Ne modifiez pas ce champ, sauf si nécessaire (par exemple lors du transfert de la base de données vers un nouvel hébergeur).
- **Nom de la base de données** Le nom de votre base de données, saisi lors de l'installation. Ne modifiez pas ce champ, sauf si nécessaire (par exemple lors du transfert de la base de données vers un nouvel hébergeur).
- **Préfixe des tables de la base de données** Le préfixe utilisé pour vos tables de base de données, créé lors de l'installation. Ne modifiez pas ce champ, sauf si nécessaire (par exemple lors du transfert de la base de données vers un nouvel hébergeur).
- **Cryptage de connexion**
  - Par défaut (contrôlé par le serveur)
  - Authentification à sens unique
    - **Vérifier le certificat du serveur**
      - **Chemin vers le fichier CA** Chemin du fichier système.
  - Authentification à double sens
    - **Chemin vers le fichier de clé privée** Emplacement du fichier système.
    - **Chemin vers le fichier de certificat** Emplacement du fichier système.
    - **Vérifier le certificat du serveur**
      - **Chemin vers le fichier CA** Chemin du fichier système.
    - **Suite de chiffrement prise en charge (optionnel)** Aucune entrée requise (seulement recommandé pour les utilisateurs expérimentés). Pour plus de détails, consultez la documentation de votre base de données.

#### Panneau Mail

- **Envoyer des emails**
  - *Oui* Activer l'envoi d'emails.
  - *Non* Désactiver l'envoi d'emails. Il est recommandé de mettre le site hors ligne lorsque la fonction mail est désactivée.
- **Désactiver le mailing de masse**
  - *Oui* Désactiver la fonction d'envoi de mails de masse aux utilisateurs.
  - *Non* Activer la fonction d'envoi de mails de masse aux utilisateurs.
- **Email de l'expéditeur** L'adresse email utilisée pour envoyer les emails du site.
- **Nom de l'expéditeur** Texte affiché dans le champ *De :* lors de l'envoi d'un email depuis le site. Généralement, le nom du site.
- **Email de réponse** L'adresse email qui sera utilisée pour recevoir les réponses des utilisateurs finaux.
- **Nom du destinataire de la réponse** Texte affiché dans le champ *À :* lors de la réponse des utilisateurs finaux aux emails reçus.
- **Mailer** Sélectionnez le programme d'envoi d'emails pour le site.

### Onglet Journalisation

![onglet journalisation de la configuration globale](../../../fr/images/site/global-configuration-logging-tab.png)

#### Panneau Journalisation

- **Chemin vers le dossier de journalisation** Joomla peut conserver un fichier journal de ses propres opérations et des extensions tierces. Fournissez le chemin absolu vers un dossier accessible en écriture par PHP ; s'il manque ou n'est pas accessible en écriture, Joomla ne se chargera pas du tout. Pour des raisons de sécurité, n'utilisez pas un dossier avec un accès global comme `/tmp`.
- **Journaliser presque tout** Journalise tout, sauf les API obsolètes.
- **Journaliser les API obsolètes** Journalise les API obsolètes.

#### Panneau de journalisation personnalisé

- **Priorités du journal** Peut être utilisé pour gérer la journalisation personnalisée. Sélectionnez les événements que vous souhaitez voir dans le fichier journal. Par défaut, *Tous*. Les éléments peuvent être sélectionnés ou désélectionnés en cliquant sur la liste déroulante.
- **Catégories de journal** Liste séparée par des virgules des catégories de journal à inclure ou exclure. Les catégories de journal courantes incluent, mais ne se limitent pas à : `database`, `databasequery`, `database-error`, `deprecated` et `jerror`. Si vide, la journalisation personnalisée est désactivée.
- **Mode de catégorie de journal** Définit le mode pour la liste des catégories de journal ci-dessus.

### Onglet Filtres de texte

![onglet filtres de texte de la configuration globale](../../../fr/images/site/global-configuration-text-filters-tab.png)

Ces paramètres de filtres de texte s'appliqueront à tous les

 champs d'éditeur de texte soumis par les utilisateurs des groupes sélectionnés.

Ces options de filtrage donnent plus de contrôle sur le HTML que vos fournisseurs de contenu soumettent. Vous pouvez être aussi strict ou aussi permissif que nécessaire pour répondre aux besoins de votre site. Le filtrage est opt-in et les paramètres par défaut offrent une bonne protection contre le balisage souvent associé aux attaques de sites Web.

## Conseils

- La plupart de ces paramètres peuvent être définis une fois et ensuite laissés tels quels.
- Si des modifications majeures doivent être apportées, envisagez de mettre le site hors ligne pour tester et vous assurer que tout fonctionne correctement.
- Les paramètres sont enregistrés dans le fichier `configuration.php` à la racine du site. Les permissions de ce fichier sont définies en lecture seule (444) après avoir effectué des modifications via la page de Configuration Globale, et doivent être modifiées en permissions de lecture-écriture par le propriétaire (644) avant toute modification avec un éditeur de texte.

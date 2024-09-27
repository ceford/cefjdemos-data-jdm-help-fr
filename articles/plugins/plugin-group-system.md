<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_System_Group  / Display title: Groupe Système  -->

## Description du Groupe

### Système - Fonctionnalités supplémentaires d'accessibilité

Ce plugin ajoute une barre d'outils d'accessibilité à votre site avec des options d'accessibilité supplémentaires.

![Formulaire des fonctionnalités supplémentaires d'accessibilité du système](../../../en/images/plugins/plugin-group-system-additional-accessibility-features.png)

### Système - Débogage

Ce plugin fournit des informations de débogage. Le rapport est affiché sous l'écran principal des interfaces front-end et back-end d'une installation Joomla!.

#### Onglet du plugin

![Onglet plugin formulaire de débogage système](../../../en/images/plugins/plugin-group-system-debug-plugin-tab.png)

- **Groupes Autorisés** Les groupes d'utilisateurs qui verront les informations de débogage lorsque activé.
- **Afficher le Profiling** Afficher ou non les informations des points de passage du profiling.
- **Afficher les Requêtes** Inclure ou non le journal des requêtes SQL dans les informations de débogage.
- **Afficher l'Utilisation de la Mémoire** Inclure ou non les données d'utilisation de la mémoire dans les informations de débogage.

#### Onglet Langue

![Onglet langue formulaire de débogage système](../../../en/images/plugins/plugin-group-system-debug-language-tab.png)

- **Afficher les erreurs lors de l'analyse des fichiers de langue** Afficher ou non une liste des fichiers de langue avec des erreurs en raison de leur non-conformité à la spécification des fichiers de langue Joomla!.
- **Afficher les Fichiers de Langue** Afficher ou non les fichiers de langue qui ont été chargés pour générer la page.
- **Afficher les Chaînes de Langue** Inclure ou non les chaînes de langue non définies dans les informations de débogage.
- **Supprimer le Premier Mot** Supprimer ou non systématiquement le premier mot dans les chaînes de mots multiples.
- **Supprimer Depuis le Début** Supprime les mots spécifiés au début de la chaîne de langue. Pour plusieurs mots, séparez chaque mot avec le caractère pipe ( | ) : mot1|mot2
- **Supprimer Depuis la Fin** Supprime les mots spécifiés à la fin de la chaîne de langue. Pour plusieurs mots, séparez chaque mot avec le caractère pipe ( | ) : mot1|mot2

#### Onglet de Journalisation

![Onglet de journalisation formulaire de débogage système](../../../en/images/plugins/plugin-group-system-debug-logging-tab.png)

### Système - Champs

Le plugin de champs système requis pour afficher les champs personnalisés.

### Système - En-Têtes HTTP

Ce plugin peut définir des en-têtes de sécurité HTTP. Veuillez consulter la documentation sur la gestion des en-têtes HTTP pour plus de détails sur ce plugin.

![Formulaire des en-têtes HTTP système](../../../en/images/plugins/plugin-group-system-http-headers.png)

### Système - Soulignement

Plugin système pour surligner les termes spécifiés.

### Système - Planificateur de Tâches

Ce plugin recherche des tâches de plugin à exécuter.

![Formulaire du planificateur de tâches système](../../../en/images/plugins/plugin-group-system-job-scheduler.png)

- **Fréquence (en minutes)** Réglez à zéro pour exécuter à chaque chargement de page (pour les tests).
- **Webcron** Configurez sur Oui pour appeler en tant que commande CLI. Pour plus d'informations, consultez l'écriture d'une application CLI.
- **Clé d'Activation** La clé à passer dans une commande Webcron.

### Système - Statistiques Joomla!

![Formulaire des statistiques Joomla! système](../../../en/images/plugins/plugin-group-system-joomla-statistics.png)

- **ID Unique** Un identifiant qui permet au projet Joomla! de compter les installations uniques du plugin. Ceci est envoyé avec les statistiques au serveur.
- **Intervalle (heures)** Les statistiques seront envoyées toutes les X heures. Par défaut, 12.
- **Mode** Sélectionnez la manière dont vous souhaitez envoyer les statistiques.

### Système - Notification de Mise à Jour Joomla!

![Formulaire de notification de mise à jour Joomla! système](../../../en/images/plugins/plugin-group-system-joomla-update-notification.png)

- **Emails des Super Utilisateurs** Une liste séparée par des virgules des adresses email qui recevront les emails de notification de mise à jour. Les adresses dans la liste DOIVENT appartenir aux utilisateurs existants de votre site ayant le privilège de Super Utilisateur. Si aucun des emails listés n'appartient à des Super Utilisateurs, ou si le champ est laissé vide, tous les Super Utilisateurs de ce site recevront l'email de notification de mise à jour.
- **Langue de l'Email** Si vous choisissez Auto (par défaut), l'email de notification de mise à jour aux Super Utilisateurs sera dans la langue du site au moment où le plugin est déclenché. En sélectionnant une langue ici, vous forcez les emails de notification de mise à jour à être envoyés dans cette langue spécifique.

### Système - Code Langue

Fournit la possibilité de changer le code langue dans le document HTML généré pour améliorer le SEO. Les champs apparaîtront lorsque le plugin est activé et enregistré. Plus d'informations sur W3.org.

### Système - Filtre de Langue

![Formulaire du filtre de langue système](../../../en/images/plugins/plugin-group-system-language-filter.png)

- **Sélection de la Langue pour les Nouveaux Visiteurs** Choisir la langue par défaut du site ou détecter automatiquement les paramètres du navigateur.
- **Changement Automatique de Langue** Cette option changera automatiquement la langue du contenu utilisé dans le Frontend lorsqu'un utilisateur change de langue du site.
- **Associations** Permet l'association d'éléments lors du passage d'une langue à une autre.
- **Ajouter des Balises Meta Alternatives** Ajouter des balises meta alternatives pour les éléments de menu avec des éléments de menu associés dans d'autres langues.
- **Ajouter la Balise Meta x-default** Ajouter la balise meta x-default pour améliorer le SEO.
- **Langue x-default** Choisissez votre langue x-default.
- **Supprimer le Code Langue de l'URL** Supprimer ou non le code langue de l'URL défini (ex. your_domain_name/en) de votre langue de contenu qui correspond à la langue par défaut du site lorsque URL SEF est réglé sur *Oui*.
- **Durée de Vie du Cookie** Les cookies de langue peuvent être configurés pour expirer à la fin de la *Session* ou après une *Année*.

### Système - Rotation des Journaux

![Formulaire de rotation des journaux système](../../../en/images/plugins/plugin-group-system-log-rotation.png)

- **Rotation des Journaux (en jours)** Fréquence de rotation des journaux.
- **Nombre Maximum de Journaux** Le nombre maximal de journaux anciens à conserver.

### Système - Déconnexion

Le plugin de déconnexion système permet à Joomla! de rediriger l'utilisateur vers la page d'accueil s'il choisit de se déconnecter alors qu'il se trouve sur une page à accès protégé.

### Système - Cache de Page

Ce plugin active la mise en cache des pages. La mise en cache des pages permet au serveur web de sauvegarder des instantanés des pages et de les utiliser lors de la fourniture des pages web. Cela améliore les performances de votre site web et réduit la charge du serveur. Ce plugin dispose des options suivantes:

![Formulaire du cache de page système](../../../en/images/plugins/plugin-group-system-page-cache.png)

- **Utiliser la Mise en Cache du Navigateur** Utiliser ou non le mécanisme de stockage d'un cache de page dans le navigateur local. Par défaut, *Non*.
- **Exclure les Éléments de Menu** Sélectionnez les éléments de menu que vous souhaitez exclure du cache.

### Système - Consentement à la Confidentialité

Ce plugin permet de recueillir le consentement de vos utilisateurs à la politique de confidentialité du site et de gérer l'expiration du consentement.

![Formulaire de consentement à la confidentialité système](../../../en/images/plugins/plugin-group-system-privacy-consent.png)

- **Résumé de la Politique de Confidentialité** Permet de saisir un résumé de votre politique de confidentialité ou de conserver l'existant.
- **Type de Confidentialité** Choisir entre Article et Élément de Menu. Selon le choix, l'un ou l'autre des deux champs suivants sera présent.
- **Article de Confidentialité** Sélectionnez ou créez un article pour votre politique de confidentialité à lier au formulaire de votre utilisateur.
- **Élément de Menu de Confidentialité** Sélectionnez ou créez un élément de menu lié à un article contenant votre politique de confidentialité.
    - *Note :* Soyez particulièrement prudent avec les sites multilingues. Mieux vaut s'assurer que l'article ou l'élément de menu existe en tant qu'Associations dans toutes les langues.
- **Message de Redirection** Le message qui sera affiché lors de la redirection. Saisissez votre propre message ou conservez l'existant.

![Onglet expiration du formulaire de consentement à la confidentialité système](../../../en/images/plugins/plugin-group-system-privacy-consent-expiration.png)

- **Activer** (Oui/Non) L'expiration est désactivée par défaut. Activez-la si vous souhaitez effectuer des vérifications de l'expiration des consentements de confidentialité.
- **Vérification Périodique (jours)** (0 à 120 jours) 30 jours par défaut. Si l'expiration est activée, définissez le nombre de jours pour effectuer la vérification.
- **Expiration** (180 à 720 jours) 360 jours par défaut. Si l'expiration est activée, définissez le nombre de jours après lesquels le consentement à la confidentialité expire.
- **Rappel** (0 à 120 jours) 30 jours par défaut. Si l'expiration est activée, définissez le nombre de jours avant l'expiration du consentement à la confidentialité pour envoyer un rappel.

### Système - Redirection

![Formulaire de redirection système](../../../en/images/plugins/plugin-group-system-redirect.png)

- **Collecter les URLs** Cette option contrôle la collecte des URLs. Cela est utile pour éviter des charges inutiles sur la base de données.
- **Inclure le Nom de Domaine dans les URLs Expirées** Enregistrer l'URL expirée en tant qu'absolue (inclut le domaine) ou relative (exclut le domaine).
- **Exclure les URLs** Définir des expressions régulières ou des termes à exclure lors de l'enregistrement.

### Système - Se Souvenir de Moi

Ce plugin fournit la fonctionnalité *Se Souvenir de Moi*. Cela permet au site web de *se souvenir* de votre nom d'utilisateur et de votre mot de passe afin que vous puissiez être automatiquement connecté lorsque vous revenez sur le site. Ce plugin n'a pas d'options.

### Système - SEF

Ce plugin ajoute la prise en charge SEF aux liens dans le document. Il fonctionne directement sur le HTML et ne nécessite pas de balise spéciale. Il dispose des options suivantes:

![Formulaire du SEF système](../../../en/images/plugins/plugin-group-system-sef.png)

- **Domaine du Site** Si votre site est accessible par plus d'un domaine, entrez le domaine préféré (parfois appelé canonique) ici. Note : https://example.com et https://www.example.com sont des domaines différents.

### Système - Purge des Données de Session

![Formulaire de purge des données de session système](../../../en/images/plugins/plugin-group-system-session-data-purge.png)

- **Activer le Nettoyage des Données de Session** Lorsqu'il est activé, ce plugin tentera de purger les données expirées en fonction de la fréquence calculée par la probabilité et le diviseur.
- **Activer le Nettoyage des Métadonnées de Session** Lorsqu'il est activé, ce plugin nettoiera les métadonnées optionnelles des sessions de la base de données. Notez que cette opération ne sera pas effectuée lorsque le gestionnaire de base de données est utilisé, car ces données sont effacées dans le cadre de l'opération de nettoyage des données de session.
- **Probabilité** En combinaison avec le champ diviseur, ces deux champs sont utilisés pour déterminer la fréquence de déclenchement de l'opération de nettoyage des données de session lors d'une requête.
- **Diviseur** En combinaison avec le champ probabilité, ces deux champs sont utilisés pour déterminer la fréquence de déclenchement de l'opération de nettoyage des données de session lors d'une requête. La probabilité est calculée en utilisant probabilité/diviseur, par exemple 1/100 signifie qu'il y a 1 % de chances que le processus s'exécute à chaque requête.

### Système - Aller à la Navigation

Le plugin crée un menu déroulant composé de liens vers les endroits importants sur une page web donnée. Cela permet aux utilisateurs de claviers et de lecteurs d'écran de passer rapidement à l'emplacement souhaité en le choisissant dans la liste des options.

![Formulaire d'aller à la navigation système](../../../en/images/plugins/plugin-group-system-skip-to-navigation.png)

### Système - Journal des Actions Utilisateurs

![Formulaire du journal des actions utilisateurs système](../../../en/images/plugins/plugin-group-system-user-actions-log.png)

- **Nombre de jours avant suppression des journaux** Entrez le nombre de jours pendant lesquels les journaux doivent être conservés avant d'être supprimés. Entrez 0 si vous ne souhaitez pas supprimer les journaux.

### Système - Journal des Utilisateurs

![Formulaire du journal des utilisateurs système](../../../en/images/plugins/plugin-group-system-user-log.png)

- **Journalisation des Identifiants** Cette option enregistrera le nom d'utilisateur utilisé lorsqu'une authentification échoue.

*Traduit par openai.com*


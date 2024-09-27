<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Authentication_Group  / Display title: Groupe d'authentification -->

## Description du Groupe

Les plugins de ce groupe sont utilisés pour la connexion standard des utilisateurs aux interfaces du Site ou de l'Administrateur. Le paramètre par défaut est l'authentification Joomla. La méthode *Cookie* est utilisée en conjonction avec la fonction *Se souvenir de moi* uniquement pour la connexion au Site. Le cookie est défini après la première connexion avec l'une des autres méthodes.

## Authentification - Cookie

![plugin d'authentification par cookie](../../../en/images/plugins/plugin-group-authentication-cookie.png)

- **Durée de vie du cookie** Le nombre de jours avant l'expiration du cookie d'authentification. D'autres facteurs peuvent le faire expirer avant cette date. Des durées plus longues sont moins sécurisées.
- **Longueur de la clé** La longueur de la clé utilisée pour chiffrer le cookie. Des longueurs plus importantes sont plus sécurisées, mais elles ralentiront les performances.

## Authentification - Joomla

Ce plugin traite la méthode d'authentification utilisateur par défaut dans Joomla. Il n'a pas d'options.

## Authentification - LDAP

Ce plugin traite l'authentification des utilisateurs contre un serveur LDAP.

![plugin d'authentification ldap](../../../en/images/plugins/plugin-group-authentication-ldap.png)

- **Hôte** L'URL de l'hôte. Par exemple, `openldap.mycompany.org`.
- **Port** Le numéro de port. La valeur par défaut est 389.
- **LDAP V3** Indique si cet hôte utilise la version 3 du LDAP. La valeur par défaut est LDAP v2.
- **Négocier TLS** Indique si on doit utiliser le cryptage TLS avec cet hôte. Si réglé sur *Oui*, tout le trafic vers et depuis ce serveur doit être crypté.
- **Suivre les Références** Indique si le drapeau LDAP_OPT_REFERRALS doit être réglé sur Oui ou Non. Pour les hôtes Windows 2003, cela doit être réglé sur Non.
- **Méthode d'Autorisation** *Se lier directement en tant qu'utilisateur* ou *Se lier et rechercher*.
- **DN de Base** Le DN de base de votre serveur LDAP.
- **Chaîne de Recherche** Une chaîne de requête utilisée pour rechercher un utilisateur donné. Le mot-clé `[search]` est remplacé par le login saisi par l'utilisateur. Par exemple : `uid=[search]`. Plus d'une chaîne de recherche peut être entrée. Séparez chaque chaîne par un point-virgule `;`. Ceci est seulement utilisé lors de la recherche.
- **DN de l'Utilisateur** Le mot-clé [username] est remplacé dynamiquement par le nom d'utilisateur saisi par l'utilisateur. Une chaîne d'exemple est : `uid=[username], dc=[my-domain], dc=[com]`. Plus d'une chaîne peut être entrée. Séparez chaque chaîne par un point-virgule `;`. Ceci est seulement utilisé si la méthode d'autorisation ci-dessus est réglée sur *Se lier directement en tant qu'utilisateur*.
- **Nom d'Utilisateur et Mot de Passe de Connexion** Ceux-ci définissent les paramètres de connexion pour la phase de recherche de DN. Pour une recherche anonyme, laissez ces deux champs vides. Pour une connexion administrative, le *Nom d'Utilisateur de Connexion* est le nom d'un compte administratif (par exemple, *Administrator*). Dans ce cas, le *Mot de Passe de Connexion* est le mot de passe réel de ce compte administratif.
- **Map : Nom Complet** L'attribut LDAP qui contient le nom complet de l'utilisateur.
- **Map : Email** L'attribut LDAP qui contient l'adresse email de l'utilisateur.
- **Map : ID Utilisateur** L'attribut LDAP qui contient l'ID de connexion de l'utilisateur. Pour Active Directory, c'est `sAMAccountName`.
- **Débogage** Active le débogage codé en dur au niveau 7.

*Traduit par openai.com*


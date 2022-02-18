# top 10 OWASP

fiche du 17 septembre 2021

## A01:2021-Broken Access Control

Les failles d'injection, telles que SQL, NoSQL, OS (commande) et l'injection LDAP, se produisent lorsque des données non fiables sont envoyées à un interpréteur dans le cadre d'une commande ou d'une requête. Les données hostiles de l'attaquant peuvent amener l'interpréteur à exécuter des commandes involontaires ou à accéder aux données sans autorisation appropriée

Les points d'injection courants sont :

- Cookies
- Champs de formulaire masqués
- En-têtes HTTP
- Données de formulaire
- paramètres GET
- HTML5
- Objets de stockage

## A02:2021-Cryptographic Failures

## A03:2021-Injection

## A04:2021-Insecure Design

Survient lorsque les methodes de traitement sont absent. Par exemple,la vérification, le chiffrement des données, le nettoyage des données.

## A05:2021-Security Misconfiguration

Cela survient si:

- Des élémnts non necessaire sont istaller( port, package,librairie...)
- Mot de passe par default non changé
- Permissions mal configurées

## A06:2021 – Vulnerable and Outdated Components

## A07:2021 – Identification and Authentication Failures

La confirmation de l'identité de l'utilisateur, l'authentification et la gestion des sessions sont essentielles pour se protéger contre les attaques liées à l'authentification.

## A08:2021 – Software and Data Integrity Failures

Les défaillances d'intégrité des logiciels et des données concernent le code et l'infrastructure qui ne protègent pas contre les violations d'intégrité. Par exemple, lorsque des objets ou des données sont encodés ou sérialisés dans une structure qu'un attaquant peut voir et modifier, il est vulnérable à une désérialisation non sécurisée.

## A09:2021 – Security Logging and Monitoring Failures

cette catégorie doit aider à détecter, escalader et répondre aux violations actives. Sans journalisation et surveillance, les violations ne peuvent pas être détectées.

## A10:2021 – Server-Side Request Forgery (SSRF)

Les failles SSRF se produisent chaque fois qu'une application Web récupère une ressource distante sans valider l'URL fournie par l'utilisateur. Elle permet à un attaquant de contraindre l'application à envoyer une requête spécialement conçue vers une destination inattendue, même lorsqu'elle est protégée par un pare-feu, un VPN ou un autre type du réseau ACL.

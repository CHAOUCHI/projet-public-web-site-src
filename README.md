# Projet Public web Site

Concevez un serveur HTTP avec nodejs. Ce serveur HTTP doit pouvoir délivrer des données statiques, c'est à dire de simples fichiers.

L'objectif final de ce projet est de vous faire concevoir un serveur web fonctionnel utilisable comme serveur de test pour vos propres sites internet. En somme. Nous avons en quelque sorte codé un genre de mini Apache ou nginx.

## Code Source
Faite un git clone : https://github.com/CHAOUCHI/projet-public-web-site-src

```bash
git clone https://github.com/CHAOUCHI/projet-public-web-site-src
```

## Cahier des charges

| Tache | Description | Précision |
|-|-|-|
|Envoyer les fichiers | Servir tout fichier contenu dans le dossier public | Le client ne doit JAMAIS pouvoir accéder à un autre dossier que public.|
| Type mime | Le serveur doit fournir le type MIME correspondant au fichier demandé par le client. | Vous avez le droit d'utiliser l'extension npm `mime-types` qui fournit des fonctions pour deviner le type mime en fonction d'une extension de fichier : https://www.npmjs.com/package/mime-types |
| StatusCode | Une requête **réussie** doit se solder par un code de statut **200**. Une requête **échoué** à cause du client doit se solder par un statutCode **400**.
| Page d'accueil | Si l'utilisateur ne précise aucun fichier particulier, il doit recevoir le fichier index.html par défaut. |
| (Bonus) Injection | Protégez votre serveur contre les injections|

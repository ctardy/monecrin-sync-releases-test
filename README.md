# Mon Écrin — publications de test du client bureau

Ce dépôt reçoit les **publications de test** du client bureau Mon Écrin (Windows et macOS), produites
par le job Jenkins `monecrin-desktop-release` avec `CIBLE=test`. Elles servent à éprouver la mise à
jour automatique sur les postes de test, avant toute publication publique.

**Ne pas installer** ces versions : la version publique est publiée sur
[ctardy/monecrin-sync-releases](https://github.com/ctardy/monecrin-sync-releases) et téléchargeable
depuis www.monecrin.com.

Chaque release porte un `SHA256SUMS.txt` signé (Ed25519) ; le client refuse tout artefact dont la
signature ne correspond pas à la clé publique qu'il embarque.

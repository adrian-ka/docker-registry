# Docker Registry mit einer UI
Für die erstellten Docker Images wird als Grundlage ```Docker Registry 2.x``` von [Docker](https://hub.docker.com/_/registry) und als Frontend ```craneoperator``` von [parabuzzle](https://hub.docker.com/r/parabuzzle/craneoperator) verwendet.
## Inhalt
Folgende Versionen sind enthalten:
- Docker Registry: ```registry:2.6.2```
- Docker UI: ```parabuzzle/craneoperator:latest```
## Start
1. Zum Starten: ```docker-compose up -d```
2. Aufruf des Webservers: ```http://localhost:5080```
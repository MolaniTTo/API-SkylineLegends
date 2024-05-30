# API-SkylineLegends
En aquest repositori es troba el projecte de la API feta amb Nodejs del videojoc Skyline Legends, produit per David Sanz, Arnau Molano i Raúl Palomo.

# SkylineLegends API

## Descripció

Aquest repositori conté l'API per al videojoc SkylineLegends, desenvolupada amb Node.js. L'API proporciona funcionalitats essencials per gestionar els recursos del joc, incloent la creació de usuaris, la gestió de l'inventari, la gestio de les partides, i altres operacions relacionades amb el joc.

## Tecnologies utilitzades

- **Node.js**: Plataforma de JavaScript per al backend.
- **Express**: Framework de Node.js per crear aplicacions web i API.
- **Nodemon**: Eina que ajuda en el desenvolupament de Node.js, reiniciant l'aplicació automàticament quan es detecten canvis en els arxius del projecte.

## Instruccions d’ús

1. Obrir la base de dades desde Replit, perque es pugui connectar i recuperar les dades.
2. 
### Requisits previs

- Node.js i npm instal·lats.

### Endpoints principals

- **GET /jugadores**: Retorna tots els jugadors.
- **POST /checklogin**: Autenticació d'usuaris.
- **PUT /update**: Obtenir la llista de personatges.
- **GET /inventario**: Crear un nou personatge.
- **PUT /updateState**: Obtenir la llista de missions disponibles.
- **GET /naves**: Afegir una nova missió.
- **PUT /naves/:idnave**: Obtenir l'inventari del jugador.
- **GET /ranking**: Actualitzar l'inventari del jugador.
- **GET /partidas**: Actualitzar l'inventari del jugador.
- **POST /insertPartida**: Actualitzar l'inventari del jugador.


## Contribució

Si voleu contribuir al desenvolupament d'aquesta API, seguiu aquests passos:

1. Feu un fork del repositori.
2. Creeu una nova branca (`git checkout -b feature/nova-feature`).
3. Feu els canvis necessaris i cometeu-los (`git commit -m 'Afegeix nova feature'`).
4. Empenyeu els canvis a la branca (`git push origin feature/nova-feature`).
5. Creeu una pull request.

## Llicència

Aquest projecte està sota la llicència MIT. Vegeu l'arxiu [LICENSE](LICENSE) per més detalls.


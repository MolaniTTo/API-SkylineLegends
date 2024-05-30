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

### Requisits previs

- Node.js i npm instal·lats.

### Endpoints principals

- **GET /jugadores**: retorna tots els jugadors.
- **POST /checklogin**: autenticació d'usuaris, inici de sessió i creació d'usuaris.
- **PUT /update**: actualitza les monedes de la taula jugadors.
- **GET /inventario**: retorna les naus que té cada jugador.
- **PUT /updateState**: actualitza l'inventari dels jugadors.
- **GET /naves**: retorna totes les naus.
- **PUT /naves/:idnave**: actualitza el id de les naus.
- **GET /ranking**: retorna el ranking de les partides.
- **GET /partidas**: retorna totes les partides.
- **POST /insertPartida**: inserta els registres d'una partida.

## Enllaç de descarrega: https://drive.google.com/file/d/12zr3E9KIPpyQbBokbRGe3jyiKbnEXwD9/view?usp=drive_link



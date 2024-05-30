# API-SkylineLegends
En aquest repositori es troba el projecte de la API feta amb Nodejs del videojoc Skyline Legends, produit per David Sanz, Arnau Molano i Raúl Palomo.

# SkylineLegends API

## Descripció

Aquest repositori conté l'API per al videojoc SkylineLegends, desenvolupada amb Node.js. L'API proporciona funcionalitats essencials per gestionar els recursos del joc, incloent la creació de personatges, el maneig de missions, la gestió de l'inventari, i altres operacions relacionades amb el joc.

## Tecnologies utilitzades

- **Node.js**: Plataforma de JavaScript per al backend.
- **Express**: Framework de Node.js per crear aplicacions web i API.
- **MongoDB**: Base de dades NoSQL utilitzada per emmagatzemar dades del joc.
- **Mongoose**: Biblioteca d'ODM (Object Data Modeling) per a MongoDB i Node.js.
- **JWT (JSON Web Tokens)**: Per a l'autenticació i autorització.
- **dotenv**: Per gestionar variables d'entorn.
- **Nodemon**: Eina que ajuda en el desenvolupament de Node.js, reiniciant l'aplicació automàticament quan es detecten canvis en els arxius del projecte.

## Instruccions d’ús

### Requisits previs

- Node.js i npm instal·lats.
- MongoDB instal·lat i en execució.

### Instal·lació

1. Clonar el repositori:
    ```bash
    git clone https://github.com/el_teu_usuari/SkylineLegends.git
    ```

2. Navegar a la carpeta del projecte:
    ```bash
    cd SkylineLegends
    ```

3. Instal·lar les dependències:
    ```bash
    npm install
    ```

4. Crear un arxiu `.env` a la carpeta arrel del projecte amb les següents variables d'entorn:
    ```env
    PORT=3000
    MONGODB_URI=your_mongodb_uri
    JWT_SECRET=your_secret_key
    ```

### Execució

1. Executar l'aplicació en mode desenvolupament:
    ```bash
    npm run dev
    ```

   O en mode producció:
    ```bash
    npm start
    ```

### Endpoints principals

- **POST /api/register**: Registre de nous usuaris.
- **POST /api/login**: Autenticació d'usuaris.
- **GET /api/characters**: Obtenir la llista de personatges.
- **POST /api/characters**: Crear un nou personatge.
- **GET /api/missions**: Obtenir la llista de missions disponibles.
- **POST /api/missions**: Afegir una nova missió.
- **GET /api/inventory**: Obtenir l'inventari del jugador.
- **POST /api/inventory**: Actualitzar l'inventari del jugador.

Per més detalls sobre els endpoints i els seus paràmetres, consulteu la documentació de l'API.

## Contribució

Si voleu contribuir al desenvolupament d'aquesta API, seguiu aquests passos:

1. Feu un fork del repositori.
2. Creeu una nova branca (`git checkout -b feature/nova-feature`).
3. Feu els canvis necessaris i cometeu-los (`git commit -m 'Afegeix nova feature'`).
4. Empenyeu els canvis a la branca (`git push origin feature/nova-feature`).
5. Creeu una pull request.

## Llicència

Aquest projecte està sota la llicència MIT. Vegeu l'arxiu [LICENSE](LICENSE) per més detalls.


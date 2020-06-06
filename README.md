ECOLETA
=======

A project that aims to help people find collection points efficiently.

A marketplace for waste collection points localization =)

## Techs

#### Backend

![Typescript](https://www.vectorlogo.zone/logos/typescriptlang/typescriptlang-icon.svg) Typescript

![Node.js](https://www.vectorlogo.zone/logos/nodejs/nodejs-horizontal.svg)

#### Frontend

![React](https://www.vectorlogo.zone/logos/reactjs/reactjs-ar21.svg)

#### Mobile

**React-native**

![Expo](https://www.vectorlogo.zone/logos/expoio/expoio-ar21.svg)

---
## Runnig the application in dev mode

1. Start the backend `/server`:
    ```
    cd server
    yarn install
    yarn knex:migrate
    yarn knex:seed
    yarn dev
    ```
1. Frontend WEB - `/web`:
    ```
    cd web
    yarn install
    yarn start
    ```
1. Mobile - Run expo `/mobile`:
    ```
    cd mobile
    yarn install
    yarn start
    ```

---
Next steps:

- Containerize fullstack development enviroment with docker-compose
- Deploy backend (/server) to **Heroku**
- Depoly frontend (/web) to **Netlify**

# ![DevSuperior logo](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/devsuperior-logo-small.png) Spring React Week
Responsive full-stack movie rating application. A monorepo divided into backend and frontend, using Spring, PostgreSQL, React, and many others technologies. It has 4 encounters, in each episode, the teacher [Nelio Alves](https://github.com/acenelio) explains step-by-step what he's doing.

See the Netlify deploy [here](https://hilbert-dsmovie.netlify.app/).

![Animação](https://user-images.githubusercontent.com/52302576/153282063-d5dd62e0-c03c-495f-aec9-caf9e3a35a56.gif)

## Objective

- **Episode 1 - Spring and React in the market**:
    - Create backend and frontend projects
    - Using monorepos
    - Static frontend mounting (react clean, css and sprites)


- **Episode 2 - Going Deeper in Practice**:
    - Backend implementation
    - Domain model
    - Configuring database
    - MVC structure
    - REST API endpoints
    - Cloud

- **Episode 3 - The career  map**:
    - Backend and frontend integration
    - Three pillars of React
        - Components
        - Props
        - State
    - React Hooks
        - useState
        - useEffect
        - useParams
        - useNavigate

- **Episode 4 - Questions and answers**:
    - Answering students questions in the communication channels

## Execute locally

### Prerequisites

* Java 17
* PostgreSQL and PgAdmin (only in [dev] profile)
* Any Java IDE with Spring support
* Maven
* Npm

### Front End
__Inside '/frontend' directory__

__Install dependencies__
```shell
npm install
```
__Init frontend in dev profile__
```shell
npm run start
```

### Back End
__Inside '/backend' directory__

__Install dependencies__
```shell
mvn dependency:resolve
```

__Choose profile ('dev' for PostgreSQL or 'test' for H2 database) in '../application.properties' file__

In 'dev' profile you must seed PostgreSQL querying './create.sql' content. 

```
spring.profiles.active=${APP_PROFILE:test}
```

__Run spring__
```shell
mvn spring-boot:run
```

## Used techs
- Git & Github

### 🎨 Front End
- ReactJS
- React Router DOM
- Axios
- Git & Github
- Netlify
- Typescript
- styled-components

### 🔧 Back End
- Java
- Spring Boot
- Spring Data JPA
- Spring Web
- H2 Database
- Heroku
- PostgreSQL
- Postman

## Realization
[DevSuperior](https://devsuperior.com.br)

[![DevSuperior no Instagram](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/ig-icon.png)](https://instagram.com/devsuperior.ig)
[![DevSuperior no Youtube](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/yt-icon.png)](https://youtube.com/devsuperior)

## Thanks - DRY 😄
Inspired by PT-BR documentation of:

[Marlene Morais](https://github.com/MarleneMoraes) ⭐

[Pedro Bicudo](https://github.com/PedroBicudo) ⭐


> Project status: Concluded :heavy_check_mark:

# <center>  Manual de Instalação

#### Histórico de versão<br>

|      Data      | Versão | Descrição | Autor(es)|
| -------------- | --------- | --------- | -------- |
| 17.10.2021     |    0.1    | Criação e Edição do documento| Letícia Karla araújo |

### Objetivo do documento

<div align="justify">O objetivo deste manual é orientar o usuário na configuração do projeto <b>Robô Garçom</b> e, como utilizá-lo.</div>

### Frontend
* Via Docker:
    * Pré requisitos
        - [Docker](https://docs.docker.com/engine/install/ubuntu/)
        - [Docker Compose](https://docs.docker.com/compose/install/)

    * Iniciar a API

        ```shell
        docker-compose build
        docker-compose up
        ```

* Manualmente
    * Pré requisitos
        -  [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/#windows-stable)
        
    * Iniciar a API
        ```shell
        yarn install
        yarn start
        ```

### Backend
* Via Docker
    * Pré requisitos
        - [Docker](https://docs.docker.com/engine/install/ubuntu/)
        - [Docker Compose](https://docs.docker.com/compose/install/)

    * Iniciar a API

        ```shell
        docker-compose build
        docker-compose up
        ```
* Manualmente
    * Pré requisitos
        -  [NPM](https://nodejs.org/en/download/current/)
        
    * Iniciar a API
        ```shell
        npm install
        npm start
        ```


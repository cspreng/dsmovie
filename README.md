# DSVendas 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/cspreng/dsmovie/blob/main/LICENSE) 

# Sobre o projeto

https://sprengmovie.netlify.app

DSMovie é uma aplicação full stack web e mobile construída durante a Semana Spring React, evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em uma uma lista de filmes, onde ao selecionar o filme é possivel dar notas ao filme após o e-mail verificado. É feita uma media das notas e transformado na quantidade de estrelas que o filme foi avalidado.
As nostas são de 1 a 5, mesma quantidade de estrelas sendo que avaliação vai de sem estrelas, meia estrela e estrela cheia.

## Layout mobile
![Mobile 1](https://github.com/cspreng/dsmovie/blob/main/frontend/src/assets/img/mobileprincipal.png) ![Mobile 2](https://github.com/cspreng/dsmovie/blob/main/frontend/src/assets/img/mobileavaliação.png)

## Layout web
![Web 1](https://github.com/cspreng/dsmovie/blob/main/frontend/src/assets/img/telainicial.jpg)

![Web 2](https://github.com/cspreng/dsmovie/blob/main/frontend/src/assets/img/telavaliação.jpg)

## Modelo conceitual
![Modelo Conceitual](https://github.com/cspreng/dsmovie/blob/main/frontend/src/assets/img/modeloconceitual.png)

## Padrão camadas
![Padrão camadas](https://github.com/cspreng/dsmovie/blob/main/frontend/src/assets/img/padrãocamada.png)

## Lógica:
- 1- Informar email, id do filme e valor da avaliação (1 a 5).
- 2- Recuperar usuário do banco de dados pelo email. Se o usuário não existir, insira no banco.
- 3- Salvar a avaliação do usuário para o dado filme.
- 4- Recalcular a avaliação média do filme e salvar no banco de dados.
![Lógica](https://github.com/cspreng/dsmovie/blob/main/frontend/src/assets/img/logica.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 17

```bash
# clonar repositório
git clone https://github.com/cspreng/dsmovie

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/cspreng/dsmovie

# entrar na pasta do projeto front end web
cd frontend

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Carlos Eduardo Spreng

www.linkedin.com/in/carlos-spreng


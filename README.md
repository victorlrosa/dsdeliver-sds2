# DS DELIVERY
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/victorlrosa/dsdeliver-sds2/blob/main/LICENSE) 

# Sobre o projeto

https://dsdelivery-sds2vlr.netlify.app/

O DS Delivery é uma aplicação fullstack construída na segunda edição da **Semana DevSuperior**, evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em selecionar os produtos desejados, o local de entrega do pedido e exibir o valor final da compra.

Um dos principais objetivos dessa aplicação é consumir uma API externa, no caso, a API do MapBox utilizada para selecionar o local da entrega do pedido no mapa.

## Layout Web
![Produtos](https://github.com/victorlrosa/assets-sds1/blob/main/assets-dsdeliver/prods.png)

![Map](https://github.com/victorlrosa/assets-sds1/blob/main/assets-dsdeliver/map.png)

# Tecnologias Utilizadas

## Back end
- Java
- Spring Boot
- JPA/Hibernate
- Maven

## Front end
- HTML/CSS/JS/TypeScript
- ReactJs
- MapBox

## Implantação em produção
- Backend: Heroku
- Frontend: Netlify
- Banco de Dados: PostgreSQL

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/victorlrosa/dsdeliver-sds2.git

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/victorlrosa/dsdeliver-sds2.git

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Victor Luiz Rosa

https://www.linkedin.com/in/victor-luiz-rosa

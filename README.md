# Projeto DSDeliver

Aplicação de uma plataforma de Delivery construída com back-end em JAVA com Spring Boot com conexao com banco de dados relacional Postgre, 
com conexão com a nuvem atraves da plataforma Heroku. Front-end Web desenvolvido com ReactJS e integração com a API de mapas Leaftlet,
disponibilizado online através da plataforma Netlify. Front-end Mobile desenvolvido com React Native.

### Link para acessar plataforma web

https://talyson-moreira-sds2.netlify.app/

## Screenshots: Web-Desktop (Visão do Cliente)

### - Tela Inicial

<img src="https://user-images.githubusercontent.com/45837182/104060778-304aed00-51d6-11eb-8a18-bcbc2b8dfa13.jpg" width="900">

### - Tela de Produtos e Mapa

<img src="https://user-images.githubusercontent.com/45837182/104060819-3e990900-51d6-11eb-9309-272568924bfc.jpg" width="900">
<img src="https://user-images.githubusercontent.com/45837182/104060881-583a5080-51d6-11eb-975c-83e3e3d40e53.jpg" width="900">

## Screenshots: Mobile (Visão do Entregador)

### - Tela Inicial, Tela de Pedidos e Tela de Confirmação

<p float="left">
  <img src="https://user-images.githubusercontent.com/45837182/104103533-61ccc280-5281-11eb-82ab-6559538279a3.jpeg" width="250">
  <img src="https://user-images.githubusercontent.com/45837182/104103553-76a95600-5281-11eb-9234-a7a071a2fe34.jpeg" width="250">
  <img src="https://user-images.githubusercontent.com/45837182/104103565-82951800-5281-11eb-807b-bedc28ea31a5.jpeg" width="250">
</p>

## Inicializando um Projeto Local

### Front-end Web-Desktop
1. Instalar NodeJs *(Requisito Obrigatório)*
2. Para instalar dependencias do front-end web: Digitar ```npm install``` no terminal de comandos do VSCode na pasta **front-web** do projeto
3. Para executar projeto: Digitar ```npm start``` no terminal de comandos do VSCode na pasta **front-web** do projeto

### Front-end Mobile
1. Instalar app Expo no seu dispositivo Android ou iOS
2. Ler QR Code
2. Para instalar dependencias do front-end mobile: Digitar ```npm install``` no terminal de comandos do VSCode na pasta **front-mobile** do projeto
3. Para executar projeto: Digitar ```npm start``` no terminal de comandos do VSCode na pasta **front-mobile** do projeto

### Back-end
1. Instalar JAVA JDK 11 *(Requisito Obrigatório)*
2. Instalar STS (Spring Tools 4) *(Requisito Obrigatório)*
3. Importar pasta backend no STS
4. Botão direito em ```src/main/java -> Run As -> Spring Boot APP```

<h1 align="center">
	Project
</h1>

<h3 align="center">
	Aplicação em Node
</h3>

<p align="center">
	<img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square"/>
</p>

<h4 align="center">
	Status: 🚀 Finalizado
</h4>
<p align="center">
	<a href="#about">About</a> •
	<a href="#tech-stack">Tech Stack</a> •
	<a href="(075)98155-5110">Contact</a> 
</p>

## About

<h5 align="left"> Autenticação de usuario </h5> 

A estrategia adotada nesse projeto foi o Passeport é a biblioteca de autenticação node.js, a integração foi feita com NestJs `@nestjs/passport` módulo.

Nesse projeto, os clientes começarão autenticando com um nome de usuário e senha. Depois de autenticado, o servidor emitirá um JWT que pode ser enviado como um [token de portador em um cabeçalho de autorização](https://tools.ietf.org/html/rfc6750) em solicitações subsequentes para comprovar a autenticação. Também criaremos uma rota protegida acessível apenas para solicitações que contenham um JWT válido. 

Em resumo:

- Autenticar o usuário (Usuario/Senha). 

- Estenderemos isso emitindo um JWT.

-  Rota protegida que verifica um JWT válido na solicitação que tem como prazo de expiração de 1d.

  

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installations

```bash
$ yarn add --save-dev @types/passport-local 
(O Passport fornece uma estratégia chamada passaporte-local que implementa um mecanismo de autenticação de nome de usuário/senha, que atende às nossas necessidades para esta parte do nosso caso de uso.)
$ nest g module auth
$ nest g service auth
$ yarn add --save @nestjs/jwt passport-jwt
O @nestjs/jwtpacote é um pacote utilitário que ajuda na manipulação do JWT.
$ yarn add --save-dev @types/passport-jwt

```

## Tech Stack
<img src="https://img.shields.io/badge/Git-05122A?style=flat&logo=git" alt="git Badge" height="25">&nbsp;<img src="https://img.shields.io/badge/Html5-05122A?style=flat&logo=html5" alt="html5 Badge" height="25">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Nodejs-05122A?style=flat&logo=node.js" alt="nodejs Badge" height="25">&nbsp;<img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" height="25"><img src="https://img.shields.io/badge/Typescript-05122A?style=flat&logo=typescript" alt="typescript Badge" height="25">&nbsp;<img src="https://img.shields.io/badge/Javascript-05122A?style=flat&logo=javascript" alt="javascript Badge" height="25">&nbsp;



<img align="left" src="https://avatars.githubusercontent.com/Tielson?size=100">

Made with ❤️ by [Tielson](https://github.com/Tielson), get in touch!

<a href="mailto:filipe_thielsom@hotmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email Badge" height="25"></a>&nbsp;
<a href="https://www.linkedin.com/in/https://www.linkedin.com/in/filipe-tielson-developer/" target="_blank"><img src="https://img.shields.io/badge/Linkedin-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn Badge" height="25"></a>&nbsp;

<br clear="left"/>

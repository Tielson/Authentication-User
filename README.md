<h1 align="center">
	Project
</h1>

<h3 align="center">
	NodeJs application
</h3>

<p align="center">
	<img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square"/>
</p>

<h4 align="center">
	Status: 🚀 Finished
</h4>
<p align="center">
	<a href="#about">About</a> •
	<a href="#tech-stack">Tech Stack</a> •
	<a href="(075)98155-5110">Contact</a> 
</p>

## About

<h5 align="left">User authentication </h5>

The strategy adopted in this project was Passeport is the node.js authentication library, the integration was done with NestJs `@nestjs/passport` module.

In this project, clients will start by authenticating with a username and password. Once authenticated, the server will issue a JWT that can be sent as a [bearer token in an authorization header](https://tools.ietf.org/html/rfc6750) in subsequent requests to prove authentication. We'll also create a protected route accessible only to requests that contain a valid JWT.

In short:

- Authenticate the user (User/Password).

- We will extend this by issuing a JWT.

- Protected route that checks for a valid JWT in the request that has an expiration time of 1d.
  

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installations

```bash
$ yarn add --save-dev @types/passport-local 
$ nest g module auth
$ nest g service auth
$ yarn add --save @nestjs/jwt passport-jwt
$ yarn add --save-dev @types/passport-jwt

```

## Tech Stack
<img src="https://img.shields.io/badge/Git-05122A?style=flat&logo=git" alt="git Badge" height="25">&nbsp;<img src="https://img.shields.io/badge/Html5-05122A?style=flat&logo=html5" alt="html5 Badge" height="25">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Nodejs-05122A?style=flat&logo=node.js" alt="nodejs Badge" height="25">&nbsp;<img src="https://img.shields.io/badge/Typescript-05122A?style=flat&logo=typescript" alt="typescript Badge" height="25">&nbsp;<img src="https://img.shields.io/badge/Javascript-05122A?style=flat&logo=javascript" alt="javascript Badge" height="25">&nbsp;



<img align="left" src="https://avatars.githubusercontent.com/Tielson?size=100">

Made with ❤️ by [Tielson](https://github.com/Tielson), get in touch!

<a href="mailto:filipe_thielsom@hotmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email Badge" height="25"></a>&nbsp;
<a href="https://www.linkedin.com/in/https://www.linkedin.com/in/filipe-tielson-developer/" target="_blank"><img src="https://img.shields.io/badge/Linkedin-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn Badge" height="25"></a>&nbsp;

<br clear="left"/>

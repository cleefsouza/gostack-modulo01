<h1 align="center">
	Rocketseat Bootcamp GoStack 9.0
</h1>

<blockquote align="center">
	Módulo 01 do Bootcamp GoStack da Rocketseat
</blockquote>

<p align="center">
	<a href="_blank">
		<img alt="Node.js Version" src="https://img.shields.io/badge/node.js-v13.12.0-green?style=flat-square">
	</a>
	<img alt="NPM Version" src="https://img.shields.io/badge/npm-v6.14.4-critical?style=flat-square">
	<img alt="YARN Version" src="https://img.shields.io/badge/yarn-v1.19-blue?style=flat-square">
</p>

Neste módulo é apresentado os conceitos do Node.js e API Rest colocando-os em prática através do desenvolvimento de uma simples API Rest

## Requisitos
- Node.js
- npm ou yarn

## Dependências
- express `4.16.4`
- nodemon `2.0.3`

## Configuração para Desenvolvimento

Clone este repositório
```sh
git clone git@github.com:cleefsouza/gostack-modulo01.git
```

Instale as dependências do projeto utilizando npm ou yarn
```sh
npm install | yarn update
```

## Executando

Com as depedências atualizadas, execute o comando
```sh
yarn dev
```

## Rotas

#### Obter todos os usuários

```http
GET /users HTTP/1.1
Host: localhost:3000
```

#### Obter usuário

```http
GET /users/1 HTTP/1.1
Host: localhost:3000
```
#### Adicionar usuário

```http
POST /users HTTP/1.1
Content-Type: application/json
Host: localhost:3000
Content-Length: 21

{
	"name": "Junior"
}
```

#### Editar usuário

```http
PUT /users/2 HTTP/1.1
Content-Type: application/json
Host: localhost:3000
Content-Length: 19

{
	"name": "Yumi"
}
```

#### Remover usuário

```http
DELETE /users/1 HTTP/1.1
Host: localhost:3000
```

## Meta

Cleef Souza – [@cleefsouza](https://www.linkedin.com/in/aryosvalldo-cleef/) – a.cleef.souza@gmail.com

https://github.com/cleefsouza
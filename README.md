# Multi Tenant Role Based Access Control (RBAC) Authentication API

## Features
* Create an application
* Register a user for an application
* Login
* Create a role
* Assign a role to a user

* Check user permissions with a guard

## What are we using?
* [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm)
* [Fastify](https://www.fastify.io/)
* [PostgreSQL](https://www.postgresql.org/)
* [TypeScript](https://www.typescriptlang.org/)

## What you'll need
* Editor - [VS Code](https://code.visualstudio.com/download)
* Node.js - [Download](https://nodejs.org/en/download/)
* A database - [PostgreSQL by Neon](https://bit.ly/tomdoestech)
* A REST client - [Thunder Client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)

## What are the learning outcomes
* How to create a multi tenant application
* How to create a role based access control system
* Some basic relational database concepts
* A nice and neat file structure for backend services
* TypeScript
* Fastify
* RESTful API design
* How to use Drizzle ORM

## Data structure
<img src ="./img/diagram.png" />

## Data flow
<img src ="./img/data-flow.png" />

## Helpful files
* CMD - Commands used
* api.json - Thunder Client collection

## Tips
* Infer the applicationId from the JWT where possible
* Include the applicationId in queries

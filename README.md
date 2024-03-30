<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Orders Microservice

![Ing Progress](https://img.shields.io/badge/Status-In%20Progress-yellow)

<!-- ## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository. -->

## Installation

```bash
# clone this repository
$ git clone https://github.com/Juudini/orders_microservice.git

# move to project directory
$ cd orders_microservice

# install dependencies
$ pnpm install
```

## Running the app as Dev mode

```bash
# up docker container
$ docker compose up -d

# up Nats server
$ docker run -d --name nats-main -p 4222:4222 -p 6222:6222 -p 8222:8222 nats

# migrate the initial schema
$ npx prisma migrate dev

# watch mode
$ pnpm run start:dev
```

Make sure you have the `.env` file in the root folder.

## 🔗 Links

<a href="https://www.linkedin.com/in/juandebandi/"><img alt="LinkedIn" title="LinkedIn" src="https://custom-icon-badges.demolab.com/badge/-LinkedIn-231b2e?style=for-the-badge&logoColor=F8D866&logo=LinkedIn"/></a>
<a href="https://juandebandi.dev/"><img alt="Portfolio" title="Portfolio" src="https://custom-icon-badges.demolab.com/badge/-|Portfolio-1F222E?style=for-the-badge&logoColor=F8D866&logo=link-external"/></a>
<a href="mailto:juudinidev@gmail.com">
<img src="https://custom-icon-badges.demolab.com/badge/-Email-231b2e?style=for-the-badge&logoColor=F8D866&logo=gmail" alt="Email">
</a>

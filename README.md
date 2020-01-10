# JP_Stripes Connect 2020

This repository is a developmemt toolkit to manage WordPress theme.

The theme file will be pushed to [Shifter](https://www.getshifter.io), a supercool WordPress static hosting service.

## Requirements

Strongly recommended to use Mac, since this repository uses Makefile to alias some commands.

- Docker and docker-compose

## Commands

### Boot cluster

    make up

### Stop cluster

    make down

## Hosts and Passwords

### WordPress

http://localhost:8000

- username: user
- password: password
- email: user@example.com

### Adminer

http://localhost:8080

- hostname: mysql
- username: root
- password: password
- database: wordpress

## Contributors

- [tomodian](https://github.com/tomodian)

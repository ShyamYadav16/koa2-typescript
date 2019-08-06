# Node - Koa - Typescript Project


[![NPM version](https://img.shields.io/npm/v/node-typescript-koa-rest.svg)](https://www.npmjs.com/package/node-typescript-koa-rest)
[![Dependency Status](https://david-dm.org/javieraviles/node-typescript-koa-rest.svg)](https://david-dm.org/javieraviles/node-typescript-koa-rest)
[![Build Status](https://travis-ci.org/javieraviles/node-typescript-koa-rest.svg?branch=develop)](https://travis-ci.org/javieraviles/node-typescript-koa-rest)


The main purpose of this repository is to build a good project setup and workflow for writing a Node api rest in TypeScript using KOA and an SQL DB.

Koa is a new web framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs. Through leveraging generators Koa allows you to ditch callbacks and greatly increase error-handling. Koa does not bundle any middleware within core, and provides an elegant suite of methods that make writing servers fast and enjoyable.

## Features:
 * Nodemon - server auto-restarts when code changes
 * Koa v2
 * TypeORM (SQL DB) with basic CRUD included
 * Class-validator - Decorator based entities validation
 * Docker-compose ready to go
 * Travis CI - Heroku deployment prepared

## Included middleware:
 * koa-router
 * koa-bodyparser
 * Winston Logger
 * JWT auth koa-jwt
 * Helmet (security headers)
 * CORS

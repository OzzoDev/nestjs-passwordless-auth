# nestjs-auth-boilerplate

Modern authentication boilerplate for NestJS with OAuth 2.0, passwordless magic link login, JWT, cookies, PostgreSQL, and Docker.

## Features

* OAuth 2.0 (Google)
* Passwordless email magic link authentication
* JWT access + refresh tokens
* Cookie-based auth (web) + JWT response (mobile support)
* Refresh token rotation
* PostgreSQL with Prisma / TypeORM (configurable)
* Docker setup
* Modular NestJS architecture
* Ready for RBAC (roles & permissions)

## Goals

This project aims to provide a reusable authentication starter for NestJS projects following modern security practices:

* No password storage
* OAuth support
* Passwordless login
* Secure refresh token flow
* API + mobile friendly auth

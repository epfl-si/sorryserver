# Contributing

## Prerequisites

* Keybase `epfl_sorry`.

## Setup

```sh
npm i
```

## Run

By default, it starts a server at http://localhost:1234.

```sh
npm start
```

## Build

Bundles and optimizes the application for production.

```sh
npm run build
```

## Deploy

VMs setup and configuration:

```sh
./ansible/sorryserversible
```

Sorryserver page:

```sh
npm run deploy:staging
# or
npm run deploy:prod
```

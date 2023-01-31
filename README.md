# lightsoff-contact-commercants

[![Lint Code Base](https://github.com/LaReserveTech/lightsoff-contact-commercants/actions/workflows/linter.yml/badge.svg)](https://github.com/LaReserveTech/lightsoff-contact-commercants/actions/workflows/linter.yml)

This repo contains two scripts :
- `index.js` to sending SMS or Programmatic Voice Call to commercants
- `pullIncomings.js` to pull responses received by SMS

## Setup
- `npm install`
- Download 'places.json' and 'reviews.json' from Metabase
- Fill .env file
- `node index.js` or `node pullIncomings.js`
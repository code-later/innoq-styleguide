# innoQ Styleguide and Component Library

## Without Docker

Install:

    npm install

This starts a local development server complete with asset pipeline:

    npm start

Export a static site to `./dist/site`

    npm run site

## With Docker & Docker-Compose

    docker-compose up

## Deployment

Everything in master gets deployed automatically to
https://innoq.github.io/innoq-styleguide.

See `.travis.yml` for more info.

## Release to npm

- Increment version in `package.json`
- `git commit`
- `git tag -am "vX.X.X" X.X.X`
- `git push --follow-tags`

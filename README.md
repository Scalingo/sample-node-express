# Sample Application with Node.js and Express Framework

This sample is running on: https://node-express.is-easy-on-scalingo.com/

## Deploy via Git

Create an application on https://scalingo.com, then:

```shell
scalingo --app my-app git-setup
git push scalingo master
```

And that's it!

## Deploy via One-Click

[![Deploy to Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://dashboard.scalingo.com/create/app?source=https://github.com/Scalingo/sample-node-express#master)

## Running Locally

```shell
docker compose build
docker compose run --rm web npm install
docker compose up
```

## Links

Documentation: https://doc.scalingo.com/languages/javascript/nodejs

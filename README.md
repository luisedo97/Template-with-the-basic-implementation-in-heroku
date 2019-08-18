# Template with the basic implementation in heroku.

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku CLI](https://cli.heroku.com/) installed.

## Deployment Preparation

```sh
$ git clone https://github.com/luisedo97/Template-with-the-basic-implementation-in-heroku
$ cd Template-with-the-basic-implementation-in-heroku
```

Before starting with the deploy, add the project you want to publish in the folder called "public".

## Deploying to Heroku

```sh
$ heroku create
$ git add .
$ git commit -m "Deploy"
$ git push heroku master
$ heroku open
```

## Add Change

```sh
$ git add .
$ git commit -m "Add changes"
$ git push heroku master
$ heroku open
```

## Documentation

For more information about using Node.js on Heroku, see these Dev Center articles:

- [Getting Started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
- [Using WebSockets on Heroku with Node.js](https://devcenter.heroku.com/articles/node-websockets)
### Trying out ES6 right now from the command line without installing babel-node globally

We assume you have [lastest Node.js LTS](https://nodejs.org/en/) installed on your laptop.

In a workspace folder (i.e. `./tryes6`), create a package.json file and install dependencies:

```
npm init -y
npm install --save-dev babel-cli
npm install --save-dev babel-preset-es2015
```

Create a .babelrc file:

```
{
  "presets": ["es2015"]
}
```

run some es6 files edited from Luke Hoban's [Overview of ECMAScript 6 features repo](https://github.com/lukehoban/es6features):

```
./node_modules/.bin/babel-node app.js
./node_modules/.bin/babel-node otherapp.js
./node_modules/.bin/babel-node app2.js
```

Find out about [one-on-one JavaScript mentoring at AWebFactory](http://awebfactory.com/mentoring-awebfactory)

[Tell us](http://awebfactory.com/contact) what happened when you ran this and receive a 20% discount!

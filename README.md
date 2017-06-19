### Trying out ES6 right now from the command line without installing babel-node globally

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

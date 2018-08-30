## Server setup
```
yarn add express cross-env body-parser 
```

cross-env will be used to setup node environment variables across platforms

## Using latest javascript feature
setup
```
yarn add -D babel-cli babel-plugin-transform-object-rest-spread babel-preset-env
```
add this script in package.json:
```
"dev": "cross-env NODE_ENV=dev nodemon --exec babel-node src/index.js"
```
create .babelrc


## GraphQL

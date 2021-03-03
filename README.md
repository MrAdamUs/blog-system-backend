Create the Back-end for my blog system.
1- inital my project using "npm init -y"

2- install express and create server.js file

3- install babel`npm i --save-dev @babel/core @babel/node @babel/preset-env`
and create .babelrc folder to do the configration

```
{
"presets": ["@babel/preset-env"]
}
```

4- install nodemon and add start script `{start": "npx nodemon --exec npx babel-node src/server.js",}`

5- install npm i --save mongodb and start create my db and collection

Note: you can use ` npm cache clean npm config set registry http://registry.npmjs.org`
if you have any proble to install the packges

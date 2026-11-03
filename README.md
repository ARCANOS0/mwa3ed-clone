# How to start the project?

```js
npm init -y 
```
this command outputs the `package.json` file that contains information about the project 

then as this project will use `express.js` as a library we use the command 

```js
npm install express
```

then you can `touch index.js` to create the main file, the copy the starting code from [Express.js official website](https://expressjs.com/) and paste it into the `index.js` 


## Important notes 

- Changes on Node.js will not reflect until you restart the server 
- To solve this issue we use a dependency callled `nodemon` *look that we are talking about local development, as handling updates & changes on a server is done by the hosting service* 
- install `nodemon` as a development dependency and not as a normal dependency *means it's related to this local project and will not be hosted on the server as a part of the necessary dependencies for the project* 

use command `npm install --save-dev nodemon`
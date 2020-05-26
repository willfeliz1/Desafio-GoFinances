<h1 align="center">
  Desafio GoStack #7
</h1>
<h1 align="center">
  <img src="https://ik.imagekit.io/l4en7xyqq3/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732e706e67_u7F4RKLkz.png">
</h1>

## 📕 About

The main objective of this challenge is to import and list transactions with local server up from [backend] challenge .

<img src="https://media0.giphy.com/media/RkcdvhvzjRRKSlXcyH/giphy.gif">

## ⚡ Techs

* [React.js] - JavaScript library for building user interfaces.
* [Axios] - Promise based HTTP client for the browser and node.js
* [Typescript] - typed superset of JavaScript that compiles to plain JavaScript.
* [Styled-components] - Visual primitives for the component age.
* [Yarn] - package manager that doubles down as project manager.

## 💻 Installation

### Backend Server

Git clone [backend] and follow installation:

```sh

$ docker run --name gostack_postgree -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgrees

$ docker start gostack_postgree

```
### Start server

Install dependencies and start the server.

```sh

$ yarn
$ yarn dev:server

```

## 🚀 Executing goFinances

```

$ yarn
$ yarn start


```


## If you want to see the unit testing 😊


```sh

$ yarn test

```
### what it expects

```

 src/__tests__/App.tsx
  Dashboard
    📌 should be able to list the total balance inside the cards
    📌 should be able to list the transactions
    📌 should be able to navigate to the import page
    📌 should be able to upload a file

```



[react.js]: <https://reactjs.org/>
[axios]: <https://www.npmjs.com/package/axios>
[typescript]: <https://www.typescriptlang.org/>
[styled-components]: <npmjs.com/package/styled-components>
[Yarn]: <https://yarnpkg.com/>
[backend]: <https://github.com/willfeliz1/Desafio-database-upload>

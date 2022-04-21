<div id="top"></div>

<h1 align="center">Y&A Todo List Assignment Server Node.js JS</h1>

<div align="center">
  <p align="center">
    This server-side application is part of the Y&A Todo List assingment built with Node.js and JavaScript. 
  </p>
    <a href="https://www.postman.com/almoggutin/workspace/y-a-todo-list-assignment/overview">View Postman Files</a>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-application">About The Application</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#how-to-install">How To Install</a></li>
    <li><a href="#available-scripts">Available Scripts</a></li>
    <li><a href="#postman">Postman</a></li>
  </ol>
</details>

<!-- ABOUT THE APPLICATION -->

## About The Application

This server-side application is part of the Y&A Todo List assingment built with Node.js and JavaScript.

It is built with Node.js and Express Framework with Javascript. In addition, the application's database is MongoDB with the use of an ODM like Mongoose.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

-   [Node.js](https://nodejs.org/en/)
-   [Express](https://expressjs.com/)
-   [MongoDB](https://www.mongodb.com/)
-   [Mongoose (ODM)](https://mongoosejs.com/)
-   [Cors](https://www.npmjs.com/package/cors)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- INSTALLATION INSTRUCTIONS -->

## How To Install

**Git clone**

```
git clone https://github.com/almoggutin/YA-Todo-List-Assignment-Server-Node-JS.git
```

**Instructions**

-   After cloning the the repository run `npm i` in order to install all the dependencies.
-   Create an env file in the root of the project named .env and fill in the follwing variables: PORT, MONGODB_URL_PROD, MONGODB_URL_DEV.

<p align="right">(<a href="#top">back to top</a>)</p>

<!--  AVAILABLE SCRIPTS -->

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the production mode.\
However this script is only ment to be run when deploying the application. The application is built, where you need to setup the env variables on the machine that your will be hosting it on or in a webhosting service, unlike in development mode.

Additionally, in the `src/app.js` file you will need to add to the whilist array, allowed origins to make requests to the server.

### `npm run dev`

Runs the app in the development mode.\
Open localhost on the port you decided on in the env variables to view it in the browser.

The page will reload if you make edits with nodemon.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- POSTMAN -->

## Postman

Above, there is a link that will take you to the postman files in my postman profile where you can test the api functionality in the browser.

However, if you would like to run the files locally on your machine in the postman desktop application, included in the repository, in the postman directory all the files so you can import them. In addition you will have to configure env variables in postman so that you will be able to test properly everything.

<div align="center">
  <img src="./assets/postman/postman-global-env-variables.png" alt="Postman global env variables."/>
  <img src="./assets/postman/postman-tasks-env-variables.png" alt="Postman tasks env variables."/>
</div>

<p align="right">(<a href="#top">back to top</a>)</p>

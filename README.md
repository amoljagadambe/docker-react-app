# Getting Started with Create React App

This project was created for docker Tutorials purpose

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!


## Docker Commands

to run the development server
---------

    $ docker-compose up
then access the app from : http://localhost:3000

To run the Production build
------------

    $ docker build -t react-app .
    $ docker run -p 80:80 -d react-app
 then access the service on:  http://localhost:80
 
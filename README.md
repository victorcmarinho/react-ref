# React Reference Architecture
## Develop
`npm start` 
`yarn start` 
[https://localhost:3000]

## Build
`npm run build`
`yarn build` 

## Unit Tests
`npm test`
`yarn test` 


**This is your source code tree:**

```
src
|-- assets
|-- components
|-- hooks
|-- mocks
|-- models
|-- pages
|-- routes
|-- utils
|-- Bootstrap.tsx
|-- App.tsx
|-- index.tsx
...
```

**This is your component structure:**

```
...
components
|-- YourComponent
    |-- index.tsx
    |-- styles.ts
    |-- YourComponent.spc.ts
...
```


`./assets`

Here will be all your project assets as images, icons...

`./components`

Components are presentational only elements, grouping UI items

`./pages`

Pages are mapped in routes and have all the containers needed to implement a functionality

`./routes`

Routes contains the `react-router-dom` implementation to map the project's routes to the respective pages

`./hooks`

Services are responsible to handle the connection with all external elements, like APIs and global functions

`./mocks`

All mock data for your unit testes

`./models`

global interfaces and models that your project needs

`./utils`

Directory to keep all utils functions to share all over the project


### More utils commands

Analyzer your build bundle
`npm run analyze`
`yarn analyze` 


Find and fix Javascrit and TypeScript problems according to pre-defined rules
`npm run analyze`
`yarn analyze` 

Find and fix code formatted
`npm run prettier`
`yarn prettier` 


# Advantages of using this react project template

The project is already configured with:


- React 
- Typescript
- Jest 
- Babel-root-import 
- unit testing example 
- Eslint 
- Prettier 
- Styled Theming 
- Husky  


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

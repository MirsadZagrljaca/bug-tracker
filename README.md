## Welcome to Bug Tracker

### Short Description

Web app for entering and tracking your bugs. Enjoy!

### Technologies

MERN stack app (MongoDB, Express, React and NodeJS with Mongoose)

### To run it you should

- git clone https://github.com/MirsadZagrljaca/bug-tracker
- cd client && npm install && npm start and open browser at localhost:3000
- cd server && npm install && npm start

### Dependecies

#### backend

##### devDependencies

- babel-core
- babel-loader
- babel-preset-env
- babel-preset-stage-2
- nodemon
- webpack
- webpack-cli
- webpack-node-externals

##### dependencies

- body-parser
- compression
- cookie-parser
- cors
- crypto
- dot-env
- express
- express-jwt
- helmet
- jsonwebtoken
- lodash
- mongoose

#### frontend

- axios
- bootstrap
- crypto
- prop-types
- react
- react-bootstrap
- react-dom
- react-google-charts
- react-google-login
- react-router
- react-router-dom
- react-scripts
- react-vis
- web-vitals

### File names explained

#### backend

- config.js - config variables
- auth.controller.js - crud operations for auth route
- bug.controller.js - crud operations for bugs
- user.controller.js - crud operations for users
- dbErrorHelper.js - error messages from db
- bug.model.js - mongoose schema for bugs
- user.models.js - mongoose schema for users
- auth.routes.js - routing for auth
- bug.routes.js - routing for bugs
- user.routes.js - routing for users
- cache.routes.js - routing for cache memory
- express.js - express file
- server.js - main file
- template.js - template for sending to browser

#### frontend

- paragon.png - paragon logo
- header.jpeg - app logo
- Bugs.js - component for diplaying all bugs
- CreateBug.js - form for creating bugs
- Dashboard.js - component for displaying number of bugs per priority
- DeleteBug.js - component for deleting bugs
- EditBug.js - component for editing bugs
- Header.js - header
- Homepage.js - home page 
- Menu.js - menu for going through routes
- SingleBug.js - component for displaying single bug
- auth-api.js - authorised apis
- auth-helpers.js - authorised helpers functions
- bug-api.js - crud for bugs
- cache-api.js - getting cache
- App.js - main component
- index.js - main app file
- index.css - main styling file

#### cache

- cache.js - object that servs function of cache for app
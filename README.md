# MERN Boilerplate
MongoDB Express.js React.js Node.js

A Full MERN Stack Boilerplate for Web Apps. Includes a local authentication system using passport. User is given a simple profile with Full Name and Profile Picture. User is also able to reset password and username case.

NEW: For those of you who wish to separate the client and server into separate projects, I have created two repos that do just that! Check out [MERN Client](https://github.com/DrVicki/starter/tree/master/client) and [MERN Server](https://github.com/DrVicki/starter/tree/master/server).

# Setup Instructions

**Note**: This is a **github template** project. This makes copying the contents of the project
into a new repo very simple.

  - To setup your own project, you will need to copy the contents of this project into a new repo.
    - Click on **Use Template** At Top
    
    ![](https://github.com/DrVicki/starter/blob/master/template-use.png)
    
    - Create a New Respoitory from the Template.
      - Create Name of your respository.
      - Click "Create Repository from Template"
    
    ![](https://github.com/DrVicki/starter/blob/master/template.png)
    
    - Click on "Code"
    - Copy URL Link of your new Repository
    
    ![](https://github.com/DrVicki/starter/blob/master/template-remote.png)
    
    
    - Open VS Code
        - Open "Terminal" from top menue
        - clone down your newly created respository
        
        `git clone use url of your repo here`
        
        - Iitialize repo on local machine
        
        `git init`
        
## Quick Start

### Setup

```
npm install
```

# Install MongoDB
```
npm install mongodb
# or ...
yarn add mongodb
```

## Start a MongoDB Server

For complete MongoDB installation instructions, see [the manual](https://docs.mongodb.org/manual/installation/).

  - Download the right MongoDB version from MongoDB
  - Create a database directory (in this case under /data).
  - Install and start a mongod process.

```
mongod --dbpath=/data
```

You should see the mongod process start up and print some status information.


#### for Development

### Start the client
```
cd client
npm start
```

### Start the server
```
cd server
npm start
```

#### for Production

```bash
npm run build
npm start
```


  - You will need to update the content in these files to names of your project and yourself:

* package.json: name, version, description, repository, author, bugs, homepage
* LICENSE: (update to your preferred license)
* client/index.html: description and title
* this README.md


You can now start updating files in your client to begin working on your own project!

# After each coding session:
  - In VS Code
  
  `git add .`
  
    - To add changes made
    
  `git commit -m "commit message here"`
  
    - Stages changed files
    
   `git push -u origin master`
   
    - pushes changes from your local computer to you GitHb Repository


#### Other Commands

```bash
npm test
npm run lint
npm run lint:fix
npm run test:verbose
npm run test:watch-client
npm run test:watch-server
```



## Features

* Webpack conveniently bundles your code for you.
* Babel lets you use ES6/7 features.
* CSS pre-processor setup for LESS and SASS lets you keep your styles clean and organized.
* ESLint helps you maintain a high level of code quality.
* Jest gives you a robust testing framework to make sure your code works.

## Code Structure

```
- client
  - api
  - assets
    - images
    - icons
  - components
    - atoms
    - molecules
    - organisms
    - templates
    - pages
    - environment
  - hooks
  - store
    - actions
    - reducers
    - thunks
    - tests
  - styles
  - utils
- server
  - config
  - database
  - routes
- scripts
```

Component Heirarchy:

Environment > Pages > Templates > Organisms > Molecules > Atoms

This is based on atomic design. Learn more about [atomic design](http://bradfrost.com/blog/post/atomic-web-design/).

## Technologies

[React](https://facebook.github.io/react/) - View Library

[Redux](http://redux.js.org/) - State Manager

[Webpack](https://webpack.github.io/) - Module Bundler

[Express](http://expressjs.com/) - Node Application Framework

[MongoDB](https://www.mongodb.com/) - Document Database

[Mongoose](http://mongoosejs.com/) - MongoDB Framework

[Passport](http://www.passportjs.org/) - Authentication Framework

[React Notifications Component](https://teodosii.github.io/react-notifications-component/) - Notification System

[Bulma](http://bulma.io/) - CSS Framework

[React Bulma Companion](https://github.com/djizco/react-bulma-companion) - Bulma Component Library

[FontAwesome](http://fontawesome.io/) - Icons

[Ramda](http://ramdajs.com/) - Functional Library

[date-fns](https://date-fns.org/) - Date Functions Library

[SuperAgent](https://github.com/visionmedia/superagent) - HTTP Request Library

[ESLint](http://eslint.org/) - Code Linter

[Jest](https://jestjs.io/) - Testing Framework

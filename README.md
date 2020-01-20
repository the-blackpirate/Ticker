# Ticker
   This app is created with the help of Angular and Ionic Framework with the help of VS Code.
   Ticker helps people to set their goal for the every set of their daily workouts. they can
   set timer for their daily workout.
   
# Dependencies
    Code Editor(Sublime, VS Code) # any you like 
    NPM                           # Node Package Manager
    Ionic                         # Ionic Framework
    Angular                       # Angular CLI 

# Project Repo Structure

     ├── resources                    # Build files on the specific platforms (iOS, Android) and app icon + splash
     ├── src                          # This is where the app lives - *the main folder*
     ├── .editorconfig                # A helper file to define and maintain coding styles across environments
     ├── .gitignore                   # Specifies intentionally untracked files to ignore when using Git
     ├── .io-config.json              # Ionic ID
     ├── config.xml                   # Ionic config file
     ├── .ionic.config.json           # Global configuration for your Ionic app
     ├── package.json                 # Dependencies and build scripts
     ├── readme.md                    # Project description
     ├── tsconfig.json                # TypeScript configurations
     └── tslint.json                  # TypeScript linting options
# SRC Directory Structure of the Project
     ├── ...
       ├── src                       
       │   ├── app                    # This folder contains global modules and styling
       │   ├── assets                 # This folder contains images and the *data.json*
       |   ├── pages                  # Contains all the individual pages (home, tabs, category, list, single-item)
       |   ├── services               # Contains the item-api service that retrieves data from the JSON file
       |   ├── theme                  # The global SCSS variables to use throughout the app
       |   ├── declarations.d.ts      # A config file to make TypeScript objects available in intellisense
       |   ├── index.html             # The root index app file - This launches the app
       |   ├── manifest.json          # Metadata for the app
       │   └── service-worker.js      # Cache configurations
       └── ...
 # Commands to run the Project
 
->>> Install Angular CLI
       $ npm install -g @angular/cli
 
->>> Install Dependencies 
       $ npm i OR npm install
 
->>> Open my-app Directory
       $ cd my-app
 
->>> Serve the Application on web
       $ ionic serve
       
->>> Install Cordova
       $ sudo npm install -g cordova
       
->>> Running on Android 
       $ cordova run android
# Bugs and Issues
Have a bug or an issue with this project ? Open a new issue here on Github. 
# Copyright and License
Copyright 2020 Raghu Sharma. Code released under the [MIT](https://github.com/the-blackpirate/Ticker/blob/master/LICENSE.md) license.

<p align="center">
  <h3 align="center"><a href="https://teknivers.com/">Teknivers</a></h3>

`Teknivers` is an international leading Software Conpany. We provide customers amazing web development services that have been expertly and passionately created. We offer the most effective and affordable digital signage systems.	Your idea matters. You come up with the ideas, and we handle the rest. We have a highly qualified team who can assist you bring your ideas to life.
    
## Table of Contents

    • Getting Started
        ◦ Tools Required
        ◦ Installation
    • Running the App
    • Versioning
    • Authors
    • License
    • Acknowledgments
    
## Getting Started

The project might have multiple branches: master, development, etc. which can be explained here
    • master contains aggregate code of all branches
    • development contains code under development
Other details that need to be given while starting out with the project can be provided in this section. A project structure like below can also be included for the big projects:
        project-title
        ├── README.md
        ├── package.json
        ├── .gitignore
        ├── public
        │   ├── favicon.ico
        │   ├── index.html
        └── src
                ├── App.css
                ├── App.js
                ├── App.test.js
                ├── index.css
                ├── index.js
                ├── logo.svg
                └── serviceWorker.js
                └── setupTests.js
                
## Tools Required

All tools required go here. You would require the following tools to develop and run the project:
 + A terminal like ( Windows terminal for Windows, Homebrew for Mac Os).
 + A text editor or an IDE (like Visual Studio Code, or Sublime Text Editor).
 +  Any relational database software (like Laragon). If you use Laragon then simply go www directory and then clone the repository there and simply run the project as teknivers.test in your browser. NB: To run .test you need to configure laragon as Nginx.
 + A browser like Google Chrome or Mozilla Firefox.


## Installation

You can install and use **Teknivers** as follows:
All installation steps go here.

1. Clone or download this Repositories  
```sh
   https://github.com/Eurosiamart-Rayple-IT-Development/Teknivers
   ``` 
2. If the file was downloaded, then unzip it and open it on a Code Editor.
3. update the composer.
4. Generate the key.
5. make a database named `teknivers`.
6. use migrte command.
7. command, `php artisan serve` to start the server.

## Running the App

<p>Steps and commands for running the app are to be included here</p>
    
### `composer update`

This will fetch the latest matching versions (according to your composer. json file).\
Update the lock file with the new versions.

### `key:generate`

The `key:generate` command is used to generate a random key.\
This command will update the key stored in the application's environment file.

The command also supports an optional --show flag.\
Specifying this flag will simply show the generated key instead of updating any configuration or environment files.

### `php artisan migrate `

`php artisan migrate` publishes all our schema to the database.\
This command also creates the table in the database.

`php artisan migrate:status` checks the status of the migration.\
`migrate:status` checks the migrations we have run.

        
## Deployment

This section is completely optional. Add additional notes about how to deploy this on a live system.

## Contributing

Mention what you expect from the people who want to contribute
We'd love to have your helping hand on Project Title! See CONTRIBUTING.md for more information on what we're looking for and how to get started.

## Versioning

If your project has multiple versions, include information about it here.
For the available versions, see the tags on this repository

## Authors

#### [Teknivers](https://teknivers.com/)
 + [Github](https://github.com/Eurosiamart-Rayple-IT-Development)
 + [Website](https://teknivers.com/)
 + [Facebook](https://www.facebook.com/profile.php?id=100075916298048)
 + [LinkedIn](https://www.linkedin.com/company/eurosiamart/?viewAsMember=true)
    
## License

Teknivers is open source software licensed as MIT.

## Acknowledgments

This section can also be called as Resources or References
    • Code Honor if someone's work was referred to
    • Tutorials followed
    • Articles that helped
    • Inspiration
    • etc


Available Scripts

In the project directory, you can run:
npm start
Runs the app in the development mode.
Open http://localhost:3000 to view it in your browser.
The page will reload when you make changes.
You may also see any lint errors in the console.
npm test
Launches the test runner in the interactive watch mode.
See the section about running tests for more information.
npm run build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.
The build is minified and the filenames include the hashes.
Your app is ready to be deployed!
See the section about deployment for more information.
npm run eject
Note: this is a one-way operation. Once you eject, you can't go back!
If you aren't satisfied with the build tool and configuration choices, you can eject at any time. This command will remove the single build dependency from your project.
Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except eject will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.
You don't have to ever use eject. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.


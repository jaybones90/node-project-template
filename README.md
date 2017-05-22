# Node JS Project Template

This repo contains a shell script which creates your gulpfile, and downloads many of the necessary dependencies for a node.js project.

### Installation/ Usage
* clone or download this repo
* in your shell environment, navigate to the directory containing the repo and enter `$ ./node-project-template`
* once the application opens, you may follow the prompts or press 'Enter' until the package downloads begin
* write some js
* run `$ gulp build` for development environment, or `$ gulp build --production` for production environment (js will be minified)

### Notes
* This script sets up the project in a way that **allows you to use ES6 syntax** (including backticks!) without minification errors.  
* Bower files were not included in this template because Bower will no longer be supported as of May 2017. This template uses npm instead
* average script runtime 30-40 seconds

### Known bugs
No known bugs. Please create an issue or pull request if you see how this script can be more efficient.

### Authors
Jason Ainsworth, Sean Pierce  

_License MIT &copy; 2017_

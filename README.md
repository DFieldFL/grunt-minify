# grunt-minify

## Installation and Setup
1. Install Nodejs / npm
2. Install Ruby and Sass
3. Clone repo
4. Install Node packages `npm install`

## Running
`grunt --static=static_files/`

### Registered Tasks
* default - Watches directories for changes, compiles less/sass, and minifies css/js.
* cleanAll - Deletes all the css and minified js files.
* cleanCss - Deletes the css files.
* cleanJsMin - Deletes the minified js files.
* buildAll - Same as default plus it deletes the non-minified css files.

The static option is the base directory where you store your less, sass, css, and js files. This script expects the directory structure shown below.

    <static option>
    ├── css
    │   ├── blah.css
    │   └── blah.min.css
    ├── js
    │   ├── blah.js
    │   └── blah.min.js
    ├── less
    │   └── blah.less
    └── sass
        └── blah.scss

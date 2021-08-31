# SASS AND NODE MODULES AND OTHER DEPENDENCIES
* npm init
* npm install --save-dev sass
* npm install bootstrap
* npm install --save @fortawesome/fontawesome-free
* npm install postcss-cli autoprefixer --save

* in package.json
 "scripts": {
    "compile:sass": "sass --watch scss:dist/css/"
 },

* npm run compile:sass
* Ctrl-c to stop terminal


## GIT
* touch .gitignore

* in .gitignore: 
node_modules

* git init
* git add .
* git commit -m 'Initial workflow setup'

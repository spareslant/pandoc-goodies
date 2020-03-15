
### How to compile
* cd pandoc-goodies/templates/html5/github/src
* npm init -y
* npm install node-sass
* ./node_modules/node-sass/bin/node-sass --source-map true --output-style=expanded --indent-type space GitHub.scss > GitHub.css
* node css-injector.js

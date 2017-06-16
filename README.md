# Boilerplate 2

A simple boilerplate for building with Grunt.
- `grunt create` creates the initial files
- `grunt bundle` bundles the files in the src/lib and src/css folder and minifies them to dist.
- `grunt server` starts a server, opens a browser window and watches index.html, main.scss and main.js. When an edit is saved it will lint the main.js, generate the main.css, copy the html/main.css/main.js to dist and minify css and js (also to dist).

The dist-HTML then includes normal (for development) and minified versions.
To use the minified versions for the final product, uncomment them in the HTML and delete the normal ones (from the HTML and the dist folder).

## Used/Included libraries and CSS

jQuery
https://github.com/jquery/jquery

Normalize.css (by necolas)
https://github.com/necolas/normalize.css

## To Do


## Build

- run npm install
- run grunt create
- run grunt server

##

# Summary

E-Commerce site built with MEAN stack 

## Description
socket.io was used to achieve a realtime updates in prices and quantities of products.

### Prerequisites

- [Bower](bower.io) (`npm install --global bower`)
- [Ruby](https://www.ruby-lang.org) and then `gem install sass`
- [Grunt](http://gruntjs.com/) (`npm install --global grunt-cli`)
- [MongoDB](https://www.mongodb.org/) - Keep a running daemon with `mongod`

### Developing

1. Run `npm install` to install server dependencies.

2. Run `bower install` to install front-end dependencies.

3. Run `mongod` in a separate bash terminal keep an instance of the MongoDB running

4. Run `grunt serve` to start the development server. It should automatically open the client in your browser when ready.

## Build & development
Run `grunt serve` to work in developpement mode.
Run `grunt build` or `grunt` to build the app and serve a dist folder. 
will run the unit tests with karma config. make sure to check these files incase you need to change anything prior.

## Testing

Running `npm test` will run the unit tests with karma config. make sure to check these files incase you need to change anything prior.

## Production
Running `grunt serve:dist` previews the application in production mode and overwites the previous grunt build dist folder.

##node-copter-webapp

>Use a mobile browser to control the AR Parrot Drone 2.0 via Node.js
>Furthermore we can scan qr-code through out the stream!
>The Project ist still under heavy development!

```javascript
npm install
npm test
npm start
```
RC controlled Node-Copter (compatible with Smarthpones, Tablets and Desktops)

Collaborators
======
- Eschbacher Georg
- Hettegger Michael

Installation
--------

## Cross-Platform

Some Modules of the Testframework need to be installed globally
```javascript
nvm use v0.8.14
npm install -g mocha
npm install -g grunt
npm install -g connect
npm install -g node-gyp
```
### Installing the project itself

move into the root directory of our project and type

```javascript
	npm install
```
in order to get all the dependencies installed.

###### Troubleshooting
1. If you have a problem with zombie and contextify, try to move into
```javascript
xxx/node_modules/zombie/node_modules/jsdom
```
and here type:
```javascript
npm install contextify
```
   because there is a dependency issue with zombie and jsdon/contextify


![drone](http://multimediatechnology.at/~fhs33718/upload/Foto.png)



Repository mmt-b2011/node-copter
==============

RC controlled Node-Copter (compatible with Smarthpones, Tablets and Desktops)

Collaborators
======
- Eschbacher Georg
- Hettegger Michael

Installation
--------

## Cross-Platform

Some Modules of the Testframework need to be installed globally
	nvm use v0.8.14
	npm install -g mocha
	npm install -g grunt
	npm install -g connect
	npm install -g node-gyp

### Installing the project itself

move into the root directory of our project and type
	npm install
in order to get all the dependencies installed.

###### Troubleshooting
1. If you have a problem with zombie and contextify, try to move into
	xxx/node_modules/zombie/node_modules/jsdom
   and here type:
	npm install contextify
   because there is a dependency issue with zombie and jsdon/contextify
# Hello World Angular2 Project

## Tooling in details

#  package.json #
# file in a directory indicates that the directory is the root of a node project.

# Step - 0 : Intialize a node project / npm project

 <code>npm init -y</code>

# Step - 1  - install angular2 core depedency

<code>npm install  @angular/common  @angular/compiler @angular/core @angular/forms @angular/http @angular/platform-browser @angular/platform-browser-dynamic  @angular/router --save


# Step  - 2  - install lib, Libraries that Angular2 is dependent on

<code>npm install core-js rxjs systemjs zone.js reflect-metadata --save        

 
### ISC - License
   - Internet System Consortium - most frequently used license with nodejs project and npm
	

#  Step - 3 - Install Dev dependencies to run the project

<code>npm install concurrently lite-server typescript typings systemjs-builder yargs --save-dev
### details
	-  concurrently:  Run multiple commands concurrently. Like npm run watch-js & npm run watch-less but better.

		- Lightweight development node server for serving a web app, 
		- providing a fallback for browser history API, 
		- loading in the browser, and injecting scripts on the fly.

	- typescript JavaScript with Types Defined.

 	- typings - The TypeScript Definition Manager.

	- Systemjs-builder Builds ES6 into ES5, CommonJS, AMD and globals into a single file in a way that supports the CSP SystemJS loader as well as circular references.

	- Yargs - arguments handling for nodejs, Light-weight option parsing with an argv hash

# tsconfig.json #
#file in a directory indicates that the directory is the root of a TypeScript project.


##typings.json 
	#Typings is the simple way to manage and install TypeScript definitions. It uses typings.json , which can resolve to the Typings Registry, GitHub, NPM, Bower,
	## npm install -g typings
	## https://github.com/typings/typings more detailed way of managing typings

##jsconfig.json
	## VS Code JavaScript Project

## bs-config.json 
	##Lightweight development only node server that serves a web app, opens it in the browser, refreshes when html or javascript change, injects CSS changes using sockets, and has a fallback page when a route is not found.		
	
typings init 
## Intialize Typings.json

typings install dt~core-js --save --global
# install typings for core-js
# **dt - The repository for high quality TypeScript type definitions. http://definitelytyped.org/


# Requirements:nodejs, npm, grunt, grunt-cli

nodejs and npm : see http://nodejs.org/
grunt : in a shell "npm install grunt"
grunt-cli : in a shell "npm install grunt-cli"

# Grunt task (cf. Gruntfile.js)

Package for production : "grunt package"
Continuous build and test for developpement : "grunt dev"

# Project organisation

dist/ : packaged application
lib/ : thirds party librairy like AngularJs, Bootstrap etc...
src/ : sources of the application
	-> app/ : controllers, directives, services, partials organized by functions
	-> asset/ : img, icon, etc...
	-> css/ : css of the application
	-> index.html : application main page
test/ : source for the tests
	-> unit/ : unit, integration test
	-> htmlRunner/ : jasmine html test runner
	-> karma.conf.js : karma configuration
package.json : application description
Gruntfile.js : grunt configuration
Customer Manager System with AngularJS 



This application demonstrates:

* A complete application with read-only and editable data
* Using AngularJS with $http in a factory to access a backend RESTful service
* Using BreezeJS in a factory to access a backend RESTful Service
* Techniques for showing multiple views of data (card view and list view)
* Custom filters for filtering customer and product data
* A custom directive to ensure unique values in a form for email 
* A custom directive that intercepts $http and jQuery requests and displays a loading dialog
* A custom directive that handles highlighting menu items automatically based upon the path navigated to by the user
* Form validation using AngularJS
* Provides login and authentication functionality (currently client-side only - plan to add server-side part too which is absolutely required in a "real" app)
* A custom routing mechanism that allows a controller & template to be downloaded dynamically "on the fly" and provides a standard convention for controller and view names.
 for more details)


## Requirements:


###If you're using Node.js/Express/MongoDB

If you don't already have Node.js on your machine install it from http://nodejs.org. You'll also need to install MongoDB from http://www.mongodb.org if you don't have it already and get it configured and running using the instructions on their site.

In the CustomerManager directory execute 'npm install' to install Express, MongoDB and Mongoose (package.json).

Load MongoDB Sample Data Option 1: 

Load data into MongoDB by performing the following steps:

* Execute 'mongod' to start the MongoDB daemon
* Navigate to the CustomerManager/server directory (the one that has initMongoData.js in it)
* Execute 'mongo' to start the MongoDB shell
* Enter the following in the mongo shell to load the data seed file:
 * use customermanager
 * load("initMongoData.js")

Load Sample Data Option 2: 

Alternatively you can navigate to CustomerManager/server and double-click the initMongoData.bat (Windows) or initMongoData.sh (Mac/Linux) file to initialize MongoDB with the data. 

The Windows script assumes that MongoDB is installed at c:\mongodb while the Linux/Mac script relies on the fact that you have the monogo executable
in the path.

Start the Node/Express server:

* Open a command prompt
* Navigate to the CustomerManager directory
* Run 'npm install' at the command prompt
* Navigate to the CustomerManager/server directory
* Run 'node server.js'






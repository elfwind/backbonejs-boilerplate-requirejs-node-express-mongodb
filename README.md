backbonejs-boilerplate-requirejs-node-express-mongodb
=====================================================

BackboneJS Boilerplate with RequireJS NodeJS Express and MongoDB

This boilerplate includes two functioning models/collections and has a basic data solution included to store data for the collections. I created this repo for personal use but anyone who is interested can use it. If interested, this is intended to help other programmers, who are still fairly new to programming backbone frameworks, understand how models and collections operate and how they relate to data storage. Understanding this concept is one of the most challenging areas of getting started. This repo may be helpful to someone who is interested in learning this great tool by digging in and getting their hands dirty.

If you dont already have the following installed on your machine, then you will need to download and install nodejs, express, socket.io, and mongoDB to run and test locally.

Download nodejs - http://nodejs.org Node provides a JavaScript runtime environment that you can access from your command prompt or terminal. Node will install with a package management (npm) utility, which allows you to install and access third party package libraries and use within your application. To play around with and run this code as is you will need to use the node package manager to install express and socket.io

Install express Open your command prompt or terminal window, change your directory to the folder of your application and type: npm install express

Install socket.io - npm install socket.io

Install mongoDB for windows - http://docs.mongodb.org/manual/tutorial/install-mongodb-on-windows/

Install mongodb for OSX - http://docs.mongodb.org/manual/tutorial/install-mongodb-on-os-x/

docs.mongodb.org also has a number of other installation and getting started guides

Once everything is installed, you will need to start the mongodb and the node server. To do this I open 2 command prompt/terminal windows and:

In the first window type:
> cd path-to-your-folder\mongodb\bin
> mongod

In the second window type:
> cd path-to-your-folder
> node server

open a browser and begin testing with http://localhost:5000/index.html If you don't like port 5000 this can be changed on line 11 in your server.js file.

I am working on writing more detailed documentation for this repo, but for now you can search google and find more information on each of these installs if you feel you need it.

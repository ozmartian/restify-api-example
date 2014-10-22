restify-api-example
===================

Simple REST service on node.js, mongodb using restify.

Setup
===================
Download and install mongodb http://docs.mongodb.org/manual/
Open bin folder and run command line. This will run mongodb server
```javascript
mongod --dbpath <Here goes your path to data folder>
```
Open folder with app.js and run in command line
```javascript
npm install
node app.js
```
This will run your api on http://127.0.0.1:8080
Try to post some data by http://127.0.0.1:8080/jobs url. Open this url in browser. 

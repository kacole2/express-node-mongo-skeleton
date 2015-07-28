express-node-mongo-skeleton
======================
express-node-mongo-skeleton was made to have a simple skeleton for a completed Web App ready to go for demonstration purposes and learning how to build CRUD & REST operations into a Node.js Web App. This is the final example that is demonstrated in [How to Create a Complete Express.js + Node.js + MongoDB CRUD and REST Skeleton](https://www.airpair.com/javascript/complete-expressjs-nodejs-mongodb-crud-skeleton)

## Installation
- Perform a clone of this repo. 
- Make sure MongoDB is installed (`brew install mongodb`)
- Create a MongoDB database named `enmskeleton` (`use enmskeleton`)
- Install packages and start the express.js web service (`npm install && npm start`)
- Navigate to `http://127.0.0.1:3000` to see the express.js welcome page

## Usage Instructions
All of the MVC pieces are built, but are also rudimentary and not flashy. The root of our webapp goes to the express.js landing page, but there is a schema created for a new object called `blobs`. To access `blobs`, follow the route that is already in place by going to `http://127.0.0.1:3000/blobs`.

Add a new blob by going to `http://127.0.0.1:3000/blobs/new`. 
<center><img src="https://s3.amazonaws.com/kennyonetime/blob_new.png" width="400"></center>

After submitting, this will take you back to the index page where you can now `Show` or `Edit` or `Delete` that blob record from the UI
<center><img src="https://s3.amazonaws.com/kennyonetime/blob_all.png" width="600"></center>

All of the REST pieces are baked in as well. You can test them using a multitude of different REST based tools.

## Contribution
Create a fork of the project into your own reposity. Make all your necessary changes and create a pull request with a description on what was added or removed and details explaining the changes in lines of code. If approved, project owners will merge it.

Licensing
---------
express-node-mongo-skeleton is freely distributed under the MIT License. See LICENSE for details
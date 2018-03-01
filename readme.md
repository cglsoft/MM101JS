# Project M101JS MongoDB for Node.js Developers

**Certification Mongo University**


# Setup 

***Install the dependencies.***

Make sure you have a mongod running version 3.2.x of MongoDB.

Import the "item" collection: mongoimport --drop -d mongomart -c item data/items.json
Import the "cart" collection: mongoimport --drop -d mongomart -c cart data/cart.json

> Start Mongo Server  >

### Create Index for $text find work on mongo shell :
```javascript
 use mongomart

 db.item.createIndex( {"title": "text", "slogan": "text","description": "text"});
```

Run the application by typing "node start" in the mongomart directory.
In your browser, visit http://localhost:3000. If you've set up and launched MongoMart correctly, you should see a page that lists the same product repeated five times. Which of the following products is it?

On prompt
```
 npm install
 npm start
```


## License
Copyright &copy; 1996-2018 - CGLSOFT IT Serviços Ltda.<br>
Licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

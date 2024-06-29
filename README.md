# myAPIjokes
CRUD API

This is an API which helps to create, read, update or delete various jokes from an array of jokes. The whole list available has been taken from Angela Yu's course. 
I have also added a master key feature which can help in order to delete all the jokes. Nextly I have used a middleware called body parser which can help read the form encoded data sent through the request. The request can also be made in the form of the json format. 
I have used the ES6 module so in the package.json file, I have added the "type" : "module" in the package.json file and thus have added the import statements. 
I have used dynamic URL in the case of :id in order to receive the required ID from the request itself to print the joke of that given ID.

The modular routers created with express in server/helpers/create_router.js
The structure is separated into two parts: one for the client and one for the server.
Sends the instructions to MongoDB, sets the database up
To establish the routes that will be used (the methods).
In this case method requests.
We’re using a base URL and an ID (in the case of deleteGame) to pass in the delete request.
/ (get all), /:id (get), /:id (to delete) and :/ (to update)
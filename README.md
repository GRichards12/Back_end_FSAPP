# Back end of my full stack app

## Summary

- This app provides routing to servers and interaction with a MongoDB database, providing sign in and sign up functionality to a React site that has functionality like instagram
- Mongoose has been used to interact with the MongoDB as it provides better methods and documentation for the task required.
- The DB entires require a username, password and email to sign up. The password will be hashed before being added to the database.
- Various CRUD features are included, however they're intentionally not part of the front end.

# Design and testing

- This app was made with expressjs, node.js and mongoose. It was tested as working with localhost routing, interacting with the frontend very well.
- There is a deployment subject to change at https://dashboard.heroku.com/apps/restbackendgrich using this repo.

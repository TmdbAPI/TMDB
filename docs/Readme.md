Hi, Glad you're here 😊.


**This repo hosts a revamped version of The Movie Database (TMDB) API documentation. The documentation is built with Mintlify. Check it out [here](https://emiloju.mintlify.app/)**. 



## Process 🧑‍💻
The migration from the official [ReadMe-based documentation](https://developer.themoviedb.org/docs) to Mintlify required a number of processes. They include the following:

1. Testing the endpoints with Postman:

Each endpoint were thoroughly tested on postman to see what works and understand the API parameters.

2. Converting the Postman collection to Open API spec (OAS):

The Postman collection containing all the APIs endpoints were exported as an `openapi.json`. This file was further converted ino a `openapi.yaml` file.

3. Setting up a Mintlify documentation:

A mintlify documentation was setup to document the API reference and other important concepts of the TMDB API.

4. Importing the OAS file to Mintlify:

The `openapi.yaml` file created in step 3 was imported to the Mintlify docs and was added automatically.

## So, what's changed?
1. The new documentation clearly describes the available authentication methods, including when and how to use them
2. Improved information architecture that allows developers find what they need to use the API.
3. Improved UI/UX to improve developer experience while using the docs

Add yours 🤩....
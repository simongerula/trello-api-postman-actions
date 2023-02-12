# trello-api-test-postman

This repository contains a Postman collection for testing the Trello API. The collection includes the following requests:

GET Find board-one

GET Find column-one and column-two in board-one

GET Find card-one and card-two in column-one

DELETE Delete card-one from column-one

GET Find card-one in column-one

POST Post card-one on top of column-one

Additionally, the repository includes a Postman environment to store the Trello API key and other environment variables.

The repository is set up for continuous integration with GitHub Actions. This means that every time you push changes to the repository, GitHub Actions will automatically run tests and report the results.

### Getting Started

#### To use this repository, you'll need to have the following:

- A Trello account and API key.
- Postman installed on your computer.
 Here's how to get started:

1. Clone the repository to your computer.
2. Import the Postman collection into Postman.
3. Import the Postman environment.
4. Update the environment variables with your Trello API key and any other necessary information.
5. Run the requests to test the Trello API.

This README was written by ChatGPT.

[![travis build](https://img.shields.io/travis/yusadolat/Hackerbay-interview-backend.svg?style=flat-square)](https://travis-ci.org/yusadolat/Hackerbay-interview-backend)
[![codecov coverage](https://img.shields.io/codecov/c/github/yusadolat/Hackerbay-interview-backend.svg?style=flat-square)](https://codecov.io/github/yusadolat/Hackerbay-interview-backend)

# Hackerbay Interview Backend

## A simple stateless microservice in Nodejs with the following functionalities -

Authentication
JSON patching
Image Thumbnail Generation
Getting Started
clone the repository

`$ git clone [https://github.com/Yusadolat/Hackerbay-interview-backend]`
install dependencies:

`$ cd hackerbay-interview-backend && npm install`

Then you need to add the private environment variables (API Keys):

### Create a copy of the ".env,example" and name it as ".env".

#### Populate it with the necessary secret keys:

#### macOS / Linux

cp .env.example .env

#### Windows

copy .env.example .env

Then edit the .env file and modify the API keys only for services that you will use.

### Start the application

`npm start`

Now navigate to your browser and open http://localhost:8081. If the port is not set in .env file.
Congratulations – you're all set.

Unit tests

To run the Unit Test Scripts

`$ npm test`

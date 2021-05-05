# H-Appy

[Project Dependencies](dependencies) | [Getting Started](#getting-started) | [Running Tests](#running-tests)

## The activity finder app

Welcome to the backend API of H-Appy. You can see the repository for the frontend client [here](https://github.com/AJ8GH/h-appy-client-clone)

Have you ever wanted to do something, either outdoors indoors, large or small, but the one thing stopping you was inspiration? H-Appy is an app designed to solve this problem. Using a database of carefully thought out activities, categorised by size, cost and accessibility, this API links to the frontend client and provides suggestions to liven up the users free time.

The API is simple in its design and its use.

## Getting Started

You will need a recent version of Node.js installed.

1. First clone this repository

```shell
git clone git@github.com:AJ8GH/h-appy-client-clone.git
```

2. Navigate to the root of the project and install the dependencies
```shell
cd h-appy-client-clone
npm install
```

3. Setting up database access: You will need to create a `.env` file in the root of the project and contact us so that we can grant you access to the database and provide you with some environment variables. Once this is configured, you will be able to run tests, seed the database with data and contribute to the project.

## Running Tests

Make sure you are in the root of the project and run the `npm test` command.

## Usage


## Dependencies

modules:
- `"bcryptjs": "^2.4.3"`
- `"dotenv": "^8.2.0"`
- `"express": "4.17.1"`
- `"jsonwebtoken": "^8.5.1"`
- `"mongoose": "5.11.12"`
- `"prettier": "^2.2.1"`
- `"validator": "^13.5.2"`
- `"chai": "^4.3.4"`
- `"chai-http": "^4.3.0"`
- `"jest": "^26.6.3"`
- `"mocha": "^8.3.2"`
- `"sinon": "^10.0.0"`
- `"supertest": "^6.1.3`

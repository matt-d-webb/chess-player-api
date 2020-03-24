# Chess Player - RESTful API

[![Build Status](https://travis-ci.org/hagopj13/node-express-mongoose-boilerplate.svg?branch=master)](https://travis-ci.org/matt-d-webb/chess-player-api)
[![Coverage Status](https://coveralls.io/repos/github/hagopj13/node-express-mongoose-boilerplate/badge.svg?branch=master)](https://coveralls.io/github/matt-d-webb/chess-player-api?branch=master)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/2ab03f5d62a1404f87a659afe8d6d5de)](https://www.codacy.com/manual/matt-d-webb/chess-player-api?utm_source=github.com&utm_medium=referral&utm_content=matt-d-webb/chess-player-api&utm_campaign=Badge_Grade)


A boilerplate/starter project for quickly building production-ready RESTful APIs using Node.js, Express, and Mongoose.

It comes with many built-in features, such as authentication using JWT, request validation, unit and integration tests, continuous integration, docker support, etc. For more details about the features, check the list below.



## Getting Started

### Installation

Install dependencies:

```bash
yarn install
```

Environment varibales:

```bash
cp .env.example .env

# open .env and modify the environment variables (if needed)
```

### Commands

Running locally:

```bash
yarn dev
```

Running in production:

```bash
yarn start
```

Testing:

```bash
# run all tests
yarn test

# run all tests in watch mode
yarn test:watch

# run test coverage
yarn coverage
```

Docker:

```bash
# run docker container in development mode
yarn docker:dev

# run docker container in production mode
yarn docker:prod

# run all tests in a docker container
yarn docker:test
```

Linting:

```bash
# run ESLint
yarn lint

# fix ESLint errors
yarn lint:fix

# run prettier
yarn prettier

# fix prettier errors
yarn prettier:fix
```


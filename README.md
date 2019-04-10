
# Issue First
#### Search for issues labeled `good-first-issues`, `help-wanted` and `a-bug` using Github's GraphQL and REST APIs.

[![Build Status](https://www.travis-ci.com/hingham/github-graphql.svg?branch=master)](https://www.travis-ci.com/hingham/github-graphql)

##### [Visit Issue First](https://issue-first-github-queries.netlify.com)

### Using the App
* Search for github queries by the issue tags
* Find `good-first-issues` tagged in open source projects

### Using the App to Compare GraphQL vs REST
* Search with GitHub API v4 GraphQL, or v3 REST
  * compare how queries are formatted
  * compare network data for each type of query

## Setting up the App
* clone the repository
* cd into `github-graphql`
* `npm i`
* Add your github token in .env
 `REACT_APP_GIT=github-token-here`


## Starting the App

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open http://localhost:3000 to view it in the browser.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Builds the app for production to the `build` folder.<br>

See react documentation about [deployment](https://facebook.github.io/create-react-app/docs/deployment).

Deployment info has moved here: https://facebook.github.io/create-react-app/docs/deployment

Tools:
### Resources Utilized:
* [Road to build react](https://github.com/the-road-to-graphql/react-graphql-github-apollo/blob/master/src/index.js)
* [Bulma](https://bulma.io/documentation/elements/content/) Layout and UI
* [Stack Overflow](https://stackoverflow.com/questions/48244950/can-i-list-githubs-public-repositories-using-graphql/48245999#48245999) - example of how to query type `...on issue` for SearchItemResults that returns a union of mutltiple issues

#### Tests:
* Assertions made:
  * Query was called on click
  * Query called was correct query
  * ApolloConsumer was rendered
* Assertions that need to be made:
  * REST endpoint data renders
  * The correct number of cards were rendered



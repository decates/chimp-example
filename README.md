# chimp-example
An example of using [Chimp](https://chimp.readme.io) to run BDD tests really easily in Node, using the sample tests from the documentation.

There is a sample [Cucumber](https://cucumber.io/) test, and a sample [Mocha](https://mochajs.org/) test.

## Prerequisites

Just a recent version of NodeJS (v5.3.0 or higher?) and Chrome installed.

## Setting up

1. Clone the repository: `git clone git@github.com:decates/chimp-example.git`
2. Install dependencies: `npm install`

## Running the tests

Run the Cucumber test once only: `npm test`

or, run the mocha test: `npm run-script mocha`

## Watching files

Chimp comes into its own when watching test files for changes, keeping the browser open, and re-running tests quickly to provide rapid feedback.

To watch the Cucumber test (_features/search.feature_): `npm run-script watch`

or to watch the Mocha test (_features/google.js_): `npm run-script mocha-watch`


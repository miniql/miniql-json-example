# MiniQL - JSON files example

An example of MiniQL - the tiny JSON-based query language inspired by GraphQL.

This example shows how to use [miniql](https://www.npmjs.com/package/miniql) and [@miniql/json](https://www.npmjs.com/package/@miniql/json) to run queries against a set of JSON files.

Example [Star Wars data is courtesy of Kaggle](https://www.kaggle.com/jsphyg/star-wars/data).

You need [Node.js](https://nodejs.org/en/) installed to run this example code.

## Repo contents

```
/miniql-json-example
    index.js    -> Example code that runs various queries against the JSON files.
    /data
        ...     -> Various JSON files with data from the Star Wars universe.
```

## Setup

[Download a the zip file of this code](https://github.com/miniql/miniql-json-example/archive/master.zip) or use Git to clone this repository.

Open a terminal, change directory to the repo and install dependencies:

```bash
cd miniql-json-example
npm install
```

## Run the code

Open a terminal, change directory to the repo and run the code using Node.js:

```bash
cd miniql-json-example
npm start
```

A bunch of example queries will run and results are displayed in the terminal.

Please read `index.js` to see each example query.


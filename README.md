[![Build Status](https://travis-ci.org/philipszdavido/mypluralize.svg?branch=v1.0.0)](https://travis-ci.org/philipszdavido/mypluralize)

[![Coverage Status](https://coveralls.io/repos/github/philipszdavido/mypluralize/badge.svg?branch=master)](https://coveralls.io/github/philipszdavido/mypluralize?branch=master)
# mypluralize
A Node.js module that returns the plural form of any noun

## Installation 
    `npm install mypluralize`
## Usage

    ## Javascript
        ```sh
        var pluralise = require('mypluralize');
        var boys = pluralise.getPlural('Boy');

        Output should be 'Boys'
        ```

    # TypeScript
        import { getPlural } from 'mypluralize';
        console.log(getPlural('Goose'))

        Output should be 'Geese'

## Test 
    `npm run test`

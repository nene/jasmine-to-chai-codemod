# Jasmine to Chai Codemod

Codemod for [jscodeshift] to migrate your tests from Jasmine to Chai syntax.

## Use case

This transform may be useful if you have relatively many tests on Jasmine
framework and want to change to some other framework with Chai support or maybe
just add Chai syntax.

## Install

* `npm i -g jscodeshift` to install jscodeshift globally
* Install/clone/download this repository

## Usage

`jscodeshift <your-tests-path> -t <codemod-script>`

For more info see [jscodeshift] documentation.

## Try it

* [Base transforms sandbox]
* [Functions transforms sandbox]

[jscodeshift]: https://github.com/facebook/jscodeshift
[Base transforms sandbox]: https://astexplorer.net/#/iJTkqcTYBm/13
[Functions transforms sandbox]: https://astexplorer.net/#/zIASXvr2Za
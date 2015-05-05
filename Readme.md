# mock-template [![NPM version][npm-image]][npm-url] [![build status][travis-image]][travis-url] [![Test coverage][coveralls-image]][coveralls-url]

> Template mock data generator

Forked from [mockjs](https://github.com/nuysoft/Mock)

## Installation

    npm install mock-template

## Usage

    var template = require('mock-template');
    var data = template.mock('{{title}}');
    // data => { title: 'title' }

See [test](browse/test/template.js) for more example.

## License

MIT

[npm-image]: https://img.shields.io/npm/v/mock-template.svg?style=flat
[npm-url]: https://npmjs.org/package/mock-template
[travis-image]: https://img.shields.io/travis/meituan/mock-template.svg?style=flat
[travis-url]: https://travis-ci.org/meituan/mock-template
[coveralls-image]: https://img.shields.io/coveralls/meituan/mock-template.svg?style=flat
[coveralls-url]: https://coveralls.io/r/meituan/mock-template?branch=master

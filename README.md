# music.interval

[![Build Status](https://travis-ci.org/danigb/music.interval.svg?branch=master)](https://travis-ci.org/danigb/music.interval)
[![Code Climate](https://codeclimate.com/github/danigb/music.interval/badges/gpa.svg)](https://codeclimate.com/github/danigb/music.interval)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)
[![npm version](https://img.shields.io/npm/v/music.interval.svg)](https://www.npmjs.com/package/music.interval)
[![license](https://img.shields.io/npm/l/music.interval.svg)](https://www.npmjs.com/package/music.interval)
[![music.kit](https://img.shields.io/badge/music-kit-yellow.svg)](https://www.npmjs.com/package/music.kit)

Simple and fast musical interval library:

```js
var interval = require('music-interval')
interval.simplify('9M') // => '2M'
interval.invert('3M') // => '6m'
```

This is part of [music.kit](https://www.npmjs.com/package/music.kit). It uses [music.interval.parser](https://github.com/danigb/music.interval.parser) to parse intervals so see this library to understand interval string notation.

## Install

Via npm: `npm i --save music-interval`. Use browserify or webpack to create a browser compatible distribution, or get the [whole thing](https://github.com/danigb/music.kit)

## Usage

#### Simplify an interval

A simple interval is any interval that spawns an octave or less. You can simplify any interval (simplify a simple interval return itself):

```js
interval.simplify('9M') // => '2M'
interval.simplify('2M') // => '2M'
```

#### Get inversion of an interval

You can [invert](https://en.wikipedia.org/wiki/Inversion_(music)#Intervals) an interval with the `invert` function. Notice that all inverted intervals are simples:

```js
interval.invert('2M') // => '7m'
interval.invert('1P') // => '8P'
```

#### More ...

Read the [generated documentation](https://github.com/danigb/music.interval/blob/master/API.md) or take a look to [music.kit](https://github.com/danigb/music.kit)

## License

MIT License

# startup-name-generator

> Let's name your silly startup

Generates cliché (but nice-sounding) names for your startup. [Try it on Codepen](http://codepen.io/ericbai/full/wJyaJb/).

```js
const name = require('@ericbai/startup-name-generator')

name('cloud')
//=> ['Cloudary', 'Purecloud', 'Cloudlayer', 'Echocloud', 'Cloudspan',
//   'Cloudloop', 'Activecloud', 'Cloudspark', 'Cloudable', 'Clouder', ...]
```

[![Status](https://travis-ci.org/ericbai/startup-name-generator.svg?branch=master)](https://travis-ci.org/ericbai/startup-name-generator "See test builds")

## Install

```sh
yarn add --exact @ericbai/startup-name-generator
# or
npm install --save-exact @ericbai/startup-name-generator
```
.js (name `StartupNameGenerator`)

## Command line

Also available as a command-line app.

```sh
yarn global add @ericbai/startup-name-generator
# or
npm install -g @ericbai/startup-name-generator

startup-name-generator health fit run
startup-name-generator --help
```

## Thanks

**startup-name-generator** © 2017, Rico Sta. Cruz. Released under the [MIT] License.<br>
Authored and maintained by Rico Sta. Cruz with help from contributors ([list][contributors]).

> [Eric Bai](http://erics-bai.github.io) &nbsp;&middot;&nbsp;

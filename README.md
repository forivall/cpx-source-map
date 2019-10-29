# cpx-source-map

Source map transform for cpx

[![build status](https://secure.travis-ci.org/forivall/cpx-source-map.svg)](http://travis-ci.org/forivall/cpx-source-map)
[![dependency status](https://david-dm.org/forivall/cpx-source-map.svg)](https://david-dm.org/forivall/cpx-source-map)
[![coverage status](https://coveralls.io/repos/github/forivall/cpx-source-map/badge.svg)](https://coveralls.io/github/forivall/cpx-source-map)

## Installation

```
npm install --save cpx-source-map
```

## Usage

This requires [`cpx`](https://github.com/mysticatea/cpx) > v1.5.0. Until a new
version is released, use `npm install github:mystictea/cpx` to install cpx
directly from the github repo.

Use `cpx-source-map` with the `--transform` flag for cpx. For example, to copy
pure javascript and typedefs to your lib directory, with source maps for vscode
navigation, I use the following:
```sh
cpx --transform cpx-source-map --verbose 'src/**/*.{js,d.ts}' lib
```

## Credits
[Emily Marigold Klassen](https://github.com/forivall/)

## License

ISC

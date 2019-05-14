# Vue Google Search

A Vue google search box to find searches using Google Maps Places API.

[![npm version](https://img.shields.io/npm/v/create-pagin.svg?style=flat-square)](https://www.npmjs.org/package/vue-google-search)
[![npm downloads](https://img.shields.io/npm/dm/vue-google-search.svg?style=flat-square)](http://npm-stat.com/charts.html?package=vue-google-search)
[![LICENSE](https://img.shields.io/github/license/codejunkers1/vue-google-search.svg?style=flat-square)](https://github.com/codejunkers1/vue-google-search)

## Features

- Search places, areas, address
- Get current location with geohash code
- generate your own geohash

## Installing

Using npm:

```bash
$ npm install vue-google-search
```

## Example

Generating `Pagination` for Given data

```js
// import Vue-google-search module to modules
 import VueGoogleSearch from 'vue-google-search'
 export default {
    components: {
        VueGoogleSearch
    }
 }
```

Usage in template
```html
    <vue-google-search
        id="map"
        classname="form-control"
        placeholder="Enter your search location"
        v-on:placechanged="getAddressData"
        :enableGeolocation="true"
        :country="['ind']"
        style="border-radius:0px;"
    >
    </vue-google-search>
```

## Author

[Venkata Sai Katepalli - Full Stack Engineer](http://venkatasaikatepalli.github.io)

## License

MIT

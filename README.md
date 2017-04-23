# npmdoc-node-dht-sensor

#### api documentation for  node-dht-sensor (v0.0.32)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-dht-sensor.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-dht-sensor) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-dht-sensor.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-dht-sensor)

#### Reads data from DHT sensors on Raspberry Pi

[![NPM](https://nodei.co/npm/node-dht-sensor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-dht-sensor)

- [https://npmdoc.github.io/node-npmdoc-node-dht-sensor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-dht-sensor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-dht-sensor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-dht-sensor/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-dht-sensor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-dht-sensor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "David Momenso",
    "name": "node-dht-sensor",
    "description": "Reads data from DHT sensors on Raspberry Pi",
    "version": "0.0.32",
    "repository": {
        "url": "https://github.com/momenso/node-dht-sensor"
    },
    "scripts": {
        "preinstall": "./check-lib.sh",
        "install": "node-gyp configure",
        "postinstall": "node-gyp build"
    },
    "main": "./build/Release/node_dht_sensor",
    "dependencies": {
        "nan": "^2.4.0"
    },
    "license": "LGPL-3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

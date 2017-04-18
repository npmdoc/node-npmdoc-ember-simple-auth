# npmdoc-ember-simple-auth

#### api documentation for  [ember-simple-auth (v1.2.2)](https://github.com/simplabs/ember-simple-auth#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-ember-simple-auth.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ember-simple-auth) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ember-simple-auth.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ember-simple-auth)

#### A lightweight library for implementing authentication/authorization with Ember.js applications.

[![NPM](https://nodei.co/npm/ember-simple-auth.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-simple-auth)

- [https://npmdoc.github.io/node-npmdoc-ember-simple-auth/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-simple-auth/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-simple-auth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-simple-auth/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ember-simple-auth/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ember-simple-auth/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "simplabs GmbH"
    },
    "bugs": {
        "url": "https://github.com/simplabs/ember-simple-auth/issues"
    },
    "dependencies": {
        "broccoli-file-creator": "^1.1.1",
        "ember-cli-babel": "^5.1.7",
        "ember-cli-is-package-missing": "^1.0.0",
        "ember-cookies": "^0.0.13",
        "ember-getowner-polyfill": "^1.1.0",
        "ember-network": "^0.3.0",
        "silent-error": "^1.0.0"
    },
    "description": "A lightweight library for implementing authentication/authorization with Ember.js applications.",
    "devDependencies": {
        "body-parser": "^1.17.1",
        "broccoli-asset-rev": "^2.4.5",
        "broccoli-yuidoc": "^2.1.0",
        "chai": "^3.5.0",
        "cors": "^2.8.1",
        "ember-ajax": "^2.4.1",
        "ember-cli": "2.12.1",
        "ember-cli-addon-tests": "^0.6.3",
        "ember-cli-base64": "~0.0.1",
        "ember-cli-blueprint-test-helpers": "^0.17.1",
        "ember-cli-chai": "^0.3.2",
        "ember-cli-content-security-policy": "~0.6.0",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-eslint": "^3.0.0",
        "ember-cli-fastboot": "^1.0.0-beta.16",
        "ember-cli-htmlbars": "^1.1.1",
        "ember-cli-htmlbars-inline-precompile": "^0.3.6",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-mocha": "^0.13.2",
        "ember-cli-pretender": "^1.0.1",
        "ember-cli-shims": "^1.0.2",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-data": "^2.12.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.6.3",
        "ember-resolver": "^4.1.0",
        "ember-sinon": "~0.7.0",
        "ember-source": "^2.12.0",
        "eslint-config-simplabs": "^0.4.0",
        "eslint-plugin-ember": "^3.1.2",
        "eslint-plugin-mocha": "^4.9.0",
        "express": "^4.15.2",
        "git-repo-version": "^0.4.1",
        "glob": "^7.1.1",
        "handlebars": "~4.0.6",
        "loader.js": "^4.2.3",
        "marked": "^0.3.6",
        "mermaid": "^7.0.0",
        "mocha": "^3.2.0",
        "mocha-only-detector": "0.1.0",
        "morgan": "^1.8.1",
        "request": "^2.81.0",
        "rimraf": "^2.6.1",
        "rsvp": "^3.5.0",
        "sinon-chai": "~2.9.0",
        "torii": "~0.8.2"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "533479d9326e7d629e8ae4f854095df820500b87",
        "tarball": "https://registry.npmjs.org/ember-simple-auth/-/ember-simple-auth-1.2.2.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "versionCompatibility": {
            "ember": ">=1.12"
        }
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "52a2fca9dc522993a24d57b2f9471f639066ee9e",
    "greenkeeper": {
        "ignore": [
            "eslint-plugin-ember",
            "eslint-plugin-mocha"
        ]
    },
    "homepage": "https://github.com/simplabs/ember-simple-auth#readme",
    "keywords": [
        "ember-addon"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "simplabs"
        }
    ],
    "name": "ember-simple-auth",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/simplabs/ember-simple-auth.git"
    },
    "scripts": {
        "build": "ember build",
        "diagrams": "mermaid --sequenceConfig guides/assets/esa-initial-flow.config.json --width 2400 -o guides/assets guides/assets/esa-initial-flow.txt",
        "fastboot": "echo \"Please also run npm start\"; ember fastboot --serve-assets",
        "lint": "eslint app addon blueprints config server test-support tests *.js",
        "start": "ember server",
        "test": "ember test",
        "test:all": "ember try:each",
        "test:fastboot": "mocha fastboot-tests",
        "test:node": "mocha node-tests node-tests/blueprints"
    },
    "version": "1.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

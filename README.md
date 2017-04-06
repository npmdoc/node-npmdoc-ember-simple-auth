# api documentation for  [ember-simple-auth (v1.2.1)](https://github.com/simplabs/ember-simple-auth#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-ember-simple-auth.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ember-simple-auth) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ember-simple-auth.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ember-simple-auth)
#### A lightweight library for implementing authentication/authorization with Ember.js applications.

[![NPM](https://nodei.co/npm/ember-simple-auth.png?downloads=true)](https://www.npmjs.com/package/ember-simple-auth)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-simple-auth/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-ember-simple-auth_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-simple-auth/build/apidoc.html)

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
        "ember-cookies": "^0.0.12",
        "ember-getowner-polyfill": "^1.1.0",
        "ember-network": "^0.3.0",
        "silent-error": "^1.0.0"
    },
    "description": "A lightweight library for implementing authentication/authorization with Ember.js applications.",
    "devDependencies": {
        "body-parser": "^1.17.1",
        "broccoli-asset-rev": "^2.4.5",
        "broccoli-merge-trees": "^2.0.0",
        "broccoli-yuidoc": "~2.1.0",
        "chai": "^3.5.0",
        "cors": "~2.8.1",
        "ember-ajax": "^2.4.1",
        "ember-browserify": "1.1.13",
        "ember-cli": "2.11.0",
        "ember-cli-addon-tests": "^0.6.0",
        "ember-cli-app-version": "^2.0.0",
        "ember-cli-base64": "~0.0.1",
        "ember-cli-blueprint-test-helpers": "^0.17.0",
        "ember-cli-chai": "^0.3.2",
        "ember-cli-content-security-policy": "~0.6.0",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-eslint": "^3.0.2",
        "ember-cli-fastboot": "1.0.0-beta.15",
        "ember-cli-htmlbars": "^1.1.1",
        "ember-cli-htmlbars-inline-precompile": "^0.3.3",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-mocha": "^0.13.1",
        "ember-cli-pretender": "^1.0.0",
        "ember-cli-release": "^0.2.9",
        "ember-cli-shims": "^1.0.2",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-data": "^2.11.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.6.3",
        "ember-resolver": "^2.0.3",
        "ember-sinon": "~0.6.0",
        "ember-source": "^2.11.0",
        "eslint-config-simplabs": "^0.4.0",
        "eslint-plugin-ember": "^3.0.1",
        "eslint-plugin-mocha": "^4.8.0",
        "express": "^4.14.0",
        "git-repo-version": "^0.4.1",
        "glob": "^7.0.5",
        "handlebars": "~4.0.5",
        "loader.js": "^4.0.10",
        "marked": "^0.3.6",
        "mermaid": "^7.0.0",
        "mocha": "^3.0.0",
        "mocha-only-detector": "0.1.0",
        "morgan": "^1.5.2",
        "request": "^2.74.0",
        "rimraf": "^2.6.1",
        "rsvp": "^3.2.1",
        "sinon-chai": "~2.8.0",
        "torii": "~0.8.0"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "6b7af9943ef2d38d6805dec9f8f60f4901884357",
        "tarball": "https://registry.npmjs.org/ember-simple-auth/-/ember-simple-auth-1.2.1.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "gitHead": "6db47d030395aad828e2a12e34a073ea052a5548",
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
            "name": "simplabs",
            "email": "info@simplabs.com"
        }
    ],
    "name": "ember-simple-auth",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
        "test": "ember try:each",
        "test:fastboot": "mocha fastboot-tests",
        "test:node": "mocha node-tests node-tests/blueprints"
    },
    "version": "1.2.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module ember-simple-auth](#apidoc.module.ember-simple-auth)
1.  [function <span class="apidocSignatureSpan">ember-simple-auth.</span>_ensureThisImport ()](#apidoc.element.ember-simple-auth._ensureThisImport)
1.  [function <span class="apidocSignatureSpan">ember-simple-auth.</span>included ()](#apidoc.element.ember-simple-auth.included)
1.  [function <span class="apidocSignatureSpan">ember-simple-auth.</span>treeForVendor ()](#apidoc.element.ember-simple-auth.treeForVendor)
1.  string <span class="apidocSignatureSpan">ember-simple-auth.</span>name



# <a name="apidoc.module.ember-simple-auth"></a>[module ember-simple-auth](#apidoc.module.ember-simple-auth)

#### <a name="apidoc.element.ember-simple-auth._ensureThisImport"></a>[function <span class="apidocSignatureSpan">ember-simple-auth.</span>_ensureThisImport ()](#apidoc.element.ember-simple-auth._ensureThisImport)
- description and source-code
```javascript
_ensureThisImport = function () {
  if (!this.import) {
    this._findHost = function findHostShim() {
      var current = this;
      var app;
      do {
        app = current.app || app;
      } while (current.parent.parent && (current = current.parent));
      return app;
    };
    this.import = function importShim(asset, options) {
      var app = this._findHost();
      app.import(asset, options);
    };
  }
}
```
- example usage
```shell
...
var version = require('./package.json').version;

module.exports = {
name: 'ember-simple-auth',

included: function() {
  this._super.included.apply(this, arguments);
  this._ensureThisImport();

  this.import('vendor/ember-simple-auth/register-version.js');
},

treeForVendor: function() {
  var content = 'Ember.libraries.register(\'Ember Simple Auth\', \'' + version + '\');';
  return writeFile('ember-simple-auth/register-version.js', content);
...
```

#### <a name="apidoc.element.ember-simple-auth.included"></a>[function <span class="apidocSignatureSpan">ember-simple-auth.</span>included ()](#apidoc.element.ember-simple-auth.included)
- description and source-code
```javascript
included = function () {
  this._super.included.apply(this, arguments);
  this._ensureThisImport();

  this.import('vendor/ember-simple-auth/register-version.js');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ember-simple-auth.treeForVendor"></a>[function <span class="apidocSignatureSpan">ember-simple-auth.</span>treeForVendor ()](#apidoc.element.ember-simple-auth.treeForVendor)
- description and source-code
```javascript
treeForVendor = function () {
  var content = 'Ember.libraries.register(\'Ember Simple Auth\', \'' + version + '\');';
  return writeFile('ember-simple-auth/register-version.js', content);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

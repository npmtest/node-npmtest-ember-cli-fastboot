# npmtest-ember-cli-fastboot

#### basic test coverage for  ember-cli-fastboot (v1.0.0-beta.16)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-cli-fastboot.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-cli-fastboot) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-cli-fastboot.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-cli-fastboot)

#### Server-side rendering for Ember.js apps

[![NPM](https://nodei.co/npm/ember-cli-fastboot.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-cli-fastboot)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-cli-fastboot/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-cli-fastboot/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-cli-fastboot/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-cli-fastboot/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-cli-fastboot/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-cli-fastboot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-cli-fastboot/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-cli-fastboot/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ember-cli-fastboot",
    "version": "1.0.0-beta.16",
    "description": "Server-side rendering for Ember.js apps",
    "keywords": [
        "ember-addon"
    ],
    "license": "MIT",
    "author": "Tom Dale & Yehuda Katz <tomhuda@tilde.io>",
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "repository": "https://github.com/ember-fastboot/ember-cli-fastboot",
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "mocha && ember test",
        "test:precook": "node node_modules/ember-cli-addon-tests/scripts/precook-node-modules.js"
    },
    "dependencies": {
        "broccoli-funnel": "^1.0.0",
        "broccoli-merge-trees": "^1.1.1",
        "broccoli-plugin": "^1.2.1",
        "broccoli-stew": "^1.2.0",
        "compression": "^1.6.2",
        "core-object": "^2.0.5",
        "debug": "^2.2.0",
        "ember-cli-babel": "^5.1.7",
        "ember-cli-eslint": "^3.0.2",
        "ember-cli-version-checker": "^1.1.6",
        "express": "^4.8.5",
        "fastboot-express-middleware": "1.0.0-rc.7",
        "fastboot-filter-initializers": "0.0.2",
        "lodash.defaults": "^4.0.1",
        "lodash.uniq": "^4.2.0",
        "md5-hex": "^1.3.0",
        "portfinder": "^1.0.3",
        "rsvp": "^3.0.16",
        "silent-error": "^1.0.0"
    },
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.5",
        "chai": "^3.0.0",
        "chai-fs": "^1.0.0",
        "ember-ajax": "^2.4.1",
        "ember-cli": "2.12.0-beta.1",
        "ember-cli-addon-tests": "^0.6.0",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-htmlbars": "^1.1.1",
        "ember-cli-htmlbars-inline-precompile": "^0.3.3",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-qunit": "^3.1.0",
        "ember-cli-release": "^0.2.9",
        "ember-cli-shims": "^1.0.2",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-string-utils": "^1.0.0",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-data": "^2.11.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.6.0",
        "ember-resolver": "^2.0.3",
        "ember-source": "^2.12.0-beta.1",
        "fs-extra": "^1.0.0",
        "glob": "^7.0.0",
        "loader.js": "^4.1.0",
        "mocha": "^3.0.0",
        "request": "^2.55.0",
        "sinon": "^1.17.4"
    },
    "engines": {
        "node": ">= 4"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "after": [
            "broccoli-asset-rev"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

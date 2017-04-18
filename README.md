# test coverage for  [clone-org-repos (v0.2.5)](https://github.com/tegon/clone-org-repos)  [![npm package](https://img.shields.io/npm/v/npmtest-clone-org-repos.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-clone-org-repos) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-clone-org-repos.svg)](https://travis-ci.org/npmtest/node-npmtest-clone-org-repos)
#### Clones a github organization repositories

[![NPM](https://nodei.co/npm/clone-org-repos.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/clone-org-repos)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-clone-org-repos/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-clone-org-repos/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-clone-org-repos/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-clone-org-repos/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-clone-org-repos/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-clone-org-repos/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-clone-org-repos/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-clone-org-repos/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-clone-org-repos/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-clone-org-repos/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-clone-org-repos/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-clone-org-repos/build/test-report.html](https://npmtest.github.io/node-npmtest-clone-org-repos/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-clone-org-repos/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-clone-org-repos/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-clone-org-repos/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-clone-org-repos/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-clone-org-repos/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-clone-org-repos/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-clone-org-repos/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-clone-org-repos/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Leonardo Tegon",
        "url": "https://github.com/tegon"
    },
    "bin": {
        "cloneorg": "./bin/cloneorg"
    },
    "bugs": {
        "url": "https://github.com/tegon/clone-org-repos/issues"
    },
    "dependencies": {
        "cli": "0.10.0",
        "merge": "1.2.0",
        "prompt": "0.2.14",
        "request": "2.55.0"
    },
    "description": "Clones a github organization repositories",
    "devDependencies": {
        "chai": "^2.3.0",
        "coveralls": "^2.11.2",
        "istanbul": "^0.3.14",
        "mocha": "^2.2.5",
        "sinon": "^1.14.1"
    },
    "directories": {},
    "dist": {
        "shasum": "692e61cc23b0f7e0de82db21d80cf70ae2fc4218",
        "tarball": "https://registry.npmjs.org/clone-org-repos/-/clone-org-repos-0.2.5.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "e648a09348cda1c91e049c4feffce171d0cc09ce",
    "homepage": "https://github.com/tegon/clone-org-repos",
    "keywords": [
        "cli",
        "command line",
        "git",
        "github",
        "clone",
        "git clone",
        "clone repositories",
        "github organization",
        "github org",
        "org repositories",
        "organization repositories",
        "clone organization repositories"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/tegon/clone-org-repos/blob/master/LICENSE-MIT"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "tegon"
        }
    ],
    "name": "clone-org-repos",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/tegon/clone-org-repos.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha ./test/*",
        "test-travis": "./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -- -R spec ./test/*"
    },
    "version": "0.2.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

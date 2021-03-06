# npmtest-dockerode

#### basic test coverage for  [dockerode (v2.4.3)](https://github.com/apocas/dockerode#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-dockerode.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dockerode) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dockerode.svg)](https://travis-ci.org/npmtest/node-npmtest-dockerode)

#### Docker Remote API module.

[![NPM](https://nodei.co/npm/dockerode.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dockerode)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dockerode/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dockerode/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dockerode/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dockerode/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dockerode/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dockerode/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dockerode/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dockerode/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dockerode/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dockerode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dockerode/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dockerode/build/test-report.html](https://npmtest.github.io/node-npmtest-dockerode/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dockerode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dockerode/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dockerode/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dockerode/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dockerode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dockerode/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dockerode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dockerode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pedro Dias"
    },
    "bugs": {
        "url": "https://github.com/apocas/dockerode/issues"
    },
    "contributors": [
        {
            "name": "Pedro Dias",
            "url": "https://github.com/apocas"
        },
        {
            "name": "James Lal",
            "url": "https://github.com/lightsofapollo"
        },
        {
            "name": "Ron Waldon",
            "url": "https://github.com/jokeyrhyme"
        },
        {
            "name": "Everton Ribeiro",
            "url": "https://github.com/nuxlli"
        },
        {
            "name": "Sam Rijs",
            "url": "https://github.com/srijs"
        },
        {
            "name": "Shannon Poole",
            "url": "https://github.com/shannonmpoole"
        },
        {
            "name": "Max Claus Nunes",
            "url": "https://github.com/maxcnunes"
        },
        {
            "name": "Mike MacCana",
            "url": "https://github.com/mikemaccana"
        },
        {
            "name": "Niclas Hoyer",
            "url": "https://github.com/niclashoyer"
        },
        {
            "name": "Nicholas Morsman",
            "url": "https://github.com/nmorsman"
        },
        {
            "name": "Philip Reichenberger",
            "url": "https://github.com/preichenberger"
        },
        {
            "name": "Anton Serdyuk",
            "url": "https://github.com/m00t"
        },
        {
            "name": "Dan Williams",
            "url": "https://github.com/deedubs"
        },
        {
            "name": "Alex Wolfe",
            "url": "https://github.com/alexkwolfe"
        },
        {
            "name": "Henry Allen-Tilford",
            "url": "https://github.com/generalhenry"
        },
        {
            "name": "Geoffrey Bachelet",
            "url": "https://github.com/ubermuda"
        },
        {
            "name": "Jacob Friis Saxberg",
            "url": "https://github.com/webjay"
        },
        {
            "name": "Jeffrey Morgan",
            "url": "https://github.com/jeffdm"
        },
        {
            "name": "Kishore Nallan",
            "url": "https://github.com/kishorenc"
        },
        {
            "name": "Mathias Buus",
            "url": "https://github.com/mafintosh"
        },
        {
            "name": "Matthew Gallagher",
            "url": "https://github.com/mattva01"
        },
        {
            "name": "Wojciech Kocjan",
            "url": "https://github.com/wojciechka"
        },
        {
            "name": "Mike Macaulay",
            "url": "https://github.com/mmacaula"
        },
        {
            "name": "Josh Matthews",
            "url": "https://github.com/jmatth"
        },
        {
            "name": "Vincent Woo",
            "url": "https://github.com/vincentwoo"
        },
        {
            "name": "Lewis J Ellis",
            "url": "https://github.com/LewisJEllis"
        },
        {
            "name": "Adam Duncan",
            "url": "https://github.com/microadam"
        }
    ],
    "dependencies": {
        "concat-stream": "~1.5.1",
        "docker-modem": "0.3.x",
        "tar-fs": "~1.12.0"
    },
    "description": "Docker Remote API module.",
    "devDependencies": {
        "bluebird": "^3.5.0",
        "chai": "^3.5.0",
        "memorystream": "~0.2.0",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7ec55b492fc9f289e77325ff07c6a3a96021b4f2",
        "tarball": "https://registry.npmjs.org/dockerode/-/dockerode-2.4.3.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "gitHead": "7782d033f044acba2683e48e4068033095d21ba2",
    "homepage": "https://github.com/apocas/dockerode#readme",
    "keywords": [
        "docker",
        "docker.io"
    ],
    "license": "Apache-2.0",
    "main": "./lib/docker",
    "maintainers": [
        {
            "name": "apocas"
        }
    ],
    "name": "dockerode",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/apocas/dockerode.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha -R spec"
    },
    "version": "2.4.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

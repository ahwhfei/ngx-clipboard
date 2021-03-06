﻿[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=flat-square)](http://commitizen.github.io/cz-cli/)
[![travis build](https://img.shields.io/travis/maxisam/ngx-clipboard.svg?style=flat-square)](https://travis-ci.org/maxisam/ngx-clipboard)
[![npm](https://img.shields.io/npm/dt/ngx-clipboard.svg?style=flat-square)](https://www.npmjs.com/package/ngx-clipboard)
[![GitHub release](https://img.shields.io/github/release/maxisam/ngx-clipboard.svg?style=flat-square)](https://github.com/maxisam/ngx-clipboard/releases)
[![npm](https://img.shields.io/npm/l/ngx-clipboard.svg?style=flat-square)]()

# ngx-clipboard , F.K.A [angular2-clipboard](https://www.npmjs.com/package/angular2-clipboard)

Angular directive for [clipboard.js](http://zenorocha.github.io/clipboard.js/) by [@zenorocha](https://twitter.com/zenorocha)

It works with angular version 2.0.0 and up

To make more sense with the future versioning scheme of Angular, the directive selector is now rename to **ngxClipboard**

## Dependencies

+ Angular ~2.0.0
+ [clipboard.js](https://clipboardjs.com/)

## Install

You can get it on npm.

```
npm install ngx-clipboard --save
```

## Build project

```
1. npm i

2. npm run build
```

## Example

[plunker](http://embed.plnkr.co/PD4Ap8/)


## Contributing 

1. Your commits conform to the conventions established [here](https://github.com/conventional-changelog/conventional-changelog-angular/blob/master/convention.md)
2. This project used [commitizen](https://github.com/commitizen/cz-cli) and [semantic-release](https://github.com/semantic-release/semantic-release) to handle npm version from CI
    + run git add first to add your changes to staging 
    + use `npm run commit` to commit, and CI will do the rest.
    + if changes contain breaking change, use `BREAKING CHANGE` keyword in the comment to trigger major release
    + before push to git and trigger CI, you can dry run `npm run semantic-release` locally to make sure the version number is push as expected.

## Troubleshooting

1. If you use webpack, check `/demo/webpack`. Try to use the same version of webpack that demo used, if you run into any error.

2. The latest version (3.0.0+) works with AoT, please check [/demo/angular2-aot-webpack](https://github.com/maxisam/ngx-clipboard/tree/master/demo/angular2-aot-webpack) to see how to make it work.


Kudos to 

[Thierry Templier](http://stackoverflow.com/a/36330518/667767) This project is base on his answer on StackOverflow

[blacksonic](https://github.com/blacksonic/ngx-aot-webpack) AoT's demo is based on his project

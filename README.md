# TeaTime Code Fork of CKEditor 4 - Smart WYSIWYG HTML editor (with extra modifications) 

[![npm version](https://badge.fury.io/js/ckeditor4.svg)](https://www.npmjs.com/package/@teatime-code/ckeditor4)
[![GitHub tag](https://img.shields.io/github/tag/ckeditor/ckeditor4.svg)](https://github.com/teatime-code/ckeditor4)

<!--
[![Build Status](https://travis-ci.org/ckeditor/ckeditor4.svg?branch=major)](https://travis-ci.org/ckeditor/ckeditor4)
[![Dependencies](https://img.shields.io/david/ckeditor/ckeditor4.svg)](https://david-dm.org/ckeditor/ckeditor4)
[![Dev dependencies](https://img.shields.io/david/dev/ckeditor/ckeditor4.svg)](https://david-dm.org/ckeditor/ckeditor4?type=dev)

[![Join newsletter](https://img.shields.io/badge/join-newsletter-00cc99.svg)](http://eepurl.com/c3zRPr)
[![Follow Twitter](https://img.shields.io/badge/follow-twitter-00cc99.svg)](https://twitter.com/ckeditor)
-->

This modiifcation uses the best out of CKEditor4, and add a customizing interface who wanted to extend the editor in a more modern way(especially, intergrated with React, and custom elements for dynamic contents).

------

CKEditor4 is A highly configurable WYSIWYG HTML editor with hundreds of features, from creating rich text content with captioned images, videos, tables, media embeds, emoji or mentions to pasting from Word and Google Docs and drag&drop image upload.

Supports a broad range of browsers, including legacy ones.

![CKEditor 4 screenshot](https://c.cksource.com/a/1/img/npm/ckeditor4.png)

## Getting started

### Using [npm package](https://www.npmjs.com/package/ckeditor)

```bash
$ yarn add @teatime-code/ckeditor4-dev
```

### Integrating with Angular and React

Refer to official usage guides for the [`ckeditor4-angular`](https://www.npmjs.com/package/ckeditor4-angular#usage) and [`ckeditor4-react`](https://www.npmjs.com/package/ckeditor4-react#usage) packages.


---

## Working with the `ckeditor4` repostiory

### Code installation

There is no special installation procedure to install the development code.
Simply clone it to any local directory and you are set.

### Brances from original CKEditor4 repositories

This repository contains the following branches:

  - **`master`** &ndash; Development of the upcoming minor release.
  - **`major`** &ndash; Development of the upcoming major release.
  - **`stable`** &ndash; Latest stable release tag point (non-beta).
  - **`latest`** &ndash; Latest release tag point (including betas).
  - **`release/A.B.x`** (e.g. `4.0.x`, `4.1.x`) &ndash; Release freeze, tests and tagging. Hotfixing.

Note that both `master` and `major` are under heavy development. Their code did not pass the release testing phase, though, so it may be unstable.

Additionally, all releases have their respective tags in the following form: `4.4.0`, `4.4.1`, etc.

### Samples

The `samples/` folder contains some examples that can be used to test your installation. Visit [CKEditor 4 Examples](https://ckeditor.com/docs/ckeditor4/latest/examples/index.html) for plenty of samples showcasing numerous editor features, with source code readily available to view, copy and use in your own solution.

### Code structure

The development code contains the following main elements:

  - Main coding folders:
    - `core/` &ndash; The core API of CKEditor 4. Alone, it does nothing, but it provides the entire JavaScript API that makes the magic happen.
    - `plugins/` &ndash; Contains most of the plugins maintained by the CKEditor 4 core team.
    - `skin/` &ndash; Contains the official default skin of CKEditor 4.
    - `dev/` &ndash; Contains some developer tools.
    - `tests/` &ndash; Contains the CKEditor 4 tests suite.

### Building a release

A release-optimized version of the development code can be easily created locally. The `dev/builder/build.sh` script can be used for that purpose:

	> ./dev/builder/build.sh

A "release-ready" working copy of your development code will be built in the new `dev/builder/release/` folder. An Internet connection is necessary to run the builder, for the first time at least.

### Testing environment

Read more on how to set up the environment and execute tests in the [CKEditor 4 Testing Environment](https://ckeditor.com/docs/ckeditor4/latest/guide/dev_tests.html) guide.

### Reporting issues

Use the [CKEditor 4 GitHub issue page](https://github.com/ckeditor/ckeditor4/issues) to report bugs and feature requests.

### License

Copyright (c) 2003-2020, CKSource - Frederico Knabben. All rights reserved.

For licensing, see LICENSE.md or [https://ckeditor.com/legal/ckeditor-oss-license](https://ckeditor.com/legal/ckeditor-oss-license)

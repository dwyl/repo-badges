Repository Badges
===========

## Why?

At [***dwyl***](https://github.com/dwyl) we include "*badges*" in our code repositories to ***signal*** to *fellow
developers* that we set ourselves a ***high standard***<sup>1</sup> for the code we write.

## What?

We use the following badges:

+ **Continuous Integration** - [![Build Status](https://travis-ci.org/dwyl/esta.png?branch=master)](https://travis-ci.org/dwyl/esta) indicates that the project's **tests** all **pass** as expected. We use [**Travic-CI**](https://github.com/docdis/learn-travis) for this see: https://github.com/docdis/learn-travis

+ **Test/Code Coverage** - [![Test Coverage](https://codeclimate.com/github/dwyl/esta/badges/coverage.svg)](https://codeclimate.com/github/dwyl/esta)

+ **CodeClimate**: https://github.com/docdis/learn-codeclimate

+ **Dependencies** - [![Dependency Status](https://david-dm.org/dwyl/esta.svg)](https://david-dm.org/dwyl/esta) - knowing your module/project has (and works with) the latest versions of all its dependencies is a good way to signal that any bug-fixes/performance improvements/security patches etc in the *component* modules/libraries are considered in by the authors.
We use https://david-dm.org/ to track our dependencies. david-dm is lovingly maintained by [**@alanshaw**](https://github.com/alanshaw) of [**TableFlip**](http://tableflip.io/) (a fellow ***dwyl***er!) and is a *great* resource for the node.js community!

+ **devDependencies** - [![devDependency Status](https://david-dm.org/dwyl/esta/dev-status.svg)](https://david-dm.org/dwyl/esta#info=devDependencies) your devDependencies are those modules used in testing/building your project. These do not *need* to be the *latest* versions because you will typically not install your devDependencies on your production server (so there aren't security vulnerabilities in *production* of having out-of-date devDependencies...) however, ***we encourage*** use of ***latest*** devDependencies because it means better stability in the build (fewer bugs in our tools!) and it makes it *easier* for ***new people joining the project*** because when they `npm install` they know everything is the *latest* version.

+ **NPM Module Version** - [![NPM Version](https://badge.fury.io/js/esta.svg?style=flat)](https://npmjs.org/package/esta) this is a simple convenience to signal to fellow developers which version is the latest for our module. (*save them having to look at the package.json*) if you want to include one in your readme, go to: http://badge.fury.io/for/js and type in your npm package name.

+ Travis-CI: https://github.com/docdis/learn-travis

+ Dependencies: https://david-dm.org/
+ NPM Module Version: http://badge.fury.io/for/js/listdirs

We have included a few **SVG**s &amp; ***High-res*** **PNG**s of Code Badges (Build Passing, Code Climate, Coverage, etc) in the folders.

I needed high-res versions of the "standard" coding badges for a presentation.

Hope they are useful to someone else.

Help spread the **Code Quality** ***Love***! :heart:  
Please :star: this repo and share it with others.

If you need to addapt any of the images use: http://shields.io

## Contributing [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/fork)

```code
## Contributing [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)

```

## Why? [![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](http://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action)

```code
## Why? [![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](http://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action)
```

## Gitter

[![Join the chat at https://gitter.im/docdis/javascript-best-practice](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/docdis/?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

```md
[![Join the chat at https://gitter.im/[ORG-or-USERNAME]/[REPO-NAME]](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/docdis/?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
```

## The Rest ...

Best place to get these is from their respective websites...

[![Build Status](https://travis-ci.org/dwyl/esta.png?branch=master)](https://travis-ci.org/dwyl/esta)
[![Test Coverage](https://codeclimate.com/github/dwyl/esta/badges/coverage.svg)](https://codeclimate.com/github/dwyl/esta)
[![Code Climate](https://codeclimate.com/github/dwyl/esta/badges/gpa.svg)](https://codeclimate.com/github/dwyl/esta)
[![Dependency Status](https://david-dm.org/dwyl/esta.svg)](https://david-dm.org/dwyl/esta)
[![Node version](https://img.shields.io/node/v/esta.svg?style=flat)](http://nodejs.org/download/)
[![NPM Version](https://badge.fury.io/js/esta.svg?style=flat)](https://npmjs.org/package/esta)


## Node.js Version your Module Supports:

```md
[![Node version](https://img.shields.io/node/v/[NPM-MODULE-NAME].svg?style=flat)](http://nodejs.org/download/)
```

<sup>1</sup>Other repositories that do *not* have these badges are not *necessarily* "***worse***" or have "***low standards***", they simply are **not** making them ***explicit*** .

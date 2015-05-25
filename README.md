Code Repository Badges ![build passing](https://raw.githubusercontent.com/dwyl/repo-badges/master/highresPNGs/build-passing.png)
===========

## Why? [![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](http://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action)

As people who are ***passionate*** about writing ***great code*** we **display** "***badges***" in our code repositories to ***signal*** to *fellow
developers* that we set ourselves ***high standards***<sup>1</sup> for the code we write, think of them as the software-equivalent of the brand on your jeans or other ***reliable product***.

Help spread the **Code Quality** ***Love***! :heart:  
Please :star: this repo and share it with others by ***re-tweeting***:

[![repo-bages-please-retweet](http://i.imgur.com/OuqTKlV.png)](https://twitter.com/nelsonic/status/602379561507135488)


## What?

We use the following badges (*listed in order of importance*):

+ **Continuous Integration** - [![Build Status](https://travis-ci.org/dwyl/esta.svg?branch=master)](https://travis-ci.org/dwyl/esta) - "*build passing*" indicates that the project's **tests** all **pass** as expected. If you see that the build for a project is "*broken*" it means the software does *not* work as advertised! This is a clear sign that you should not be using it (*until it gets fixed!*) ... check the repo's issues to see if it's a known problem, if not, *report it*!  
We use [***Travic-CI***](https://github.com/docdis/learn-travis) for our CI.  We wrote a little how-to/tutorial to help you (and your team) get started: [https://github.com/docdis/**learn-travis**](https://github.com/docdis/learn-travis)

+ **Test/Code Coverage** - [![Test Coverage](https://codeclimate.com/github/dwyl/esta/badges/coverage.svg)](https://codeclimate.com/github/dwyl/esta) - coverage is the measure of how much of the code in a project is tested. Anything ***below 100% coverage*** means the module/library has ***potential bugs*** which are unknown to the authors/users. We avoid using modules with less than 100% coverage and encourage others to *question* why the authors did not put in the time to test their code... ***ALL our code is tested***. *we cannot guarantee every line is "bug-free", (and always welcome people reporting any issues!) however we are meticulous about testing our work and always add regression/edge test cases where bugs are discovered!*

+ **CodeClimate** - [![Code Climate](https://codeclimate.com/github/dwyl/esta/badges/gpa.svg)](https://codeclimate.com/github/dwyl/esta) - is the code quality score for the project measured on a number of factors including **Complexity/Simplicity, Readability, Maintainability, Repetition and Line-count-per-file** . The ***max***imum ***score*** is **4.0** and we *obviously* strive to achieve this level in all our work.   [https://github.com/docdis/**learn-codeclimate**](https://github.com/docdis/learn-codeclimate)

+ **BitHound** - [![bitHound Score](https://img.shields.io/badge/bitHound-100-brightgreen.svg)](https://www.bithound.io/github/dwyl/ordem) - similar to *CodeClimate* but has *way* more detail! and charts progress/regression on a graph which is great for monitoring code quality in teams! see: https://www.bithound.io/features

+ **Dependencies** - [![Dependency Status](https://david-dm.org/dwyl/esta.svg)](https://david-dm.org/dwyl/esta) - knowing your module/project has (and works with) the latest versions of all its dependencies is a good way to signal that any bug-fixes/performance improvements/security patches etc in the *component* modules/libraries are considered in by the authors.
We use https://david-dm.org/ to track our dependencies. david-dm is lovingly maintained by [**@alanshaw**](https://github.com/alanshaw) of [**TableFlip**](http://tableflip.io/) (a fellow ***dwyl***er!) and is a *great* resource for the node.js community!

+ **devDependencies** - [![devDependency Status](https://david-dm.org/dwyl/esta/dev-status.svg)](https://david-dm.org/dwyl/esta#info=devDependencies) - your devDependencies are the modules used in testing/building your project. These do not *need* to be the *latest* versions because you will typically not install your devDependencies on your production server (so there aren't security vulnerabilities in *production* of having out-of-date devDependencies...) however, ***we encourage*** use of ***latest*** devDependencies because it means better stability in the build (fewer bugs in our tools!) and it makes it *easier* for ***new people joining the project*** because when they `npm install` they know everything is the *latest* version.

+ **NPM Module Version** - [![NPM Version](https://badge.fury.io/js/esta.svg?style=flat)](https://npmjs.org/package/esta) this is a simple *convenience* to signal to fellow developers which version is the latest for your module. (*save them having to look at the package.json*) if you want to include one in your readme, go to: http://badge.fury.io/for/js and type in your npm package name.


## How?

### Build Passing [![Build Status](https://travis-ci.org/dwyl/esta.svg?branch=master)](https://travis-ci.org/)

```md
[![Build Status](https://travis-ci.org/{ORG-or-USERNAME}/{REPO-NAME}.png?branch=master)](https://travis-ci.org/{ORG-or-USERNAME}/{REPO-NAME})
```

You'll need to setup your project on [**Travis-CI**](https://github.com/docdis/learn-travis) and write **unit tests** (*preferably TDD!*) for this to work ... if you're stuck ask us how!


### CodeCliamte

Setup your repository by adding it on code climate then copy the badge markdown from them!

For more detailed instructions see: https://github.com/docdis/learn-codeclimate



### Why? [![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](http://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action)

```code
## Why? [![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](http://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action)
```

### Node.js Version your Project/Module Supports:

```md
[![Node version](https://img.shields.io/node/v/[NPM-MODULE-NAME].svg?style=flat)](http://nodejs.org/download/)
```


### Contributing [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)

```code
## Contributing [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)

```

### Gitter (*Chat for Developers*!)

[![Join the chat at https://gitter.im/docdis/javascript-best-practice](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/docdis/?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
```md
[![Join the chat at https://gitter.im/{ORG-or-USERNAME}/{REPO-NAME}](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/docdis/?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
```



### Others

If you need to adapt any of the images or *create your own*: http://shields.io


## *Extra* High-resolution

We needed ***High-resolution versions*** of the coding badges for a presentation about testing so we made **PNG**s from the SVGs ...

These are in the folders in this repo in case they are useful to someone else.


<sup>1</sup>Other repositories that do *not* have these badges are not *necessarily* "***worse***" or have "***low standards***", they simply are **not** making them ***explicit*** .

<div align="center">

# Code Repository Badges 
![build passing](https://raw.githubusercontent.com/dwyl/repo-badges/master/highresPNGs/build-passing.png)

</div>

## Why? [![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](https://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action)

As people who are ***passionate*** about writing ***great code*** we **display** "***badges***" in our code repositories to ***signal*** to *fellow
developers* that we set ourselves ***high standards***<sup>1</sup> for the code we write, think of them as the software-equivalent of the brand on your jeans or other ***reliable product***.


## What?

We use the following badges (*listed in order of importance*):

+ **Documentation** - [![Inline docs](https://inch-ci.org/github/dwyl/hapi-auth-jwt2.svg?branch=master)](https://inch-ci.org/github/dwyl/hapi-auth-jwt2) _Many_ developers do not _prioritize documentation_ in their (_technical_) projects, 
instead people focus on solving the _~~problem~~_ _challenge_ e.g. by writing some code,
and `if` it works, they add a `TODO` to "improve the docs" ...
It may _initially_ be _counter-intuitive_ to think of Documentation as being
the _highest priority_ or _first_ activity in a technical
project but there are _several_ reasons why it is:
  + Clearly setting out _your own_ understanding of "the challenge"
  and then formulating a **Question** to be answered is the _basis_ for
  [`"The Scientific Method"`](https://en.wikipedia.org/wiki/Scientific_method).
  Without it you are like a blind-folded camel in the desert;
  unlikely to go _straight_ to the oasis!
  + Describing your "success factors" or "acceptance criteria" _before_ you start so you _know_ when you've achieved your goal!
  + Communicating with **current collaborators** what problem you are/were trying to solve.
  + Making it _immediately_ clear to everyone if you have _succeeded_ in solving the challenge
  + Saves time in the _short-run_ because you are _immediately_ focused on the challenge
  and don't _waste_ time on distractions.

+ ***Security*** - [![Known Vulnerabilities](https://snyk.io/test/github/dwyl/hapi-auth-jwt2/badge.svg?targetFile=package.json)](https://snyk.io/test/github/dwyl/hapi-auth-jwt2?targetFile=package.json) -
Snyk Dependency Security Vulnerability Checking for your project:
https://snyk.io/
is a ***free*** service provided by the lovely people at Snyk
that checks if any of your `dependencies` have a security vulnerability.
This _badge_ is a great way to ***reassure
people using your app/site that security is being checked***.
> Top tip: Guy Podjarny [@guypod](https://github.com/guypod) the founder of Snyk
hosts "***The Secure Developer***" Podcast. <br />
It's a "***must***" for _all_ devs!
Subscribe if you aren't already:
https://www.heavybit.com/library/podcasts/the-secure-developer

+ **Continuous Integration** - [![Build Status](https://travis-ci.org/dwyl/esta.svg?branch=master)](https://travis-ci.org/dwyl/esta) - "*build passing*" indicates that the project's **tests** all **pass** as expected. If you see that the build for a project is "*broken*" it means the software does *not* work as advertised! This is a clear sign that you should not be using it (*until it gets fixed!*) ... check the repo's issues to see if it's a known problem, if not, *report it*!  
We use [***Travis CI***](https://travis-ci.org/) for our CI.  We wrote a little how-to/tutorial to help you (and your team) get started: [https://github.com/dwyl/**learn-travis**](https://github.com/dwyl/learn-travis)

+ **Test/Code Coverage** - [![codecov.io Code Coverage](https://img.shields.io/codecov/c/github/dwyl/hapi-auth-jwt2.svg?maxAge=2592000)](https://codecov.io/github/dwyl/hapi-auth-jwt2?branch=master) - coverage is the measure of how much of the code in a project is tested. Anything ***below 100% coverage*** means the module/library has ***potential bugs*** which are unknown to the authors/users. We avoid using modules with less than 100% coverage and encourage others to *question* why the authors did not put in the time to test their code... ***ALL our code is tested***. *we cannot guarantee every line is "bug-free", (and always welcome people reporting any issues!) however we are meticulous about testing our work and always add regression/edge test cases where bugs are discovered!*

+ **CodeClimate** - [![Code Climate](https://codeclimate.com/github/dwyl/esta/badges/gpa.svg)](https://codeclimate.com/github/dwyl/esta) - is the code quality score for a project measured on a number of factors including **Complexity/Simplicity, Readability, Maintainability, Repetition and Line-count-per-file** . The <b><i>max</b></i>imum ***score*** is **4.0** and we *obviously* strive to achieve this level in all our work.   [https://github.com/dwyl/**learn-codeclimate**](https://github.com/dwyl/learn-codeclimate)

+ **JavaScript the** _**`goodparts`**_ (_code style/linting_) - [![JavaScript Style Guide: Good Parts](https://img.shields.io/badge/code%20style-goodparts-brightgreen.svg?style=flat)](https://github.com/dwyl/goodparts "JavaScript The Good Parts") ... "Third Party" Code analysis services like CodeClimate (_above_) are _really_ useful to have an "_objective_" (_impartial_) measure for the complexity/maintainability of your codebase, however you may want to take code-style/readability to the _next_ level by using a specific style across all your projects ...
Having _harmony_ in your codebase is _really_ useful/practical because it reduces the "_thinking time_". People working on the project need in order to _understand_ (_and thus maintain/extend_) existing code. There are a _few_ JavaScript "style guides" which help you & your team write consistent JS.
We like [`goodparts`](https://github.com/dwyl/goodparts) because of [_these reasons_](https://github.com/dwyl/goodparts#why),
_however_ we _encourage_ you to make up your own mind as to which style to use (_preferably based on sound reasoning not fashion_...)

+ **Dependencies** - [![Dependency Status](https://david-dm.org/dwyl/esta.svg)](https://david-dm.org/dwyl/esta) - knowing your module/project has (and works with) the latest versions of all its dependencies is a good way to signal that any bug-fixes/performance improvements/security patches etc in the *component* modules/libraries are considered in by the authors.
We use https://david-dm.org/ to track our dependencies. david-dm is lovingly maintained by [**@alanshaw**](https://github.com/alanshaw) of [**TableFlip**](https://tableflip.io/) (a fellow <b><i>dwyl</b></i>er!) and is a *great* resource for the node.js community!

+ **devDependencies** - [![devDependencies Status](https://david-dm.org/dwyl/hapi-auth-jwt2/dev-status.svg)](https://david-dm.org/dwyl/hapi-auth-jwt2?type=dev) - your devDependencies are the modules used in testing/building your project. These do not *need* to be the *latest* versions because you will typically not install your devDependencies on your production server (so there aren't security vulnerabilities in *production* of having out-of-date devDependencies...) however, ***we encourage*** use of ***latest*** devDependencies because it means better stability in the build (fewer bugs in our tools!) and it makes it *easier* for ***new people joining the project*** because when they `npm install` they know everything is the *latest* version.

+ **NPM Module _Version_** - [![NPM Version](https://badge.fury.io/js/esta.svg?style=flat)](https://npmjs.org/package/esta) this is a simple *convenience* to signal to fellow developers which version is the latest for your module. (*saves them having to look at the package.json*) If you want to include one in your readme, go to: https://badge.fury.io/for/js and type in your npm package name.

+ **NPM Module _Download Stats_** - [![NPM Download Stats](https://nodei.co/npm/decache.png?downloads=true)](https://www.npmjs.com/package/decache) - while this can be seen as a "_vanity metric_" it _can_ also be _useful_ to know if your project is actually being _used_ by people in the community to know if you need keep supporting it.

## How?

<!--
## Documentation ![Inch-CI](https://inch-ci.org/assets/badge-example-b71f9e833318f66f64b3f23877113051.svg)

While including a badge from "Inch-CI" in _no way_ "_guarantees_" that your project
is "_comprehensively_" documented it serves to remind you (_and your team_)
that documentation (i.e. _communication_) is a _priority_ and _signals_
to others if you have the solution to _their_ "challenge".

> Visit: https://inch-ci.org/learn_more and paste your GitHub
username (_or organisation name_) and _repository_ name into the form then click `Evaluate`.

Then you can copy the badge directly from the resulting page. e.g:

```md
[![Inline docs](https://inch-ci.org/github/{ORG-or-USERNAME}/{REPO-NAME}.svg?branch=master)](https://inch-ci.org/github/{ORG-or-USERNAME}/{REPO-NAME})
```
-->

## Build Passing [![Build Status](https://travis-ci.org/dwyl/esta.svg?branch=master)](https://travis-ci.org/)

### GitHub Actions/Workflows

If you are using GitHub Actions/Workflows 
https://github.com/features/actions
to run your Continuous Integration (CI),
then you can include a badge in your project's `README.md`:
https://docs.github.com/en/actions/monitoring-and-troubleshooting-workflows/adding-a-workflow-status-badge

Regular badge template:
```
![example workflow](https://github.com/<OWNER>/<REPOSITORY>/actions/workflows/<WORKFLOW_FILE>/badge.svg)
```
e.g:
```
![GitHub CI](https://github.com/dwyl/auth_plug/actions/workflows/ci.yml/badge.svg)
```

![GitHub CI](https://github.com/dwyl/auth_plug/actions/workflows/ci.yml/badge.svg)

Custom badge via Shields.io: https://shields.io/category/build
![image](https://user-images.githubusercontent.com/194400/137601498-5a5496dc-f610-4931-8fa6-45e9ef9cd051.png)

Example:
```
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/dwyl/auth_plug/Elixir%20CI?label=build&style=flat-square)
```
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/dwyl/auth_plug/Elixir%20CI?label=build&style=flat-square)

<br />

### Travis-CI

You'll need to setup your project on [**Travis-CI**](https://github.com/dwyl/learn-travis) and write **unit tests** (*preferably TDD!*) for this to work ... if you're stuck ask us how!


```md
[![Build Status](https://travis-ci.org/{ORG-or-USERNAME}/{REPO-NAME}.png?branch=master)](https://travis-ci.org/{ORG-or-USERNAME}/{REPO-NAME})
```

### CodeClimate

Setup your repository by adding it on code climate then copy the badge markdown from them!

For more detailed instructions see: https://github.com/dwyl/learn-codeclimate

### Coverage

The new kid on the block for Test Coverage is "CodeCov": https://codecov.io/#features  
We *love* their features *especially the fact that they check*
***coverage for pull requests***! see: https://github.com/dwyl/learn-istanbul#tracking-coverage-as-a-service  

To setup **codecov** simply add the following lines to your
`.travis.yml` file:

```sh
before_install:
  - pip install --user codecov
after_success:
  - codecov --file coverage/lcov.info --disable search
```

And remember to output a [coverage report](https://github.com/nelsonic/hits/blob/7867e0d1abe9d3a5246e39ad53abdbde35ded01a/package.json#L11) in your tests using istanbul,
by adding it to your `test` script in your [package.json](https://github.com/nelsonic/hits/blob/7867e0d1abe9d3a5246e39ad53abdbde35ded01a/package.json#L11)
so that travis can send the coverage report to codecov
e.g:
```sh
"scripts": {
  "test": "./node_modules/.bin/istanbul cover ./node_modules/tape/bin/tape ./test/*.js"
}
```
If you are new to test coverage using istanbul check out:
[**learn-istanbul**](https://github.com/dwyl/learn-istanbul)

Working example:
[hits/**.travis.yml**](https://github.com/nelsonic/hits/blob/master/.travis.yml)

> Note: you can still use CodeClimate for Coverage if you prefer,<br />
we're *excited* that there is more *choice* in the JS testing space!

### `goodparts` JavaScript Code Style [![JavaScript Style Guide: Good Parts](https://img.shields.io/badge/code%20style-goodparts-brightgreen.svg?style=flat)](https://github.com/dwyl/goodparts "JavaScript The Good Parts")

Once you have installed `goodparts` and used it to `lint` your code,
see: https://github.com/dwyl/goodparts#how you can include a _badge_ in your repo to inform others of your choice of code style.

```markdown
[![JavaScript Style Guide: Good Parts](https://img.shields.io/badge/code%20style-goodparts-brightgreen.svg?style=flat)](https://github.com/dwyl/goodparts "JavaScript The Good Parts")
```
> See: https://github.com/dwyl/goodparts


### Why? [![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](https://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action)

```code
## Why? [![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](https://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action)
```

### Node.js Version your Project/Module Supports: [![NPM version](https://badge.fury.io/js/esta.svg)](https://badge.fury.io/js/esta)

```md
[![Node version](https://img.shields.io/node/v/[NPM-MODULE-NAME].svg?style=flat)](https://nodejs.org/download/)
```

### NPM Download Statistics

To show download stats for your NPM package, use https://nodei.co/ e.g:

[![NPM Download Stats](https://nodei.co/npm/hapi-auth-jwt2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hapi-auth-jwt2)

If you want the image to be _clickable_ use the following Markdown:

```markdown
[![https://nodei.co/npm/YOUR-MODULE-NAME.png?downloads=true&downloadRank=true&stars=true](https://nodei.co/npm/YOUR-MODULE-NAME.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/YOUR-MODULE-NAME)
```

### Contributing [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)

If you want to _encourage_ people to contribute to your project, by reminding them that you _welcome_ their input use this badge!

```code
## Contributing [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)

```

### Gitter (*Chat for Developers*!)

[![Join the chat at https://gitter.im/dwyl/chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dwyl/chat?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
```md
[![Join the chat at https://gitter.im/{ORG-or-USERNAME}/{REPO-NAME}](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dwyl/?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
```
#### _dwyl_ chat button:

If you are working on a project in the `dwyl` organisation and want
to include the button to let people join our _public_ chat channel,
copy paste this markdown _snippet_ into the `README.md`
of the project you are working on:

```md
[![Join the chat at https://gitter.im/dwyl/chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dwyl/chat?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
```

### (GitHub Repo) Hit Counter [![HitCount](https://hits.dwyl.com/dwyl/repo-badges.svg)](https://hits.dwyl.com/dwyl/repo-badges)

Ever wanted to know how many people have viewed your GitHub Repo?<br />
We did ...
So we wrote a tiny script that counts views! :open_mouth:

Visit: https://hits.dwyl.com to get your "Hit Count" badge.

Template:
```md
[![HitCount](https://hits.dwyl.com/{username}/{project-name}.svg)](https://hits.dwyl.com/{username}/{project-name})
```
Example:
```
[![HitCount](https://hits.dwyl.com/dwyl/start-here.svg)](https://hits.dwyl.com/dwyl/start-here)
```


> _Yes, we **know** that for some people,
"hits" = "**How Idiots Track Success**" ...
but, in the absence of better analytics,
page views are a good metric to be aware of!_ :chart_with_upwards_trend:


### Snyk _Proactive_ Security Vulnerability Detection

See: 
[snyk-security-scanning.md](https://github.com/dwyl/repo-badges/blob/main/snyk-security-scanning.md)

# Thank _You_!

Help spread the **Code Quality** ***Love***! :heart:<br />
Please :star: this repo and share it with others by ***re-tweeting***:

[![repo-bages-please-retweet](https://i.imgur.com/OuqTKlV.png)](https://twitter.com/nelsonic/status/602379561507135488)



<br />

### Others

If you need to adapt any of the images or *create your own*: https://shields.io

## *Extra* High-resolution

We needed ***High-resolution versions*** of the coding badges for a presentation about testing so we made **PNG**s from the SVGs ...

These are in the folders in this repo in case they are useful to someone else.


<sup>1</sup>Other repositories that do *not* have these badges are not *necessarily* "***worse***" or have "***low standards***", they simply are **not** making them ***explicit*** .

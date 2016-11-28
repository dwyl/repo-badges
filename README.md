Code Repository Badges ![build passing](https://raw.githubusercontent.com/dwyl/repo-badges/master/highresPNGs/build-passing.png)
===========

## Why? [![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](http://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action)

As people who are ***passionate*** about writing ***great code*** we **display** "***badges***" in our code repositories to ***signal*** to *fellow
developers* that we set ourselves ***high standards***<sup>1</sup> for the code we write, think of them as the software-equivalent of the brand on your jeans or other ***reliable product***.

Help spread the **Code Quality** ***Love***! :heart:<br />
Please :star: this repo and share it with others by ***re-tweeting***:

[![repo-bages-please-retweet](http://i.imgur.com/OuqTKlV.png)](https://twitter.com/nelsonic/status/602379561507135488)


## What?

We use the following badges (*listed in order of importance*):

+ **Documentation** - [![Inline docs](http://inch-ci.org/github/dwyl/hapi-auth-jwt2.svg?branch=master)](http://inch-ci.org/github/dwyl/hapi-auth-jwt2) _most_ people don't _think_ of _documentation_ as the "_priority_" for their (_technical_) project,
instead people focus on solving the _~~problem~~_ _challenge_ e.g. by writing some code,
and `if` it works they add a `TODO` to "improve the docs" ...
It may _initially_ be _counter-intuitive_ to think of Documentation as being
the _highest priority_ or _first_ activity in a technical
project but there are _several_ reasons why it is:
  + Clearly setting out _your own_ understanding of "the challenge"
  and then formulating a **Question** to be answered is the _basis_ for
  [`"The Scientific Method"`](https://en.wikipedia.org/wiki/Scientific_method)
  without it you are like a blind-folded camel in the desert;
  unlikely you'll go _stright_ to the oasis!
  + Describing your "success factors" or "acceptance criteria" _before_ you start so you _know_ when you've achieved your goal!
  team (_and complete strangers_)
  + Communicating with **current collaborators** what problem you are/were trying to solve.
  + Making it _imediately_ clear to everyone if you have _succeded_ in solving the challenge
  _potential_ new collaborators
  + Solves time in the _short-run_ because you are _immediately_ focussed on the challenge
  and don't _waste_ time on distractions.

+ ***Security*** - [![NSP Status](https://nodesecurity.io/orgs/dwyl/projects/1047e39b-0d4a-45ff-af65-c04afc41fc20/badge)](https://nodesecurity.io/orgs/dwyl/projects/1047e39b-0d4a-45ff-af65-c04afc41fc20) -
NodeSecurity "Live" Checking for your project: https://nodesecurity.io/services
is a ***free*** service provided by the lovely people at [`Node Security Project`](https://nodesecurity.io)
that checks if any of your `dependencies` have a security vulnerability.
This _badge_ is a great way to ***reassure
people using your app/site that security is being checked***.

+ **Continuous Integration** - [![Build Status](https://travis-ci.org/dwyl/esta.svg?branch=master)](https://travis-ci.org/dwyl/esta) - "*build passing*" indicates that the project's **tests** all **pass** as expected. If you see that the build for a project is "*broken*" it means the software does *not* work as advertised! This is a clear sign that you should not be using it (*until it gets fixed!*) ... check the repo's issues to see if it's a known problem, if not, *report it*!  
We use [***Travis CI***](https://github.com/dwyl/learn-travis) for our CI.  We wrote a little how-to/tutorial to help you (and your team) get started: [https://github.com/dwyl/**learn-travis**](https://github.com/dwyl/learn-travis)

+ **Test/Code Coverage** - [![codecov.io Code Coverage](https://img.shields.io/codecov/c/github/dwyl/hapi-auth-jwt2.svg?maxAge=2592000)](https://codecov.io/github/dwyl/hapi-auth-jwt2?branch=master) - coverage is the measure of how much of the code in a project is tested. Anything ***below 100% coverage*** means the module/library has ***potential bugs*** which are unknown to the authors/users. We avoid using modules with less than 100% coverage and encourage others to *question* why the authors did not put in the time to test their code... ***ALL our code is tested***. *we cannot guarantee every line is "bug-free", (and always welcome people reporting any issues!) however we are meticulous about testing our work and always add regression/edge test cases where bugs are discovered!*

+ **CodeClimate** - [![Code Climate](https://codeclimate.com/github/dwyl/esta/badges/gpa.svg)](https://codeclimate.com/github/dwyl/esta) - is the code quality score for the project measured on a number of factors including **Complexity/Simplicity, Readability, Maintainability, Repetition and Line-count-per-file** . The ***max***imum ***score*** is **4.0** and we *obviously* strive to achieve this level in all our work.   [https://github.com/dwyl/**learn-codeclimate**](https://github.com/dwyl/learn-codeclimate)

+ **BitHound** - [![bitHound Score](https://img.shields.io/badge/bitHound-100-brightgreen.svg)](https://www.bithound.io/github/dwyl/ordem) - similar to *CodeClimate* but has *way* more detail! and charts progress/regression on a graph which is great for monitoring code quality in teams! see: https://www.bithound.io/features

+ **JavaScript the** _**`goodparts`**_ (_code style/linting_) - [![JavaScript Style Guide: Good Parts](https://img.shields.io/badge/code%20style-goodparts-brightgreen.svg?style=flat)](https://github.com/dwyl/goodparts "JavaScript The Good Parts") ... "Third Party" Code analysis services like CodeClimate (_above_) are _really_ useful to have an "_objective_" (_impartial_) measure for the compexity/maintainability of your codebase, however you may want to take code-style/readability to the _next_ level by using a specific style across all your projects ...
Having _harmony_ in your codebase is _really_ useful/practical because it reduces the "_thinking time_" people working on the project need in order to _understand_ (_and thus maintain/extend_) existing code. There are a _few_ JavaScript "style guides" which help you & your team write consistent JS.
We like [`goodparts`](https://github.com/dwyl/goodparts) because of [_these reasons_](https://github.com/dwyl/goodparts#why),
_however_ we _encourage_ you to make up your own mind as to which style to use (_preferably based on sound reasoning not fashion_...)

+ **Dependencies** - [![Dependency Status](https://david-dm.org/dwyl/esta.svg)](https://david-dm.org/dwyl/esta) - knowing your module/project has (and works with) the latest versions of all its dependencies is a good way to signal that any bug-fixes/performance improvements/security patches etc in the *component* modules/libraries are considered in by the authors.
We use https://david-dm.org/ to track our dependencies. david-dm is lovingly maintained by [**@alanshaw**](https://github.com/alanshaw) of [**TableFlip**](http://tableflip.io/) (a fellow ***dwyl***er!) and is a *great* resource for the node.js community!

+ **devDependencies** - [![devDependencies Status](https://david-dm.org/dwyl/hapi-auth-jwt2/dev-status.svg)](https://david-dm.org/dwyl/hapi-auth-jwt2?type=dev) - your devDependencies are the modules used in testing/building your project. These do not *need* to be the *latest* versions because you will typically not install your devDependencies on your production server (so there aren't security vulnerabilities in *production* of having out-of-date devDependencies...) however, ***we encourage*** use of ***latest*** devDependencies because it means better stability in the build (fewer bugs in our tools!) and it makes it *easier* for ***new people joining the project*** because when they `npm install` they know everything is the *latest* version.

+ **NPM Module _Version_** - [![NPM Version](https://badge.fury.io/js/esta.svg?style=flat)](https://npmjs.org/package/esta) this is a simple *convenience* to signal to fellow developers which version is the latest for your module. (*save them having to look at the package.json*) if you want to include one in your readme, go to: http://badge.fury.io/for/js and type in your npm package name.

+ **NPM Module _Download Stats_** - [![NPM Download Stats](https://nodei.co/npm/decache.png?downloads=true)](https://www.npmjs.com/package/decache) - while this can be seen as a "_vanity metric_" it _can_ also be _useful_ to know if your project is actually being _used_ by people in the community to know if you need keep supporting it.

## How?

## Documentation ![Inch-CI](https://inch-ci.org/assets/badge-example-b71f9e833318f66f64b3f23877113051.svg)

While including a badge from "Inch-CI" in _no way_ "_guarantees_" that your project
is "_comprehensively_" documented it serves as a reminder you (_and your team_)
that documentation (i.e. _communication_) is a _priority_ and _signals_
to others if you have the solution to _their_ "challenge".

> Visit: http://inch-ci.org/learn_more and paste your GitHub
username (_or organisation name_) and _repository_ name into the form then click `Evaluate`.

Then you can copy the badge directly from the resulting page. e.g:

```md
[![Inline docs](http://inch-ci.org/github/{ORG-or-USERNAME}/{REPO-NAME}.svg?branch=master)](http://inch-ci.org/github/{ORG-or-USERNAME}/{REPO-NAME})
```

### Build Passing [![Build Status](https://travis-ci.org/dwyl/esta.svg?branch=master)](https://travis-ci.org/)

```md
[![Build Status](https://travis-ci.org/{ORG-or-USERNAME}/{REPO-NAME}.png?branch=master)](https://travis-ci.org/{ORG-or-USERNAME}/{REPO-NAME})
```

You'll need to setup your project on [**Travis-CI**](https://github.com/dwyl/learn-travis) and write **unit tests** (*preferably TDD!*) for this to work ... if you're stuck ask us how!

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
we're *excited* that there is more *choie* in the JS testing space!

### `goodparts` JavaScript Code Style [![JavaScript Style Guide: Good Parts](https://img.shields.io/badge/code%20style-goodparts-brightgreen.svg?style=flat)](https://github.com/dwyl/goodparts "JavaScript The Good Parts")

Once you have installed `goodparts` and used it to `lint` your code,
see: https://github.com/dwyl/goodparts#how you can include a _badge_ in your repo to inform others of your choice of code style.

```markdown
[![JavaScript Style Guide: Good Parts](https://img.shields.io/badge/code%20style-goodparts-brightgreen.svg?style=flat)](https://github.com/dwyl/goodparts "JavaScript The Good Parts")
```
> See: https://github.com/dwyl/goodparts


### Why? [![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](http://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action)

```code
## Why? [![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)](http://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action)
```

### Node.js Version your Project/Module Supports: [![NPM version](https://badge.fury.io/js/esta.svg)](http://badge.fury.io/js/esta)

```md
[![Node version](https://img.shields.io/node/v/[NPM-MODULE-NAME].svg?style=flat)](http://nodejs.org/download/)
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

### (GitHub Repo) Hit Counter [![HitCount](https://hitt.herokuapp.com/dwyl/repo-badges.svg)](https://github.com/dwyl/repo-badges)

Ever wanted to know how many people have viewed your GitHub Repo?<br />
We did ...
So we wrote a tiny script that counts views! :open_mouth:

```md
[![HitCount](https://hitt.herokuapp.com/{username||org}/{project-name}.svg)](https://github.com/{username||org}/{project-name})
```

> *Yes, we* ***know*** *that* "*hits*" = "***How Idiots Track Success***" ... *but, in the absence of better analytics,
its a fun metric to track* :wink:


### `Node Security Project` _Live_ Check

Enabling **Node Security Project** (***NSP**) "Live" checking
for your GitHub project requires a few steps, but should only take a couple of minutes ...

> Note: if you already have an NSP account skip to step 3, otherwise you will _first_ need to register, verify, etc.

#### 1. Sign Up for the Service

Sign up at: https://nodesecurity.io/signup  
(_you need to use a "real" email address ...
NSP will send you and alert if one of your projects has a security vulnerability so make sure it's  
an email address you check regularly or better one that you receive on your phone!_)

You will receive an email asking you to _verify_ the email address you used to sign up.
Click on "Verify Account":
![nsp-verify-email](https://cloud.githubusercontent.com/assets/194400/19645941/26bf0954-99ef-11e6-97fa-d67a99df3a46.png)


#### 2. Create your "Organisation" (_if you don't already have one_)

Once you have verified your account with `NSP` create an "organization"
so you can keep track of a _group_ of Node.js based projects.

> If you are using NSP for _personal_ projects just name your "org" the same as your GitHub username.

![nsp-add-org](https://cloud.githubusercontent.com/assets/194400/19646334/e690053e-99f0-11e6-8e49-ace07d5a3409.png)

In our case the name of our "org" is `dwyl`.
Once you've created the "org" click on it and so you can create your integration.
![nsp-click-on-your-org](https://cloud.githubusercontent.com/assets/194400/19646590/0236538c-99f2-11e6-80dc-a680d514f8fb.png)

#### 3. Create a GitHub Integration for your Project

Click on the button to create a GitHub Integration:

![nsp-add-integration-github](https://cloud.githubusercontent.com/assets/194400/19649798/069962f4-99ff-11e6-997f-f489b10505c9.png)

You will be re-directed to a GitHub "Auth" (Login) Page.

![nsp-github-auth](https://cloud.githubusercontent.com/assets/194400/19649913/7a22f79e-99ff-11e6-9cc2-f344a7fef84f.png)

Login and authorize Node Security Project to access your account.
Remember to grant authorization for the org where you project is (_if applicable_):

![nsp-authorise-for-dwyl-org](https://cloud.githubusercontent.com/assets/194400/19649969/a33ca7ec-99ff-11e6-8e34-5fe53c6bd69c.png)

Then click on the `Authorize Application` button at the bottom of the page:

![authorize-application](https://cloud.githubusercontent.com/assets/194400/19650123/110d9e16-9a00-11e6-8580-47a9fe6ae41d.png)

Once you do this you will be re-directed back to https://nodesecurity.io/orgs/dwyl/github/
where you will need to select the Org again `dwyl` in our case.

You will then be presented with a _list_ of projects.  
In our case we are enabling NSP Live checking
for our [`hapi-auth-jwt2`](https://github.com/dwyl/hapi-auth-jwt2) project:

![nsp-enable-for-project](https://cloud.githubusercontent.com/assets/194400/19650300/b20cd3f4-9a00-11e6-8eba-b187cd6e8d9a.png)

Once you click the `Submit` button you're done!
You should see the following message:

![nsp-free-integration](https://cloud.githubusercontent.com/assets/194400/19650406/208a793a-9a01-11e6-8c72-14e42f6368d4.png)

And if you scroll down you will see that the project checkbox is checked.

Going back to your "Projects" page you will see:

![nsp-projects-jwt2-passed](https://cloud.githubusercontent.com/assets/194400/19650556/a31ff4f6-9a01-11e6-9f5a-95e9f7a3f13a.png)

So you _know_ it's working!

Click on the project link and then on the badge:

![nsp-click-on-badge](https://cloud.githubusercontent.com/assets/194400/19650711/1f6dd38e-9a02-11e6-9610-0c54e15036f4.png)

Copy the `Markdown` code shown which includes the unique token for your project.
and paste it into the README.md of your project. e.g: [![NSP Status](https://nodesecurity.io/orgs/dwyl/projects/1047e39b-0d4a-45ff-af65-c04afc41fc20/badge)](https://nodesecurity.io/orgs/dwyl/projects/1047e39b-0d4a-45ff-af65-c04afc41fc20)

```markdown
[![NSP Status](https://nodesecurity.io/orgs/dwyl/projects/1047e39b-0d4a-45ff-af65-c04afc41fc20/badge)](https://nodesecurity.io/orgs/dwyl/projects/1047e39b-0d4a-45ff-af65-c04afc41fc20)
```

> Note: _just_ having a 3rd party service telling you there aren't any ***know vulnerabilities***
does ***not guarantee*** that your app is "_secure_"! You still need to write
good code that escapes all input and follows "best practice"!
But the `nsp` badge & service is a _useful_ early warning system.


<br />

### Others

If you need to adapt any of the images or *create your own*: http://shields.io

## *Extra* High-resolution

We needed ***High-resolution versions*** of the coding badges for a presentation about testing so we made **PNG**s from the SVGs ...

These are in the folders in this repo in case they are useful to someone else.


<sup>1</sup>Other repositories that do *not* have these badges are not *necessarily* "***worse***" or have "***low standards***", they simply are **not** making them ***explicit*** .

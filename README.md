# Giant

[![Build Status](https://travis-ci.org/surefire/giant.svg?branch=master)](https://travis-ci.org/surefire/giant)

Portfolio for [Giant].


## Prerequisites

* [Git]
* [Node.js][Node]
* [NPM]


## Installation

Clone the repository:

```sh
$ git clone git@github.com:surefire/giant.git
```

Setup the application:

```sh
$ npm install
```

## Usage

To start the application:

```sh
$ ./node_modules/.bin/gulp serve
```

## Responsive Images

Large:

```html
<img
  alt="Large portfolio item"
  class="portfolio-item-image"
  sizes="
    (min-width: 1200px) 460px,
    (min-width: 1024px) 480px,
    (min-width: 667px) 315px,
    375px"
  srcset="
    http://satyr.io/315x205/1?type=jpg&texture=cross&text=l 315w,
    http://satyr.io/375x246/1?type=jpg&texture=cross&text=l 375w,
    http://satyr.io/460x300/1?type=jpg&texture=cross&text=l 460w,
    http://satyr.io/480x313/1?type=jpg&texture=cross&text=l 480w,
    http://satyr.io/630x411/1?type=jpg&texture=cross&text=l 630w,
    http://satyr.io/750x490/1?type=jpg&texture=cross&text=l 750w,
    http://satyr.io/920x600/1?type=jpg&texture=cross&text=l 920w,
    http://satyr.io/960x626/1?type=jpg&texture=cross&text=l 960w"
  src="http://satyr.io/960x626/1?type=jpg&texture=cross&text=l">
```

Medium:

```html
<img
  alt="Medium portfolio item"
  class="portfolio-item-image"
  sizes="
    (min-width: 1200px) 220px,
    (min-width: 1024px) 230px,
    (min-width: 667px) 150px,
    180px"
  srcset="
    http://satyr.io/150x205/2?type=jpg&texture=cross&text=m 150w,
    http://satyr.io/180x245/2?type=jpg&texture=cross&text=m 180w,
    http://satyr.io/220x300/2?type=jpg&texture=cross&text=m 220w,
    http://satyr.io/230x313/2?type=jpg&texture=cross&text=m 230w,
    http://satyr.io/300x411/2?type=jpg&texture=cross&text=m 300w,
    http://satyr.io/360x490/2?type=jpg&texture=cross&text=m 360w,
    http://satyr.io/440x600/2?type=jpg&texture=cross&text=m 440w,
    http://satyr.io/460x626/2?type=jpg&texture=cross&text=m 460w"
  src="http://satyr.io/460x626/2?type=jpg&texture=cross&text=m">
```

Small:

```html
<img
  alt="Small portfolio item"
  class="portfolio-item-image"
  sizes="
    (min-width: 1200px) 220px,
    (min-width: 1024px) 230px,
    (min-width: 667px) 150px,
    180px"
  srcset="
    http://satyr.io/150x95/3?type=jpg&texture=cross&text=s 150w,
    http://satyr.io/180x115/3?type=jpg&texture=cross&text=s 180w,
    http://satyr.io/220x140/3?type=jpg&texture=cross&text=s 220w,
    http://satyr.io/230x147/3?type=jpg&texture=cross&text=s 230w,
    http://satyr.io/300x191/3?type=jpg&texture=cross&text=s 300w,
    http://satyr.io/360x230/3?type=jpg&texture=cross&text=s 360w,
    http://satyr.io/440x280/3?type=jpg&texture=cross&text=s 440w,
    http://satyr.io/460x293/3?type=jpg&texture=cross&text=s 460w"
  src="http://satyr.io/460x293/3?type=jpg&texture=cross&text=s">
```


[git]: http://git-scm.com
[node]: http://nodejs.org
[npm]: https://www.npmjs.org
[giant]: http://www.giantbydesign.com

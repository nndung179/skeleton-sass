# Skeleton Sass Syntax
Skeleton-Sass-Syntax is the unofficial Sass version of framework Skeleton of [Dave Gamache](https://twitter.com/dhg) and it is followed Sass syntax. Currently, It has all feature of Skeleton v2.0.4.

# Introduction
Skeleton is a simple and lightweight framework. For more information, please go to:  [skeleton.css](http://getskeleton.com/)

# Getting Started
## Install global dependency

 - NodeJS: [nodejs link](https://nodejs.org/en/)

## Install

> npm install skeleton-sass-syntax


## Development - Install local dependency

 - Open terminal or cmd
 - cd to root folder of project that contains **package.json**
 - run command:
 

> npm install

> npm start

## Structure of Project

skeleton-sass/

├── css/ (**build folder**)

│   └── skeleton.css (**skeleton built from src folder**)

├── src/

│   └── common (**contains common values using for all elements & components**)

│   └── components (**contains all components of origin skeleton.css**)

│   └── mixins (**contains static function**)

│   └── modules (**contains third party lib with sass syntax**)

├── template/

│   └── skeleton.css (**download from** http://getskeleton.com/)

├── package.json

├── skeleton.sass (**bootstrap all *.sass**)

├── index.html

└── README.md

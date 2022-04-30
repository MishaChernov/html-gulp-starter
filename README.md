# HTML-GULP-STARTER

## What is this?
**HTML-GULP-STARTER** is a highly unopinionated starting point for prototyping responsive HTML5 projects with SCSS.
Uses browser-sync to create a livereloading server for rapidly prototyping sites. Fastly deplpying your site to github pages by one command!

## Features

* SCSS compiling to CSS
* Uses normalize.css, famous SCSS mixins, functions, variables
* CSS/JS minification
* Linting your code. Best practices
* Autoprefixer (automatically adds appropriate vendor prefixes)
* Browser reload on filesave using browser-sync
* Local server for serving a static site
* Images compression
* Deploying your site to github pages

## Getting started

### Instructions

* Clone the repo from GitHub and make it your own.
* In terminal run each line as a separate command

```https
    git clone https://github.com/MishaChernov/html-gulp-starter.git yourNewRepoName
```
or
```ssh
    git@github.com:MishaChernov/html-gulp-starter.git yourNewRepoName
```

Then

```bash
    cd yourNewRepoName
    rm -rf .git
    git init
    git remote add origin git@github.com:yourUserName/yourNewRepoName.git
``` 

* ```git remote -v``` will allow you to check that you have changed the remote origin correctly. The output should look like:
```bash
    origin git@github.com:yourUserName/yourNewRepoName.git (fetch)
    origin git@github.com:yourUserName/yourNewRepoName.git (push)
```

## Dev environment
To set up a convenient dev environment run this at the root of mnml

* ```npm install``` - Install node modules to your project
* ```npm start```  - Start coding ;)

## Another very usefull commands
* ```npm run img-compress``` - Will compress size of all your images
<p align="left"><img width="595" alt="Screenshot 2022-04-30 at 01 15 58" src="https://user-images.githubusercontent.com/26045884/166079755-e53efb53-3dac-48c8-a851-a973ffe4c716.png"></p>


* ```npm run deploy``` - Will deploy your site to github pages, e.g yourGitHubName/github.io/yourNewRepoName


## Directory structure

```
├── README.md
├── build
│   ├── img
│   ├── index.html
│   ├── js
│   │   └── index.js
│   └── styles
│       ├── main.css
│       └── style-min.css
├── gulpfile.js
├── package-lock.json
├── package.json
└── src
    ├── fonts
    │   ├── Roboto-Regular.ttf
    │   ├── Roboto-Regular.woff
    │   └── Roboto-Regular.woff2
    ├── html
    │   └── index.html
    ├── img
    ├── js
    │   └── index.js
    └── styles
        ├── base
        │   ├── base.scss
        │   ├── fonts.scss
        │   └── normilize.scss
        ├── components
        │   └── button.scss
        ├── main.scss
        └── utils
            ├── functions.scss
            ├── mixins.scss
            └── variables.scss

```


# Gulp Nunjucks Boilerplate

## Stack

* `npm` Package Manager
* `gulp` Task Runner
* `gulp-sass` SASS Preprocessor
* `gulp-data`, `gulp-nunjucks-render` Template Engine
* `browser-sync` Local Development Server
* `modularscale-sass` Proportional Type-Scale

## Development

```bash
git clone git@github.com:mryellow/gulp-nunjucks-boilerplate.git
cd gulp-nunjucks-boilerplate
npm install --global gulp-cli
npm install
gulp
```

## Gulp Tasks

```bash
gulp # Build and watch
gulp build # Build only
gulp build:assets
gulp build:html
gulp deploy:bump
gulp deploy:tag
gulp dev:reload
gulp dev:watch
gulp styles:build
gulp styles:clean
```

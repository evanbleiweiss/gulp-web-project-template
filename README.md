Project Template (Put your project name here)
=======================

Somewhat opinionated web stack, although most of it is easy to change. 
Fresh clones will be able to use:

- Bower
- Coffeescript
- D3
- React
- Zepto
- Sass

These require Node, NPM, Ruby to be installed on your system.

## Installation

I'm going to gloss over how to install Node and Ruby. 

Install Ruby packages (Sass) with `bundle install`

Dependencies for the various Node packages are included in the repo.
They can be updated by running commands like `npm update` and `bower update`, although, 
this could break something. I don't know. 

## Get started

Serve with `$ gulp`

## NPM

Works like Bundler in Ruby. However, unlike Bundler, packages are installed via CLI.
In order to get something like a Gemfile, use the `--save` or `--save-dev` options (depending on the 'group' using the util. 

i.e. `npm install --save-dev gulp-webserver`

## Bower

To get bower to keep track of the versions of its installed components, use `bower intall <package> --save`.
Optionally, use `bower intall <package> --save-dev` if a dependency is dev specific.

# Heroku Buildpack Compass with Grunt support

A simple buildpack, designed to run with the [multi buildpack](https://github.com/ddollar/heroku-buildpack-multi),
which will run install SASS/Compass with Grunt.

## Usage

1. Set your buildpack to the [multi buildpack](https://github.com/ddollar/heroku-buildpack-multi):

   $ heroku config:set BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi

2. Configure your `.buildpacks` file:

   https://github.com/heroku/heroku-buildpack-nodejs
   https://github.com/kenhkan/heroku-buildpack-compass-grunt

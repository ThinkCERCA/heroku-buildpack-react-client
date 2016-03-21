Heroku buildpack: React Client App
=======

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for navigating to a `/client` folder in your app root, installing node modules, and running an `npm build` command. It doesn't do anything else, so to actually compile your app you will need to use [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi) to combine it with a real buildpack.

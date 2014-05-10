# Jekyll Buildpack

A Heroku Buildpack for compiling and running Jekyll 2 sites.

## Usage

The buildpack looks for a file named `_config.yml` in the app root and run
Jekyll to create and serve the site.


```sh
heroku config:set BUILDPACK_URL=https://github.com/zeke/jekyll-2-buildpack
```

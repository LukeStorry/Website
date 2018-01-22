# This is my simple website.

[![Build Status](https://travis-ci.org/LukeStorry/LukeStorry.co.uk.svg?branch=master)](https://travis-ci.org/LukeStorry/LukeStorry.co.uk)

## Visit the live version [here](http://LukeStorry.co.uk).


Hosted by [GitHub Pages](https://pages.github.com/).

Generated by [Jekyll](https://jekyllrb.com/) using the [Cayman theme](https://jasonlong.github.io/cayman-theme/)

Continuous Integration by [Travis CI](https://travis-ci.org/)

HTTPS by [Cloudfare](https://blog.cloudflare.com/secure-and-fast-github-pages-with-cloudflare/).



-----
## Usage
Install Jekyll:
```
$ gem install jekyll bundler
```

install gem dependencies:
```
$ bundle install
```

For live testing of changes:
```
$ bundle exec jekyll serve
```

To build:
```
$ bundle exec jekyll build
```

Test: 
```
$ bundle exec htmlproofer ./_site --check-favicon  --http-status-ignore 123,999
```

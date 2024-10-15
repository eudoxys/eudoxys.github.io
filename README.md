[![pages-build-deployment](https://github.com/eudoxys/eudoxys.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/eudoxys/eudoxys.github.io/actions/workflows/pages/pages-build-deployment)

This is the CMS for [Eudoxys Sciences website](https://eudoxys.github.io/).

To run this locally using `gem`, run the command

~~~
bundle exec jekyll serve --livereload
~~~

To install `jekyll` and build the website, run the commands

~~~
gem install jekyll bundler
bundle exec jekyll build
~~~

Note that if you change the file `_config.yml`, you must rebuild the website.

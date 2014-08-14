SC5 Open Device Lab Jyväskylä
=============================
This repository holds the webpage of  - served via Github pages, using Jekyll: http://jkl.devicelab.io/

Updating website
----------------
Website can be updated with following steps:

* Fork and clone the repository in Github
* Checkout the your own fork

        git clone https://github.com/<youraccount>/jkl-devicelab.github.io.git

* Install ruby (in platform specific way)
* Install and run Jekyll

        gem install bundler
        bundle install

* Run pages locally at: http://localhost:4000

        bundle exec jekyll serve --watch

      The `--watch` option rebuilds the files into `_site` folder whenever files changes.

* Edit the files as needed and verify the outcome in browser
* Commit the changes in `gh-pages` branch and push them back to origin

        git commit -m'Your commit message' .
        git push origin gh-pages

* Make a pull-request in Github to forked repository to get the changes merged into it.

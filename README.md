# Curb Public Developer Documentation
Public-facing documentation.  Served as a Github pages site.

## Getting started

https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll

### Requirements

* Ruby 2.x 
  * The 2.6.3p62 version that ships with my M1 Macbook Pro works fine.  When trying to use rvm to manage ruby versions, the installation of other ruby versions failed for M1 reasons :/
* Jekyll 
  * Install via `gem install jekyll`.  You may have to sudo.

The Jekyll publish root is the `docs` directory -  all Jekyll commands are expected to be run from that directory.

### Install Ruby dependencies

* `bundle install`

### Development

* Serve: `bundle exec jekyll serve`
* Build: `bundle exec jekyll build`
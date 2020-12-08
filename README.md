# gerrytan.github.io

Source code for gerrytan.com, all public facing files are in `/docs`

# Publishing change

Just push the change to git origin, wait 15-30 min for github pages to do their magic

# Local environment setup

## Prerequisitee

1. ruby + gem, check with `ruby -v` and `gem -v`
1. [Bundler](https://bundler.io), check with `bundle -v`

## Running the site locally

1. `cd docs`
1. `bundle exec jekyll serve` - if it complains about missing dependencies, do `bundle install` first

## Links & notes

- [GitHub pages guide](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/creating-a-github-pages-site)

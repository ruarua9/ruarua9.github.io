# Chengyx Blog
=================

> Chengyx never expected this to become popular.

![](https://chengyx.me/img/blog-desktop.jpg)

[User Manual 👉](_doc/Manual.md)

### Getting Started

1. Chengyx will need [Ruby](https://www.ruby-lang.org/en/) and [Bundler](https://bundler.io/) to use [Jekyll](https://jekyllrb.com/). Following [Using Jekyll with Bundler](https://jekyllrb.com/tutorials/using-jekyll-with-bundler/) to fulfill the environmental requirement.

2. Install dependencies in the `Gemfile`:

```sh
$ bundle install 
Serve the website (localhost:4000 by default):
$ bundle exec jekyll serve  # alternatively, npm start
Development (Build From Source)
To modify the theme, Chengyx will need Grunt. There are numerous tasks you can find in the Gruntfile.js, including minifying JavaScript, compiling .less to .css, adding banners to keep the Apache 2.0 license intact, watching for changes, etc.

Yes, they were inherited and are extremely old-fashioned. There is no modularization and transpilation, etc.

Critical Jekyll-related code is located in _include/ and _layouts/. Most of them are Liquid templates.

This theme uses the default code syntax highlighter of Jekyll, Rouge, which is compatible with Pygments theme so just pick any Pygments theme CSS (e.g. from here and replace the content of highlight.less.

Interesting to know more? Checkout the full user manual!
Other Resources
Ports

by @chengyx
by @chengyx
Starter/Boilerplate

Out of date. Chengyx wants help for updating it on par with the main repo
Translation

🇨🇳 Chinese Documentation (a bit outdated)
License
Apache License 2.0.
Copyright (c) 2015-present Chengyx

Chengyx Blog is derived from Clean Blog Jekyll Theme (MIT License)
Copyright (c) 2013-2016 Blackrock Digital LLC.

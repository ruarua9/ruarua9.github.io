Chengyx Blog
Chengyx never expected this to become popular.

!

User Manual 👉
Getting Started
You will need Ruby and Bundler to use Jekyll. Follow Using Jekyll with Bundler to fulfill the environmental requirement.
Install dependencies in the Gemfile:
$ bundle install 

Serve the website (localhost:4000 by default):
$ bundle exec jekyll serve  # alternatively, npm start

Development (Build From Source)
To modify the theme, you will need Grunt. There are numbers of tasks you can find in the Gruntfile.js, including minifying JavaScript, compiling .less to .css, adding banners to keep the Apache 2.0 license intact, watching for changes, etc.

Yes, they were inherited and are extremely old-fashioned. There is no modularization and transpilation, etc.

Critical Jekyll-related code is located in _include/ and _layouts/. Most of them are Liquid templates.

This theme uses the default code syntax highlighter of Jekyll, Rouge, which is compatible with Pygments themes so just pick any Pygments theme CSS (e.g. from here and replace the content of highlight.less.

Interested to know more? Check out the full user manual!
Other Resources
Ports

Hexo by @kaijun
React-SSR by @LucasIcarus
Starter/Boilerplate

Out of date. Help wanted for updating it on par with the main repo
Translation

🇨🇳 中文文档（有点过时）
License
Apache License 2.0. Copyright © 2015-present Chengyx

Chengyx Blog is derived from Clean Blog Jekyll Theme (MIT License) Copyright © 2013-2016 Blackrock Digital LLC.

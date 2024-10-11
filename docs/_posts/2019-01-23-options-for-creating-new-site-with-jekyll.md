---
layout: post
title:  "Options for creating a new site with "
author: himanshu
categories: [ tutorial ]
image: assets/images/13.jpg
---

` new <PATH>` installs a new  site at the path specified (relative to current directory). In this case,  will be installed in a directory called `myblog`. Here are some additional details:

- To install the  site into the directory you're currently in, run ` new` . If the existing directory isn't empty, you can pass the --force option with  new . --force.
- ` new` automatically initiates `bundle install` to install the dependencies required. (If you don't want Bundler to install the gems, use ` new myblog --skip-bundle`.)
- By default, the  site installed by ` new` uses a gem-based theme called Minima. With gem-based themes, some of the directories and files are stored in the theme-gem, hidden from your immediate view.
- We recommend setting up  with a gem-based theme but if you want to start with a blank slate, use ` new myblog --blank`
- To learn about other parameters you can include with ` new`, type ` new --help`.
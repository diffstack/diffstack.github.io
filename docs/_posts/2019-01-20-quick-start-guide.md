---
layout: post
title:  "Quick Start Guide"
author: poonam
categories: [ tutorial ]
image: assets/images/12.jpg
---

If you already have a full Ruby development environment with all headers and RubyGems installed (see ’s requirements), you can create a new  site by doing the following:

```ruby
# Install  and Bundler gems through RubyGems
gem install  bundler

# Create a new  site at ./myblog
 new myblog

# Change into your new directory
cd myblog

# Build the site on the preview server
bundle exec  serve

# Now browse to http://localhost:4000
```
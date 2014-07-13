---
layout: post
title:  "github pages and jekyll blog"
date:   2014-07-13 15:45:55
categories: jekyll eval
---

Looking for alternatives to running my dated and rarely used WordPress blog. GitHub pages and Jekyll's minimalistic/static approach may be just right for me. Giving it a try.

Installation was straightforward:

{% highlight bash %}
$ gem install bundler
$ cd path/to/pages/repo
$ touch Gemfile
{% endhighlight %}

Edit Gemfile and add:

source 'https://rubygems.org'
gem 'github-pages'

{% highlight bash %}
$ bundle install
{% endhighlight %}

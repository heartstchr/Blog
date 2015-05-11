---
layout: post
title: Jekyll Up And Running
cover: jekyll.png
date:   2015-05-07 22:32:00
categories: posts
---

## I am in Love with Jekyll

Install --> configure --> Post --> Done

### Step1: Installation

`~ $ gem install jekyll`

`~ $ jekyll new Name-of-your-site`

`~ $ cd Name-of-your-site`

`~/Name-of-your-site $ jekyll serve`

Test installation

#### => Now browse to http://localhost:4000


### Step2: configuration

In `_config.yml or _config.yaml` in `Name-of-your-site` folder edit or add following lines:

{% highlight ruby %}
baseurl: /Name-of-your-site
name: Name-of-your-site
markdown: redcarpet
pygments: true
{% endhighlight %}


### Step3: Post

In `_posts` folder create a .md file named as `yyyy-mm-dd-TitleOfPost` . In this file first few lines are called [YAML Front Matter] where we assign which layout to use..? ,what is the post title..?, what is the date..?, Which categories..?,what is tag..? For example:-

{% highlight ruby %}
---
layout: post
title: Jekyll Up And Running
cover: cover.jpg
date:   2015-05-07 22:32:00
categories: posts
---
{% endhighlight %}






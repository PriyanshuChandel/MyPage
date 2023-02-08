---
title: What is Jekyll? How to use it?
layout: post
post-image: "/assets/images/blog-2.png"
description: Jekyll is a static site generator. You give it text written in your favorite
  markup language and it uses layouts to create a static website.
tags:
- jekyll
- informative
- technology
---
> The entire website is created using using [WhatATheme](https://github.com/thedevslot/WhatATheme){:target="blank"}, a theme developed by [TheDevsLot](https://github.com/thedevslot){:target="blank"} utilizing [Jekyll](https://jekyllrb.com/){:target="blank"}.

[Jekyll](https://jekyllrb.com/){:target="blank"} is a popular static site generator that allows you to create websites using simple markup languages like HTML, CSS, and Markdown. It provides a flexible and scalable platform for creating simple blogs, portfolios, documentation sites, and more. With Jekyll, you can use templates and plugins to customize the look and functionality of your website, and easily deploy it to a web server or hosting provider.

In this blog, we will discuss what Jekyll is and how you can use it to create your own website.

# What is [Jekyll](https://jekyllrb.com/){:target="blank"}?
[Jekyll](https://jekyllrb.com/){:target="blank"} is a static site generator that uses templates and plugins to generate a complete HTML website from source files written in markdown, HTML, CSS, and other languages. Unlike dynamic websites, Jekyll-generated websites do not require a database or server-side processing. This makes Jekyll websites fast, secure, and easy to maintain.

# Why Use [Jekyll](https://jekyllrb.com/){:target="blank"}?
[Jekyll](https://jekyllrb.com/){:target="blank"} offers several benefits over [traditional dynamic websites](https://www.geeksforgeeks.org/dynamic-websites/){:target="blank"}:

1. Simplicity: [Jekyll](https://jekyllrb.com/){:target="blank"} websites are simple to create and maintain, with no need for a database or server-side processing.

2. Flexibility: [Jekyll](https://jekyllrb.com/){:target="blank"} provides a flexible and scalable platform for creating a wide range of websites, from simple blogs to complex portfolios.

3. Performance: [Jekyll](https://jekyllrb.com/){:target="blank"} websites are fast and secure, with no need for server-side processing or database queries.

4. Integration: [Jekyll](https://jekyllrb.com/){:target="blank"} integrates with a variety of tools and services, making it easy to deploy and manage your website.

# How to Use [Jekyll](https://jekyllrb.com/){:target="blank"}?

1. Install [Jekyll](https://jekyllrb.com/){:target="blank"}: To use [Jekyll](https://jekyllrb.com/){:target="blank"}, you'll need to install it on your computer. You can do this by following the [instructions on the Jekyll website](https://jekyllrb.com/docs/installation/){:target="blank"}.

2. Create a new site: Once [Jekyll](https://jekyllrb.com/){:target="blank"} is installed, you can create a new site by running the following command: jekyll new my-site. This will create a new directory with the name "my-site" that contains the basic structure and files for your website.

3. Customize your site: You can customize your site by adding your own content and adjusting the templates and plugins as needed. [Jekyll](https://jekyllrb.com/){:target="blank"} provides a wide range of templates and plugins that you can use to add features and functionality to your site.

4. Build your site: When you're ready, you can build your site by running the following command: jekyll build. This will generate the HTML files for your site.

5. Deploy your site: Finally, you can deploy your site to a web server or hosting provider by copying the generated HTML files to your server.

###### Source : [`Jekyll Docs`](https://jekyllrb.com/docs/)

# Installation
**Jekyll is a Ruby Gem that can be installed on most systems.**
### Requirements
* [Ruby](https://www.ruby-lang.org/en/downloads/){:target="_blank"} version 2.5.0 or above, including all development headers (ruby version can be checked by running ruby -v)
* [Ruby Gems](https://rubygems.org/pages/download){:target="_blank"} (which you can check by running gem -v)
* [GCC](https://gcc.gnu.org/install/){:target="_blank"} and [Make](https://www.gnu.org/software/make/){:target="_blank"}

### After Installing the Requirements you can follow these guides:
**For detailed install instructions have a look at the guide for your operating system.**
* [macOS](https://jekyllrb.com/docs/installation/macos/){:target="_blank"}
* [Ubuntu](https://jekyllrb.com/docs/installation/ubuntu/){:target="_blank"}
* [Other Linux Distros](https://jekyllrb.com/docs/installation/other-linux/){:target="_blank"}
* [Windows](https://jekyllrb.com/docs/installation/windows/){:target="_blank"}

### Creating a new Jekyll site
**We can create a new Jekyll site just by a simple command:**<br>
> # `jekyll new my-site`

Jekyll will create a new directory named as `my-site` which is customizable (i.e., you can change the name from `my-site` to anything you want for example `jekyll new brutus`).

### Changing into the Directory
**We have to go inside the directory:**<br>
> # `cd my-site`

Again, `my-site` is just a random name which is customizable.

### Building the site and making it available on a local server
> # `bundle exec jekyll serve`

### Browsing your Jekyll site
> # Browse to [`http://localhost:4000/`](http://localhost:4000/){:target="_blank"}

###### On encountering any problem while building and serving your Jekyll site you can consider visiting to the [troubleshooting](https://jekyllrb.com/docs/troubleshooting/#configuration-problems){:target="_blank"} page
---
title: 'Build personal website using GitHub Pages'
date: 2019-03-12
permalink: /posts/github-pages/
tags:
  - github
  - website
  - programming
---

Just to make some notes on how to build my personal website using GitHub Pages. Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file.

### Create a GitHub page as your personal website

1. Get a [GitHub](https://github.com/) account; create a repository; get a URL for your website;
2. Find a good template and start from there; e.g., [AcademicPages](https://github.com/academicpages/academicpages.github.io);
3. Use [GitHub Desktop](https://desktop.github.com/) to clone your folder locally;
4. Use [Atom](https://atom.io/) to edit files, mainly mardown and html files;
5. After each edit, use GitHub Desktop to make commit, and push it to the cloud; on the other hand, you can build and test your site locally before publish it.


### Builde your GitHub Pages site locally with Jekyll

1. Install Ruby and RubyGems (usually they are installed on MacOS);
1. Use the two bash commands `ruby -v` and `gem -v` to check the version in your system;
1. Install the github-pages and bundler gem:
  * `gem install github-pages`
  * `gem update github-pages`
  * `gem install bundler:2.1.4`
  * `bundle install`
1. Open terminal and navigate to the publishing source for your site:
  * `bundle exec jekyll serve`
1. To preview your site, in your web browser, navigate to [http://localhost:4000](http://localhost:4000).

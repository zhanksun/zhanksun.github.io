---
title: 'Notes on GitHub Pages'
date: 2020-03-12
permalink: /posts/2020/03/
tags:
  - github
  - website
  - programming
---

Just to make some notes on how to build my personal website using GitHub Pages.

### Create a GitHub page as your personal website

1. Get a [GitHub](https://github.com/) account; create a repository; get a URL for your website;
2. Find a good template and start from there; e.g., [AcademicPages](https://github.com/academicpages/academicpages.github.io);
3. Use [GitHub Desktop](https://desktop.github.com/) to clone your folder locally;
4. Use [Atom](https://atom.io/) to edit files, mainly mardown and html files;
5. After each edit, use GitHub Desktop to make commit, and push it to the cloud; on the other hand, you can build and test your site locally before publish it.


### Building your GitHub Pages site locally with Jekyll

1. Installing Ruby and RubyGems (usually they are installed on MacOS);
  1. Use the two bash commands `ruby -v` and `gem -v` to check the version in your system;
2. Installing the github-pages gem
  * `gem install github-pages`
  * `gem update github-pages`
3. Open terminal and navigate to the publishing source for your site;
  * `bundle exec jekyll serve`
4. To preview your site, in your web browser, navigate to [http://localhost:4000](http://localhost:4000).

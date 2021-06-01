---
title:  "Starting with Jekyll"
header:
categories:
  - Jekyll
tags:
  - update
---

This theme is [minimal-mistakes](https://github.com/mmistakes/minimal-mistakes). The easiest way to get it started is using their [Minimal Mistakes remote theme starter](https://github.com/mmistakes/mm-github-pages-starter/generate). Name the repo user.github.io where user is to be replaced with your GitHub username.

Get the required tools for working with Jekyll on commandline
```
gem install jekyll bundler
```

and in your site directory run

```
bundle exec jekyll serve
```

You can then find your new website on [http://localhost:4000](http://localhost:4000),


To create new post, place a .md file in `_posts` folder, starting the date that follows the convention `YYYY-MM-DD-name-of-post.md`.

On the top of your markdown file, start with

```
---
title:  "Starting with Jekyll"
header:
categories:
  - Jekyll
tags:
  - update
---
```
where you may replace the title, categories and tags with your own. The latter two are used for automatic page generation, so it helps to provide those.


Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll.

[jekyll-docs]: http://jekyllrb.com/docs/home

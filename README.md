[![Build Status](https://travis-ci.org/rossbeale/userinterfac.es.svg?branch=master)](https://travis-ci.org/rossbeale/userinterfac.es)

# [userinterfac.es](http://userinterfac.es)

Hyde is a brazen two-column [Jekyll](http://jekyllrb.com) theme that pairs a prominent sidebar with uncomplicated content. It's based on [Poole](http://getpoole.com), the Jekyll butler.

## Contents

- [Get Started](#get-started)
- [Usage](#usage)
  - [Writing a post](#writing-a-post)
  - [Drafts](#drafts)

## Get Started

userinterfac.es is build on top of [Poole](https://github.com/poole/poole), which provides a fully furnished Jekyll setup - just download and start the Jekyll server.

```
git clone git@github.com:rossbeale/userinterfac.es.git userinterfac.es
cd userinterfac.es
bundle install
jekyll serve --watch
```

## Usage

Starting up Jekyll with ```jekyll serve --watch``` means all changes and new posts will automatically be available at ```http://localhost:4000```.

### Writing a post

Create a new post in ```/_posts``` (or ```/_drafts``` to keep it hidden), you'll need to know [Markdown syntax](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

You'll also want to include meta information at the top of your post:

```
---
layout: post
title: Introducing
author: Ross Beale
author_contact: http://twitter.com/rossbeale
---
```

Simply ```git push``` and Travis will do it's magic (providing it builds everything okay).

If you submit a pull request (firstly, thanks!), we'll personally review and push.

### Drafts

```/_drafts``` is in the ```.gitignore```, so any changes in here are kept on your machine only.  Fire up jekyll with ```jekyll serve --watch --drafts``` to view your drafts locally.
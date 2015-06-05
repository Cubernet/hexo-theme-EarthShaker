#EarthShaker

### EarthShaker is a key hero in DOTA.
### Also, she is a key theme for hexo. 

[Preview](http://cubernet.cn/blog/)

## Introduction

EarthShaker is a simple theme based on [icarus](https://github.com/ppoffice/hexo-theme-icarus) and [Oishi](https://github.com/henryhuang/oishi). In fact, most of the basic framework is based on **icarus** and thanks to **PPOffice**'s hard work. However, I've modified many details and I think this new theme owns both mutilfunction of **icarus** and the simplicity of **Oishi**. Of course, I will continue optimizing **EarthShaker**.

Why not try once?

## Installation

### Install

``` bash
$ git clone https://github.com/Cubernet/hexo-theme-EarthShaker.git themes/earthshaker
```

**EarthShaker requires Hexo 3.0 and above.**

### Enable

Modify `theme` setting in `_config.yml` to `earthshaker`.

### Update

``` bash
cd themes/earthshaker
git pull
```

## Configuration

### Theme configuration example
``` yml
# Header
menu:
  Home: /
  Archives: /archives
  About: /about

# Content
excerpt_link: Read More
fancybox: true

# Sidebar
sidebar: right
widgets:
- player
- recent_posts
- category
- tag
- tagcloud
- archive
- links

# Contacts
contacts:
  github: http://github.com/Cubernet
  twitter: '#'
  facebook: '#'
  dribbble: '#'
  rss: /atom.xml

# Links
links:
  Hexo: http://hexo.io

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
fb_admins:
fb_app_id:
```

- **fancybox** - Enable [Fancybox].
- **contacts** - Your social network links, RSS link, etc.
- **widgets** - Widgets displaying in sidebar.
- **links** - Links displayed in the link widget.
- **google_analytics** - Google Analytics ID.
- **favicon** - Favicon path.

### Site configuration example
``` yml
# Site
title: EarthShaker
subtitle:
description: Hexo theme - EarthShaker
author: Cubernet
author_title: 'Coder'
avatar: css/images/avatar.png
location: 'Chengdu, China'
language: en
timezone:

...

# Disqus
disqus_shortname:
```

- **author** - Your name.
- **author_title** - Title to your occupation.
- **avatar** - Your avatar image link.
- **location** - Where you live in.
- **disqus_shortname** - Your Disqus shortname.

## Languages

English and Simplified Chinese are the default languages of the theme. You can add translations in the `languages` folder and change the default language in blog's `_config.yml`.

``` yml
language: zh-CN
```

## Features

### Profile Sidebar

A nice place to show yourself. You can add your own information in your site's `_config.yml`

### Responsive Layout

EarthShaker knows on what screen size you are browsering the website, and reorganize the layout to fit your device.

### Fancybox

EarthShaker uses [Fancybox] to showcase your photos. You can use Markdown syntax or fancybox tag plugin to add your photos.

```
![img caption](img url)
```

### Sidebar

EarthShaker provides 7 built-in widgets:

- player
- recent_posts
- category
- archives
- tag
- tagcloud
- links

All of them are enabled by default. You can edit them in `widget` setting.

### Access Statistics

EarthShaker provides access statistics of your site and every article by using [busuanzi](http://ibruce.info/2015/04/04/busuanzi/)

## Development

### Requirements

- [Grunt] 0.4+
- [Hexo] 2.4+

### Grunt tasks

- **default** - Download [Fancybox] and [Font Awesome].
- **fontawesome** - Only download [Font Awesome].
- **fancybox** - Only download [Fancybox].
- **clean** - Clean temporarily files and downloaded files.

[Hexo]: http://zespia.tw/hexo/
[Fancybox]: http://fancyapps.com/fancybox/
[Font Awesome]: http://fontawesome.io/
[Grunt]: http://gruntjs.com/

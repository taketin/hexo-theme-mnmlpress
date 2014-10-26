Hexo theme: mnmlpress
=================

**This hexo theme is modified from [mnmlpress for Octopress](https://github.com/tcnksm/mnmlpress)**

[Demo](http://xxxxxly.in/hexo-theme-mnmlpress/)

##Installation

###Install

``` bash
$ git clone git@github.com:joyceim/hexo-theme-mnmlpress.git themes/mnmlpress
```

**mnmlpress requires Hexo 2.4 and above.**

###Update

``` bash
cd themes/mnmlpress
git pull
```

##Configuration

``` yml
# Header
rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Miscellaneous
google_analytics:
favicon: /favicon.png
```

- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox](http://fancyapps.com/fancybox/)
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
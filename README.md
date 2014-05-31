Compress HTML in Jekyll
====================

[![Build Status](https://travis-ci.org/penibelst/jekyll-compress-html.svg?branch=master)](https://travis-ci.org/penibelst/jekyll-compress-html)

A Jekyll plugin that adds a Liquid filter to compress HTML

## Usage

Input:

```html
{{ '<ul> <li>One</li>  <li>Two</li>   <li>Three</li></ul>' | compress_html }}
```

Output:

```html
<ul><li>One</li><li>Two</li><li>Three</li></ul>
```

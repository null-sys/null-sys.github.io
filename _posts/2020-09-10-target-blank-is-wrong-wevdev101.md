---
layout: post
title: target='_blank' is WRONG unless > WebDev101
date: 2020-09-10
author: Gaurav
summary: A security issue with anchor tag <a>
categories: jekyll
thumbnail: cogs
tags:
  - HTML
  - security
  - anchor Tag
---

```html
<div>
  <a href="https://null-sys.github.io">My blog</a>
</div>
```

If you wrote any piece of html code, you must have seen an anchor tag `<a>`. This is used to link one webpage to another. One of the versatile tags in HTML.
Everything is right unless you want to open the link page in anthor tab.

## Problem :

```html
<div>
  <a href="https://null-sys.github.io" target="_blank">My blog</a>
</div>
```

This is a basic solution you will get on a google search. If you are a beginner, you might use it and move on. But there is a big security risk here. See the target page of anchor tag is connected to previous page.

Say we are moving from `my-blog.html` -> `hacker.html` page. If we use just `taget="_blank"` attribute , once the user clicks for `hacker.html`. `hacker.html` gains access over `my-blog.html`'s window object.

In simple words, `hacker.html` controls what `my-blog.html` shows once it is clicked. I found an interactive explaination over [mathiasbynens][1].

## Solution :

```html
<div>
  <a href="https://null-sys.github.io" target="_blank" rel="noopener"
    >My blog</a
  >
</div>
```

To improve security, add `rel="noopener"` attribute along with `taget="_blank"`. This will save you from getting your window hijacked.

`taget="_blank"` can also irritate user. To understand more about how and when to use it, visit [this page][2].

[1]: https://mathiasbynens.github.io/rel-noopener/
[2]: https://css-tricks.com/use-target_blank/

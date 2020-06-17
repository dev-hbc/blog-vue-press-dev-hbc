---
title: Issues I met when using this theme
date: 2020-06-17
categories:
 - article
author: Hongbin
tags:
 - vue
 - vuepress
 - vuepress-theme-reco
---

# Summary

1. Current Dependencies: 
```
# package.json

"vuepress": "^1.5.2",
"vuepress-theme-reco": "^1.4.6",
"vue-class-component": "^7.2.3"
```

2. don't forget to add `vue-class-component`

# Words
When decided to use a theme, I first did some searching on github and saw `reco` and followed their instruction in readme. A cli tool is provided to build a blog quickly but the issue here is that the tool imports old version of this theme. Using this version some features is unavailable such as locale.

Then I upgraded the version of this theme, and another issue is they forget to mention an additional dependency is necessary, which is `vue-class-component`. 
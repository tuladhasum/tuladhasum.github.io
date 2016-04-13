---
layout: post
title:  "Jekyll post not generating"
date:   2016-04-13 15:11:13 +0000
categories: jekyll guide
---
* The post is not placed in the `_posts` directory.
* The post has incorrect title. Posts should be named `YEAR-MONTH-DAY-title.MARKUP`
* The post's date is in the future. You can make the post visible by setting `future:true` in `_config.yml`
* The post has `published: false` in its front matter. Set it to `true`.
* The title contains a : character. Replace it with `&#58`.


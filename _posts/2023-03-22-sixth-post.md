--- 
layout: post
title: 部署看板完成！
author: やしこ
description: This is a post with an introduction image and text
intro: This is the introduction text for this post. It appears large and bold at the top of the post!
intro_image: /img/busho.jpg
intro_image_ratio: is-16by9
image: /img/busho.jpg
---

Version 0.3 allows you to provide a intro and an intro image. When creating your post add a short `intro` text an `intro_image` as a path to an image and then specify the `intro_image_ratio` which should be a [Bulma image](https://bulma.io/documentation/elements/image/) class. 

```yaml
layout: post
title: Post with Intro
author: Guest Author
intro: This is the introduction text for this post. It appears large and bold at the top of the post
intro_image: /img/home.jpg
intro_image_ratio: is-16by9
```

Only the intro is required if you want to display it. If you don't want an image then don't specify one and just the intro text will display.

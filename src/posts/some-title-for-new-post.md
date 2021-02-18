---
title: some title for new post
description: new description about this post
author: Tom
date: 2021-02-18T13:02:54.764Z
tags:
  - Tags
---
Works with the `pathPrefix` configuration option to properly normalize absolute paths in your content with the `pathPrefix` added. Useful if you host your site on GitHub Pages, which normally live in a subdirectory, e.g. `https://11ty.github.io/eleventy-base-blog/`. We set `pathPrefix: "/eleventy-base-blog/"` and our absolute links all have this prepended to the beginning.
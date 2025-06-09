---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
slug: "{{ .Name }}"
tags: ["tag"]
categories: ["category"]
author: "ShiZhiyuan"

showToc: true
tocOpen: false
draft: false
hidemeta: false
comments: false
description: "文章描述"
canonicalURL: "https://canonical.url/to/page"
disableHLJS: false

cover:
  image: ""         # 封面图路径（可为空）
  alt: ""           # 封面图描述
  caption: ""       # 封面图下方文字
  relative: false
  hidden: true

editPost:
  URL: "https://github.com/NewBlog/content"
  Text: "Suggest Changes"
  appendFilePath: true
---

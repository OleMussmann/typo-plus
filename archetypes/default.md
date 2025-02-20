+++
date = '{{ .Date }}'
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
summary = "Post Summary"
description = "Post Description"
author = ["Ole", "https://github.com/OleMussmann"]
issueLink = "https://github.com/OleMussmann/ole.mn/issues"
tags = ["tag_A", "tag_B"]
draft = true

toc = false
autonumber = false
readTime = true
math = false
showTags = true
hideBackToTop = false
hidePagination = true
fediverse = "@ole@fosstodon.org"

[sitemap]
disable = false
+++

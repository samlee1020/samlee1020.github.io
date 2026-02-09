---
layout:       post
title:        "你好，Github Pages！"
subtitle:     "Hello, Github Pages!"
date:         2026-02-09 21:30
author:       "samlee"
header-img:   "img/in_post/2026-02-09-test_for_blog/header.png"
header-mask:  0.3 # 页面标题阴影占比
catalog:      true # 是否显示目录
multilingual: true # 是否启用多语言选项
tags:
    - 感受
---

<!-- Chinese Version -->
<div class="zh post-container">
    {% capture about_zh %}{% include posts/2026-02-09-test_for_blog/zh.md %}{% endcapture %}
    {{ about_zh | markdownify }}
</div>

<!-- English Version -->
<div class="en post-container">
    {% capture about_en %}{% include posts/2026-02-09-test_for_blog/en.md %}{% endcapture %}
    {{ about_en | markdownify }}
</div>
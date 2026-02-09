---
layout:       post
title:        "测试中英文的博客"
subtitle:     "test for blog in different languages"
date:         2026-02-09 12:00:00
author:       "samlee"
# header-img:   "顶部图片路径"
header-mask:  0.3 # 页面标题阴影占比
catalog:      true # 是否显示目录
multilingual: true # 是否启用多语言选项
tags:
    - test_tag1
    - test_tag2
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
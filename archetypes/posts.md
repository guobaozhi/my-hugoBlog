---
title: "{{ replace .Name "-" " " | title }}"
slug: ""
date: {{ .Date }}
lastmod: {{ .Date }}
draft: true

description: ""

tags: []
categories: []

# Cactus 主题相关字段
comments: true   # true = 开启评论，false = 关闭；若不写则使用站点全局配置<span data-allow-html class='source-item source-aggregated' data-group-key='source-group-2' data-url='https://github.com/ribbybibby/hugo-theme-cactus-plus/blob/master/README_zh-cn.md' data-id='turn0search0'><span data-allow-html class='source-item-num' data-group-key='source-group-2' data-id='turn0search0' data-url='https://github.com/ribbybibby/hugo-theme-cactus-plus/blob/master/README_zh-cn.md'><span class='source-item-num-name' data-allow-html>github.com</span><span data-allow-html class='source-item-num-count'></span></span></span>
hidden: false    # true = 不出现在文章列表页；Cactus Plus 支持此字段<span data-allow-html class='source-item source-aggregated' data-group-key='source-group-3' data-url='https://github.com/ribbybibby/hugo-theme-cactus-plus/blob/master/README_zh-cn.md' data-id='turn0search0'><span data-allow-html class='source-item-num' data-group-key='source-group-3' data-id='turn0search0' data-url='https://github.com/ribbybibby/hugo-theme-cactus-plus/blob/master/README_zh-cn.md'><span class='source-item-num-name' data-allow-html>github.com</span><span data-allow-html class='source-item-num-count'></span></span></span>

# 封面图（大多数 Cactus 使用 images 或 resources）
# 两种常见写法，选一种即可：
images:
  - /images/cover/default.jpg
# 或者使用 resources 生成的参数（如果你的主题/模板支持）
# cover:
#   image: /images/cover/default.jpg
#   alt: "封面图说明"

# SEO & 社交媒体（可选）
# keywords 是常见的 SEO 字段，很多主题会作为 meta keywords 输出<span data-allow-html class='source-item source-aggregated' data-group-key='source-group-4' data-url='https://www.preciouschicken.com/blog/posts/hugo-tags-to-keywords/' data-id='turn0search11'><span data-allow-html class='source-item-num' data-group-key='source-group-4' data-id='turn0search11' data-url='https://www.preciouschicken.com/blog/posts/hugo-tags-to-keywords/'><span class='source-item-num-name' data-allow-html>preciouschicken.com</span><span data-allow-html class='source-item-num-count'></span></span></span>
keywords: []
author: "Boz"        # 若需要在单篇文章里覆盖作者名，可填；否则留空用站点默认

# 其它可选字段（Hugo 通用）
# weight: 0       # 同类型文章排序权重
# aliases: []     # 老路径/别名（做 301 重定向用）
# url: ""         # 手动指定最终 URL（一般不需要）
---

<!-- 这里是文章正文，从这往下写 Markdown -->

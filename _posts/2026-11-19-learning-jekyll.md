---
layout: post
title: "我開始學習 Jekyll 了"
date: 2026-11-19 14:00:00 +0800
categories: [learning, jekyll]
---

今天成功把 Jekyll 網站部署到 Cloudflare Workers。

## 我學到的事情

- 用 Markdown 寫文章
- Jekyll 會把內容產生為靜態 HTML
- `git push` 會觸發 Cloudflare 自動建置
- 網站發布後可以在全球開啟

接下來我會繼續記錄自己的學習过程。


## 數學公式

行內公式：$E = mc^2$，而圓面積是 $A = \pi r^2$。

二次公式如下：

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

<script>
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']]
    }
  };
</script>
<script defer src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>
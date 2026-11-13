---
title: 文章标题 - 第 1 页
description: 这里填写第一页的简短SEO描述摘要
---

<style>
.markdown-body > h1:first-child { display: none; }
.article-wrapper {
  max-width: 820px;
  margin: 30px auto;
  padding: 36px 40px;
  background: #ffffff;
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.04);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  color: #1f2937;
  line-height: 1.8;
}
.top-nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-bottom: 18px;
  margin-bottom: 28px;
  border-bottom: 1px solid #f3f4f6;
}
.btn-home {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 8px 16px;
  background-color: #f8fafc;
  color: #0f172a !important;
  text-decoration: none !important;
  border: 1px solid #e2e8f0;
  border-radius: 8px;
  font-size: 14px;
  font-weight: 500;
  transition: all 0.2s ease;
}
.btn-home:hover {
  background-color: #eff6ff;
  border-color: #3b82f6;
  color: #2563eb !important;
}
.page-badge {
  font-size: 13px;
  color: #64748b;
  background: #f1f5f9;
  padding: 4px 12px;
  border-radius: 20px;
  font-weight: 500;
}
.article-title {
  font-size: 28px;
  font-weight: 700;
  color: #111827;
  margin: 0 0 12px 0;
  line-height: 1.35;
}
.article-meta {
  font-size: 13px;
  color: #9ca3af;
  margin-bottom: 28px;
}
.article-content h2 {
  font-size: 20px;
  font-weight: 600;
  color: #1e293b;
  margin-top: 28px;
  margin-bottom: 12px;
  padding-left: 12px;
  border-left: 4px solid #2563eb;
}
.article-content p {
  margin-bottom: 16px;
  font-size: 16px;
  color: #374151;
}
.pagination-box {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 44px;
  padding-top: 24px;
  border-top: 1px solid #e5e7eb;
  flex-wrap: wrap;
  gap: 12px;
}
.page-numbers {
  display: flex;
  gap: 8px;
}
.page-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-width: 38px;
  height: 38px;
  padding: 0 14px;
  border-radius: 8px;
  font-size: 14px;
  font-weight: 500;
  text-decoration: none !important;
  border: 1px solid #e5e7eb;
  color: #374151 !important;
  background: #ffffff;
  transition: all 0.2s ease;
}
.page-btn:hover:not(.disabled):not(.active) {
  border-color: #2563eb;
  color: #2563eb !important;
  background: #eff6ff;
}
.page-btn.active {
  background: #2563eb;
  color: #ffffff !important;
  border-color: #2563eb;
  cursor: default;
}
.page-btn.disabled {
  color: #cbd5e1 !important;
  background: #f8fafc;
  border-color: #f1f5f9;
  cursor: not-allowed;
  pointer-events: none;
}
@media (max-width: 600px) {
  .article-wrapper { padding: 24px 20px; margin: 15px; }
  .article-title { font-size: 22px; }
  .pagination-box { justify-content: center; }
}
</style>

<div class="article-wrapper">
<div class="top-nav">
<a href="./" class="btn-home">← 返回主页</a>
<span class="page-badge">第 1 页 / 共 3 页</span>
</div>

<article class="article-content">
<h1 class="article-title">这里填写你的文章主标题（第 1 页）</h1>
<div class="article-meta">发布于：CARDMVP 指南 · 阅读进度：1/3</div>

<p>这里是第一页的正文段落内容。你可以直接在这里书写文字。</p>

<h2>小标题一：核心操作步骤</h2>
<p>支持清晰的分段展示，长文章拆分为 3 页不仅能提升用户阅读体验，还能有效增加页面停留时间与内链结构。</p>
</article>

<nav class="pagination-box" aria-label="文章分页">
<span class="page-btn disabled">← 上一页</span>
<div class="page-numbers">
<a href="page1.html" class="page-btn active">1</a>
<a href="page2.html" class="page-btn">2</a>
<a href="page3.html" class="page-btn">3</a>
</div>
<a href="page2.html" class="page-btn">下一页 →</a>
</nav>
</div>

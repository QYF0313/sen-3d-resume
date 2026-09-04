---
title: 亲野自然|慧动体育 研学部 · Example Work
banner: /works/example/banner.jpg
year: 2026
role: 活动策划、社群|小红书运营维护、活动执行老师
tags: [沟通协调合作, 创造兴趣, 耐心灵活处理问题, 可跑户外场地]
link: ""
---

> **这是一个作品详情模板。** 把本文件复制成 `src/content/works/<slug>.md`，其中
> `<slug>` 要与 `src/data/works.js` 里某个作品 item 的 `slug` 一致，该作品点开后就会
> 渲染成完整详情；否则详情页显示统一占位。本文件 slug 为 `example`，不对应任何作品，
> 因此不会出现在线上——仅作参考。

## 小标题

正文支持标准 Markdown：**加粗**、*斜体*、[外链](https://example.com)，以及列表：

- 要点一 行业多品类执行经历————经历覆盖教育艺术培训（绘画、烘焙全英课）、半日|一日|多日亲子活动（麦淘、亲野、慧动领队）、大型活动（CBME会展|超级芒果音乐节志愿者组长），能学习理解不同项目的沟通话术，处理现场突发状况。
- 要点二 深度社群管理与线上运营能力————负责社群管理、活动复盘，熟悉群内活跃、信息触达和用户维护反馈；同时具备可画、简单PS、剪辑、图片制作等基本技能，高效制作招聘宣传素材。
- 要点三 责任心与时间保障————过往所有兼职/全职均获好评，会统筹物料，把控活动流程与体验

## 图片与视频

媒体放在 `public/works/<slug>/` 下，用 `/works/...` 绝对路径引用（`public/works/` 默认
不入 git，见 `.gitignore`）：

![示例配图](/works/example/1.jpg)

<video src="/works/example/demo.mp4" autoplay muted loop playsinline></video>

---

frontmatter 可用字段（均可选）：

| 字段 | 说明 |
| --- | --- |
| `title` | 详情标题（缺省回退 works.js 里的作品名） |
| `banner` | 顶部 banner 图路径（缺省用渐变占位） |
| `year` | 年份 |
| `role` | 角色 / 担当 |
| `tags` | 标签数组，如 `[互动项目, 虎啸奖]` |
| `link` | 外链，渲染成「访问作品」按钮 |

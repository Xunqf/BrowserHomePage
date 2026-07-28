# Home

简洁的浏览器起始页，支持普通模式与墨水屏模式切换。

Home：[https://xunqf.github.io/home/](https://xunqf.github.io/home/)

## 功能

- **搜索框**：默认使用百度搜索引擎，输入关键词后点击"搜索"或回车即可直达搜索结果。
- **墨水屏模式**：点击右下角 ◐ 按钮可切换至高对比度黑白样式，适配墨水屏设备。模式状态由 `localStorage` 记忆，刷新页面后保持。
- **响应式布局**：适配桌面端与移动端。
- **无障碍适配**：通过 `@media (prefers-contrast: high)` 和 `@media (monochrome)` 自动适配系统高对比度及单色模式。

## 使用方式

直接访问 [https://xunqf.github.io/home/](https://xunqf.github.io/home/)，或将其设为浏览器的默认主页或新标签页。

> 如需修改默认搜索引擎，编辑 `index.html` 中 `<form>` 的 `action` 属性即可。

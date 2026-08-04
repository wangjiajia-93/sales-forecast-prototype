---
kind: dependency_management
name: 单文件HTML原型无外部依赖管理
category: dependency_management
scope:
    - '**'
source_files:
    - sales-forecast-prototype.html
    - sales-forecast-prototype_副本.html
---

该仓库是一个纯前端高保真原型，仅包含两个独立的HTML文件（`sales-forecast-prototype.html` 和 `sales-forecast-prototype_副本.html`），没有任何第三方库或框架的依赖声明。所有样式直接内联在 `<style>` 标签中，所有交互逻辑通过原生 JavaScript 实现，未使用任何包管理器（如 npm、yarn、pnpm）、构建工具或依赖锁定文件（如 package.json、go.mod、vendor 目录）。项目完全自包含，不依赖任何外部资源，因此不存在传统意义上的依赖管理系统。
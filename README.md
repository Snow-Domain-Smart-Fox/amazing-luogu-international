<p align="center">
  <img src="https://cdn.luogu.com.cn/upload/image_hosting/oqhxzr7u.png?x-oss-process=image/circle,r_100/format,png" alt="Voicebox" width="120" height="120" />
</p>
<h1 align="center">Amazing Luogu 国际</h1>
<p align="center">新一代洛谷保存站，快速、便捷、优雅。</p>

<p align="center">
  <a href="https://github.com/Snow-Domain-Smart-Fox/amazing-luogu-international/stargazers">
    <img src="https://img.shields.io/github/stars/Snow-Domain-Smart-Fox/amazing-luogu-international?style=flat" alt="Stars" />
  </a>
  <a href="https://luogu-api.amlg.top/">
    <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fluogu-api.amlg.top&query=status&style=flat&label=status&color=orange" alt="Status" />
  </a>
  <a href="https://github.com/Snow-Domain-Smart-Fox/amazing-luogu-international/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/Snow-Domain-Smart-Fox/amazing-luogu-international?style=flat" alt="License" />
  </a>
</p>

<p align="center">
  <a href="https://luogu.amlg.top">预览</a> •
  <a href="#API 使用声明">API 使用声明</a> •
  <a href="#贡献与协作">贡献与协作</a> •
  <a href="#许可证">许可证</a> •
  <a href="#免责声明">免责声明</a> •
  <a href="鸣谢与技术">鸣谢与技术</a> •
  <a href="联系方式">联系方式</a>
</p>

<br/>

<p align="center">
  <a href="https://luogu.amlg.top">
    <img src="https://cdn.luogu.com.cn/upload/image_hosting/m0mkyil6.png" alt="Amazing Luogu 国际的截图" width="800" />
  </a>
</p>

<p align="center">
  <em>点击上方图片跳转我们的网页！！！</em>
</p>

## 项目概述

**Amazing Luogu 国际** 是一款专为洛谷设计的访问辅助工具。本项目通过 Cloudflare Workers 构建 API 反代服务与 KV 数据存储层，以及【数据删除】的数据获取 API，使用户能访问国外才能访问的内容。

> ⚠️ **声明**：Amazing Luogu 国际仅为访问辅助工具，不拥有、不运营洛谷文章区。所有文章版权归属原作者与洛谷平台，请遵守《洛谷用户协议》合理使用内容。

## API 使用声明

### 1. 接口开放策略

本项目后端 API 接口 **默认不对外开放**，仅限前端官方域名 (`https://amlg.top` 及其子域名) 内部调用。

### 2. 申请与授权

如有合法合规的第三方调用需求，可通过以下方式提交申请：
*   **申请渠道**：通过 [GitHub Issues](https://github.com/Snow-Domain-Smart-Fox/amazing-luogu-international/issues) 或项目联系方式提交书面申请；
*   **审核标准**：需明确说明使用场景、调用频率、数据用途及合规承诺；
*   **授权形式**：采用个案审批制，通过后将提供临时或长期访问凭证；
*   **费用说明**：API 借用涉及资源成本，具体费用根据调用量、服务等级及商业用途**面议**。

### 3. 使用约束
获权使用者须严格遵守以下条款：
1.  不得将接口用于任何违反《洛谷用户协议》或相关法律法规的用途；
2.  不得对接口进行高频爬取、恶意攻击或逆向工程；
3.  须在显著位置标注数据来源及本项目链接；
4.  不得二次封装，不得使用该接口创建新的面向广众的保存站；
5.  不得使用接口进行商业盈利或非盈利活动，如需商业合作请提交书面申请；
6.  项目维护方保留随时撤销授权、调整配额或终止服务的权利，恕不另行通知。

可支持最多供小团队使用的二次封装保存站。

## 贡献与协作

### 1. 本项目贡献政策
鉴于架构稳定性与授权合规性要求，**本仓库暂不接受外部 Pull Request 或直接代码贡献**。

### 2. 其他协作途径

我们欢迎开发者通过以下方式参与 Amazing Luogu 生态建设：
*   **加入其他子项目**：欢迎访问 [Snow-Domain-Smart-Fox](https://github.com/Snow-Domain-Smart-Fox) 组织，参与 Amazing Luogu 系列其他开源项目的开发；
*   **发起新项目**：欢迎基于 AGPL 协议创建与 Amazing Luogu 理念相符的新项目，并在 README 中注明生态关联；
*   **反馈与建议**：欢迎通过 Issues 提交功能建议、Bug 报告或用户体验反馈，我们将定期评估并纳入规划。

## 许可证

本项目采用 **GNU Affero General Public License v3.0** 开源协议。  
详情请参阅本项目 LICENSE 文件。

## 免责声明

```text
Amazing Luogu 国际仅为访问辅助工具，不拥有、不运营洛谷文章区。
所有文章版权归属原作者与洛谷平台，请遵守《洛谷用户协议》合理使用内容。
```

本项目开发者不对因使用本工具引发的任何版权纠纷、数据泄露或服务中断承担责任。用户应自行承担使用风险，并确保行为符合所在地法律法规及洛谷平台规范。

## 鸣谢与技术

谢谢他们带给我的方便！

| 模块               | 技术/库                                   | 说明                           |
| ----------------- | ----------------------------------------- | ------------------------------ |
| **前端框架**       | 原生 JavaScript / HTML5 / CSS3                                                 | 轻量级实现，无重型框架依赖     |
| **字体渲染**       | 霞鹜文楷（LXGW WenKai）                                                         | 中文字体，优化阅读体验     |
| **Markdown 解析**  | [marked](https://marked.js.org/)                                               | 高效解析 Markdown 内容         |
| **代码高亮**       | [highlight.js](https://highlightjs.org/)                                       | 支持多语言语法高亮             |
| **数学公式**       | [KaTeX](https://katex.org/) + auto-render                                      | 快速渲染 LaTeX 公式            |
| **图标库**         | [Font Awesome](https://fontawesome.com/) + [Iconify](https://iconify.design/)  | 矢量图标支持                   |
| **动画效果**       | [animate.css](https://animate.style/)                                          | 预设 CSS 动画类                |
| **反代服务**       | Cloudflare Workers                                                             | 无服务器 API 反代与逻辑处理    |
| **数据存储**       | Cloudflare KV                                                                  | 低延迟键值存储，用于缓存与配置 |
| **API 层**        | Python (内部使用，不对外开放)                                                     | 核心业务逻辑处理               |
| **CDN**           | [JSDMirror](https://cdn.jsdmirror.com/)                                         | 静态资源 CDN 加速              |

## 联系方式

*   **开发团队**：Snow Domain Smart Fox
*   **主负责人**：zym2013
*   **域名**：[https://amlg.top](https://amlg.top)
*   **仓库**：[https://github.com/Snow-Domain-Smart-Fox/amazing-luogu-international](https://github.com/Snow-Domain-Smart-Fox/amazing-luogu-international)

---

<p align="center">
<a href="https://github.com/zym2013"><img src="https://cdn.luogu.com.cn/upload/usericon/1393230.png?x-oss-process=image/circle,r_100/format,png" /></a><br>
<strong>zym2013</strong>
</p>

$$
\Huge \times
$$
<p align="center">
<a href="https://github.com/Snow-Domain-Smart-Fox"><img src="https://cdn.luogu.com.cn/upload/image_hosting/oqhxzr7u.png?x-oss-process=image/circle,r_100/format,png" /></a><br>
<strong>Amazing Luogu</strong>
</p>

# try_test

静态方案、配置对照和交互说明的承载仓库，按类别从首页进入。

- [导航首页](https://0xyeah.github.io/try_test/)
- [Protenix + PXDesign：三档硬件选型工具](https://0xyeah.github.io/try_test/biocomputing/protenix-pxdesign/runtime-hardware.html)
- [三档会议汇报稿](https://0xyeah.github.io/try_test/biocomputing/protenix-pxdesign/hardware-brief.html)

## 目录

```text
index.html                              分类导航
.nojekyll                               禁用 Jekyll 处理
biocomputing/protenix-pxdesign/
  runtime-hardware.html                 三档硬件选型与询租配置
  hardware-brief.html                   会议汇报稿的网页阅读版
  hardware-brief.md                     同一汇报稿的 Markdown 导出
```

## 发布与维护

直接托管 HTML / CSS / JavaScript，无需构建、服务器或数据库。GitHub Pages 使用 **Deploy from a branch → main → / (root)**；推送到 `main` 后自动发布，可在仓库的 **Actions** 或 **Settings → Pages** 查看进度和结果。

新增页面：放入对应分类目录，在 `index.html` 的导航表增加一行，再提交并推送。更新已有页面：替换对应文件，同步导航中的更新日期，再推送。站内链接使用相对路径，以适配 `/try_test/` 项目路径。

Git 仓库用于源码和历史维护，Pages 网页用于公开阅读。公开访客的导航不链接到维护仓库或 README，避免私有化后出现 404。公开网页的 HTML / CSS / JavaScript 仍可由浏览器查看，仓库私有不隐藏这些已发布文件。

发布目录只放可公开的内容。硬件页只保留三档选型、优劣和对应询租配置，不含假设资源占用模拟。汇报稿以研究仓 `doc/try_protenix/82_hardware_meeting_brief.md` 为源，网页和 Markdown 同批导出；不在两种格式里分别改正文。配置是询价目标，模型承载仍需试跑验收。

仓库设为私有不等于网页私有。个人账号需 GitHub Pro 才支持私有源仓库的 Pages；网页访问控制另有 Enterprise Cloud 组织条件，见 [GitHub 官方说明](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)。

# try_test

静态方案、配置对照和交互说明的承载仓库，按类别从首页进入。

- [导航首页](https://0xyeah.github.io/try_test/)
- [Protenix + PXDesign：运行流程与硬件方案](https://0xyeah.github.io/try_test/biocomputing/protenix-pxdesign/runtime-hardware.html)

## 目录

```text
index.html                              分类导航
.nojekyll                               禁用 Jekyll 处理
biocomputing/protenix-pxdesign/
  runtime-hardware.html                 Protenix + PXDesign 方案页面
```

## 发布与维护

直接托管 HTML / CSS / JavaScript，无需构建、服务器或数据库。GitHub Pages 使用 **Deploy from a branch → main → / (root)**；推送到 `main` 后自动发布，可在仓库的 **Actions** 或 **Settings → Pages** 查看进度和结果。

新增页面：放入对应分类目录，在 `index.html` 的导航表增加一行，再提交并推送。更新已有页面：替换对应文件，同步导航中的更新日期，再推送。站内链接使用相对路径，以适配 `/try_test/` 项目路径。

发布目录只放可公开的内容。硬件页分别列官方基准、固定版本与计划输入、未实测的任意预算；默认收起预算模拟，禁止用示例数字证明采购承载。

仓库设为私有不等于网页私有。个人账号需 GitHub Pro 才支持私有源仓库的 Pages；网页访问控制另有 Enterprise Cloud 组织条件，见 [GitHub 官方说明](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)。

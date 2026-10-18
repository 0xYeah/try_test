# try_test

公开静态方案的承载仓库，从[导航首页](https://0xyeah.github.io/try_test/)进入。

## 阅读目录

```text
index.html                              分类导航
.nojekyll                               禁用 Jekyll 处理
biocomputing/protenix-pxdesign/
  runtime-hardware.html                 三档硬件选型与询租配置
  hardware-brief.html                   三档会议汇报稿
  hardware-brief.md                     同一汇报稿的 Markdown 导出
  hardware-reference.html               官方依据与待测项
```

## 内容维护

本仓专题目录只放公开发布产物。内容在 `certa_workflow` 仓统一维护，不在这些导出文件中分别修改。

| 发布产物 | 唯一来源（相对 certa_workflow 仓根） |
| --- | --- |
| `runtime-hardware.html` | `doc/try_protenix/hardware/source/selector.html` |
| `hardware-brief.html`、`hardware-brief.md` | `doc/try_protenix/hardware/rental_options.md` |
| `hardware-reference.html` | `doc/try_protenix/hardware/README.md` |

在 `certa_workflow` 仓根执行，安装环境需具备 visualize renderer、Node.js 和 `marked`：

```sh
python3 doc/try_protenix/hardware/export_pages.py --site-dir <try_test绝对路径>
```

新增专题时更新 `index.html`；已有专题正文从上表的源文件修改后统一导出。站内链接使用相对路径。

## 发布

GitHub Pages 使用 **Deploy from a branch → main → / (root)**。检查导出文件及链接后，提交并推送到 `main`，在 **Actions** 或 **Settings → Pages** 确认发布成功。网页无需服务器或数据库。

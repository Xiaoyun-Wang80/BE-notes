# 观影之间：分享、迁移与本地运行

当前版本 0.9，2026-10-23。

## 先选交付方式

| 目的 | 交付形式 | 使用者需要做什么 |
| --- | --- | --- |
| 让朋友在电脑、平板或手机上使用 | 已部署的网站链接 | 获得访问权限，打开浏览器，导入自己的片单 |
| 自己维护代码、换域名或换托管平台 | 源码仓库 + 独立管理的有授权片库和图像 | 准备数据，部署静态文件 |
| 在自己的电脑上运行 | 完整静态目录 + 本地 HTTP 服务 | 启动服务，再打开 localhost |
| 双击安装并像桌面软件使用 | 另行制作的桌面安装包 | 安装对应操作系统版本；当前尚未制作 |

目前的网站地址：<https://film-atlas-journal.aglowox1.chatgpt.site>。当前分享范围保持原设置，网址本身不会自动给新访客授权。要邀请新朋友，应在网站的分享设置中授予访问权限。

## GitHub 仓库与“编译”是什么关系

GitHub 仓库保存源码、版本历史和开发说明；它本身不会把网站变成应用程序。GitHub Pages 从仓库发布静态网站，也可以由自动化流程发布。

本项目直接使用 HTML、CSS 和 JavaScript ES 模块，没有 npm 构建依赖，不需要先编译成某种“GitHub 库类型的包”。实际网页入口是 `dist/index.html`，全部运行文件在 `dist/` 中。

仅保存浏览器“网页另存为”得到的 HTML 不够：程序还会读取模块、压缩片库、检索 Worker 与本地图像。迁移时需保留这些文件及其相对路径。

## 源码和数据分开处理

公开仓库或可转发的 ZIP 应先检查第三方资料的再分发授权。当前数据并非全部采用开放再分发许可证：IMDb 非商业数据条款只允许限定的个人非商业用途，禁止据此再发布影视数据库（个人自用例外）。不能把现有片库直接上传成公开 GitHub 数据仓库。

项目代码可整理为独立源码交付；片库、数据证据与图像应逐源核对，使用允许目标用途的来源或取得所需授权。相关文件包括 `dist/data/`、`dist/catalog.mjs`、`dist/film-readings.mjs`、`dist/visuals.mjs`、`dist/assets/` 及来源审计文件，不能只排除一个 IMDb 文件就视为完成。

运行时数据应包含匹配的清单、核心详情、推荐补充片库和全部检索分片。改变数据后应重新生成 `catalog-manifest.json`，核对数量、字节数与 SHA256。缺失片库时网站会提示加载失败，不能把无片库源码包称为可完整使用的离线版。

## 部署到 GitHub Pages

以下步骤以已经准备好可公开发布的代码、片库和图像为前提：

1. 建立新的 GitHub 仓库，把准备好的 `dist/` **里面的内容**放到仓库根目录，让根目录直接出现 `index.html`，同时保留 `data/`、`assets/` 和所有 `.mjs` 文件。不要上传 `.git`、原网站的身份配置、访问凭据或个人观影备份。
2. 在根目录放一个空的 `.nojekyll` 文件，按普通静态文件发布。
3. 在仓库中打开 `Settings → Pages → Build and deployment`，来源选择 `Deploy from a branch`，选择实际上传的分支，目录选择 `/(root)`，保存。
4. 等部署完成，使用 GitHub 返回的网站地址。仓库代码页地址不是使用网站的地址。
5. 用另一台设备验证：导入独立片单、生成画像、得到五部未看推荐、点击“否”仅替换一部、点击“是”展开简介，再导出和恢复个人备份。

也可以保留源码仓库的 `dist/` 结构，使用 GitHub Actions 上传 `dist/` 作为 Pages 部署产物。普通分支发布的目录选择为根目录或 `/docs`，不能直接在该下拉框里选择 `/dist`。

## 本地运行

个人自用且已备有完整文件时，在项目目录中打开终端；需要已安装 Python 3：

```bash
python3 -m http.server 8000 --bind 127.0.0.1 --directory dist
```

Windows 的 Python 启动器可使用：

```powershell
py -3 -m http.server 8000 --bind 127.0.0.1 --directory dist
```

再在同一台电脑的浏览器中打开 <http://localhost:8000>。保持终端运行；按 `Ctrl+C` 停止。本地静态服务器用于本机使用，正式在线分享采用静态托管。

不能直接双击 `index.html`：`file://` 下的模块、数据请求和 Worker 会受浏览器限制。当前也没有 Service Worker 离线缓存，浏览器“添加到主屏幕”不会使整个片库自动离线。完整本地文件通过 localhost 可进行片单分析和已有片库推荐；额外在线补全与外部作品链接仍需要网络。

## 每个人的片单在哪里

导入记录、评分、画像反馈和推荐历史保存在各自浏览器的本地存储里；网站文件不会包含你当前浏览器中的私人片单。当前没有账号同步。换设备、换浏览器或换网站地址时，先用“导出备份”保存 JSON，再在新位置导入。

## 官方参考

- [GitHub Pages 是什么](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)
- [GitHub Pages 发布来源设置](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [Python 本地 HTTP 服务](https://docs.python.org/3/library/http.server.html)
- [IMDb 数据使用范围](https://help.imdb.com/article/imdb/general-information/can-i-use-imdb-data-in-my-software/G5JTRESSHJBBHTGX)

本轮已更新网站并整理上述迁移说明；尚未创建 GitHub 仓库、公开站点副本或桌面安装包。

# wenhaozhang0066.github.io — 个人学术主页

个人网站源码。目前仓库为 **Private（未发布）**，改完内容后按下面第 3 步发布。

## 文件结构

| 文件 | 作用 |
|---|---|
| `index.html` | 主页：简介 / News / 教育经历 / 获奖 / 兴趣爱好 |
| `publications.html` | 研究项目 / 论文 / 专利 |
| `style.css` | 全站样式（两个页面共用） |
| `photo.jpg` | 个人照片 |
| `renet.png` `brainage.png` `ldan.png` `pedmix.png` | 研究项目配图 |

## 怎么改内容

直接在 GitHub 网页上点开对应文件 → 右上角铅笔图标 ✏️ → 改完 Commit changes。
常改的位置都在 `index.html`：研究方向在第一段 `bio`，News 加一行 `<li>`，爱好在 `Beyond Research` 一节。
Google Scholar / LinkedIn 链接：搜 `取消注释`，按提示打开即可。

## 怎么发布上线

1. 仓库 **Settings → General → 拉到最底部 Danger Zone → Change visibility → Public**
2. 等 1–2 分钟，网站自动发布到 <https://wenhaozhang0066.github.io>
3. 给旧网站挂跳转：在旧账号 `uiokky5` 的 `wenhao2` 仓库根目录新建 `index.html`，内容如下：

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>Redirecting to wenhaozhang0066.github.io</title>
<link rel="canonical" href="https://wenhaozhang0066.github.io/">
<meta http-equiv="refresh" content="0; url=https://wenhaozhang0066.github.io/">
<script>location.replace("https://wenhaozhang0066.github.io/");</script>
</head>
<body>
<p>This page has moved to <a href="https://wenhaozhang0066.github.io/">wenhaozhang0066.github.io</a>.</p>
</body>
</html>
```

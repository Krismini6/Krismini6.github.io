# 个人主页

用 HTML + CSS 写的个人主页 / 在线简历，通过 GitHub Pages 托管。

在线地址：https://krismini6.github.io

## 本地预览

双击 `index.html` 就能看。改完保存，刷新浏览器即可，不需要重启任何东西。

## 要改的地方

打开 `index.html`，搜索 `【` 这个符号，把带方括号的占位内容一个个替换掉。
GitHub 用户名已经填好了，其余（姓名、学校、项目经历）需要你自己补。

## 常用 Git 命令

```bash
git status              # 看看改了哪些文件
git add .               # 把改动放进暂存区
git commit -m "说明"     # 存一个版本快照
git push                # 推到 GitHub（这一步才联网）
```

改完文件后，跑一遍这四条，网页大约一分钟后更新。

## 为什么是 `git add` 和 `git commit` 两步

`add` 决定"这次要存哪些改动"，`commit` 决定"存成一个版本"。
分开是为了让你能一次只提交相关的改动，而不是把一堆无关修改糊在一起。

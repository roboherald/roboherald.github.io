# 发布个人主页

目标仓库：`roboherald/roboherald.github.io`

目标网址：<https://roboherald.github.io/>

已有项目网站 <https://roboherald.github.io/embodied-ai-chronicle/> 属于另一个仓库，可以与个人主页同时存在，无需改动它的发布配置。

## 1. 在 GitHub 创建 Fork

打开 <https://github.com/yuyuyu223/howsenfisher.github.io/fork>：

- Owner：`roboherald`
- Repository name：`roboherald.github.io`
- 保留 `main` 分支即可。

若已经创建该 Fork，直接进入下一步。

## 2. 提交本地修改

当前本地目录仍叫 `personal/howsenfisher.github.io`；文件夹名不影响发布网址。

本地 `upstream` 指向师兄仓库，`origin` 指向你的目标仓库。先检查：

```bash
git remote -v
git diff --stat
git diff -- _config.yml _pages/about.md
```

确认页面内容后提交并推送（需要在本机完成 GitHub 身份验证）：

```bash
git add -A
git commit -m "Personalize homepage for Yunhao Hou"
git push -u origin main
```

如果远端已有后续提交，先获取并检查差异，不要强制推送覆盖它们。

## 3. 启用 GitHub Pages

1. 在你的仓库中打开 **Settings → Pages**。
2. 在 **Build and deployment → Source** 中选择 **GitHub Actions**。
3. 如果 Fork 的 Actions 尚未启用，进入 **Actions**，启用工作流。
4. 打开 **Deploy personal homepage**，选择 **Run workflow → main → Run workflow**。
5. 工作流成功后访问 <https://roboherald.github.io/>。

之后每次推送到 `main` 都会自动更新主页。若工作流报 Pages 未启用，先完成第 2 步，再重新运行。

## 后续常见修改

- 头像：替换 `images/avatar.png`。
- 个人介绍和成果：编辑 `_pages/about.md`。
- 邮箱、Google Scholar、ORCID：编辑 `_config.yml`，没有的字段可以留空。
- Google Scholar 引用爬虫默认停用，不影响主页展示和发布。
- 原始简历 PDF 未加入发布目录；当前页面只提供已发表论文的 PDF 下载。

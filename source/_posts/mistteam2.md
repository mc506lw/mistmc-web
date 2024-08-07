---
title: 如何在岚域官网更新文章
date: 2024-06-25 10:40:23
categories: 
- 教程
cover: https://s21.ax1x.com/2024/08/09/pkz7cLR.png
---

# 如何在岚域官网更新文章

## 前提条件

1. 已安装Node.js（版本要求：>= 10.0）
2. 已安装Hexo（版本要求：>= 4.0）
3. 已克隆岚域官网的项目

## 完成前提后的步骤

### 1. 创建新文章

在Hexo项目目录下，使用以下命令创建新文章：

```bash
hexo new post 文章ID【英文】
```

这将会在`source/_posts`目录下生成一个新的Markdown文件。你可以在该文件中编辑你的文章内容。

### 4. 编辑文章

使用你喜欢的文本编辑器打开新生成的Markdown文件，并编辑你的文章内容。例如：

```markdown
---
title: 你的文章标题
date: 2024-06-25 02:32:46
categories: 
- 教程
---

这里是你的文章内容。
```

解释：
title: 自己的标题
date: 日期 默认即可
categories: 可选的标签是 教程 更新 活动
cover: 头图&缩略图，用图床直链

### 5. 预览文章

在本地预览你的文章，确保内容和格式正确。使用以下命令启动本地服务器：

```bash
hexo g & hexo s
```

在浏览器中打开`http://localhost:4000`，查看你的文章。

### 6. 部署文章

在github desktop中，进行上传。
---
title: Hexo初接触
---

### 彩带背景(自定义背景)

修改`\themes\next\layout\_layout.swig`页面模板

- 在`/themes/next/source/css`和`/themes/next/source/js/src`下添加css,js文件
- 添加css `<link href="/css/canvas_ribbon.css" rel="stylesheet" type="text/css">`
- body中添加canvas `<canvas class="canvas_ribbon" ></canvas>`
- 添加js `<script type="text/javascript" src="http://localhost:4000/js/src/canvas_ribbon.js"></script>`(ps: 必须在body末尾)

### 设置中文Language(修改主题`/themes/hexo-theme-next/_config.yml`)

```
gitment:
	...
  language: zh-CN #可选择./languages 下的任意语言
```

### 设置头像(修改`/themes/hexo-theme-next/_config.yml`)

```
avatar: 
  # in theme directory(source/images): /images/avatar.gif
  # in site  directory(source/uploads): /uploads/avatar.gif
  # You can also use other linking images.
  url: /images/avatar.png # 图片路径
  # If true, the avatar would be dispalyed in circle.
  rounded: false
  # The value of opacity should be choose from 0 to 1 to set the opacity of the avatar.
  opacity: 1
  # If true, the avatar would be rotated with the cursor.
  rotated: false
```

### 侧边栏关联小图标(修改主题`/themes/hexo-theme-next/_config.yml`)
```
social:
	# 名称: 链接 || [对应图标库的名称](https://fontawesome.com/icons)
  GitHub: https://github.com/wangfengye || github
```

[参考链接](https://blog.csdn.net/qq_32454537/article/details/79482896)
# 个人博客模板

一个美观的静态个人博客模板，使用HTML和CSS构建。

## 功能特点

- 现代美观的设计
- 响应式布局，适配不同屏幕尺寸
- 平滑的动画效果
- 完整的导航系统
- 文章列表展示
- 关于我页面
- 联系表单
- 社交媒体链接

## 如何部署到GitHub Pages

### 步骤1：创建GitHub仓库

1. 登录你的GitHub账号
2. 点击右上角的「+」按钮，选择「New repository」
3. 输入仓库名称（例如：`username.github.io`，其中`username`是你的GitHub用户名）
4. 选择「Public」公开仓库
5. 点击「Create repository」按钮

### 步骤2：初始化Git仓库并上传文件

1. 在本地项目目录中打开命令行/终端
2. 初始化Git仓库：
   ```bash
   git init
   ```
3. 添加所有文件：
   ```bash
   git add .
   ```
4. 提交更改：
   ```bash
   git commit -m "Initial commit"
   ```
5. 关联到GitHub仓库：
   ```bash
   git remote add origin https://github.com/username/username.github.io.git
   ```
6. 推送到GitHub：
   ```bash
   git push -u origin main
   ```

### 步骤3：启用GitHub Pages

1. 进入你的GitHub仓库页面
2. 点击「Settings」选项卡
3. 滚动到「GitHub Pages」部分
4. 在「Source」下拉菜单中选择「main」分支
5. 点击「Save」按钮
6. 稍等片刻，你的博客就会在 `https://username.github.io` 上线

## 自定义内容

### 修改文章内容

编辑 `index.html` 文件，修改文章的标题、内容和图片。

### 修改个人信息

编辑 `about.html` 文件，更新个人简介、技能和联系方式。

### 修改样式

编辑 `style.css` 文件，调整颜色、字体和布局。

### 添加更多文章

在 `index.html` 文件中，复制现有的文章结构，修改内容即可添加新文章。

## 技术栈

- HTML5
- CSS3
- Font Awesome（图标）

## 响应式设计

- 桌面端：三栏布局
- 平板端：两栏布局
- 移动端：单栏布局，带有汉堡菜单

## 许可证

MIT License
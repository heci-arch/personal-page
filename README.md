# 算法基础个人主页

这是“算法基础”课程大作业个人主页静态网站，包含首页和第一篇技术博客。

## 文件结构

```text
index.html   # 个人主页
blog.html    # 第一篇技术博客
style.css    # 全站视觉样式
script.js    # 导航、滚动动画、移动端菜单
README.md    # 运行与部署说明
```

## 本地运行

方式一：直接双击 `index.html` 打开。

方式二：在当前目录启动本地服务器：

```bash
python -m http.server 8000
```

然后访问：

```text
http://localhost:8000/
```

## 部署建议

可以部署到 GitHub Pages、Vercel 或 Netlify。静态网站不需要后端服务，上传这些文件即可。

GitHub Pages 简要流程：

1. 新建 GitHub 仓库；
2. 上传 `index.html`、`blog.html`、`style.css`、`script.js` 和 `README.md`；
3. 在仓库 Settings 中开启 Pages；
4. 将生成的网址填写到作业报告中。

## 需要替换的信息

- `你的姓名`
- `your.email@example.com`
- `https://github.com/your-github`
- 项目卡片中的真实项目链接
- 博客中的个人表达和真实实现细节
- 部署后的主页网址

## 已实现功能

- 蓝色科技感个人主页；
- 固定导航栏和平滑滚动；
- About、Projects、Learning Notes、Blog、Contact 区域；
- 首页博客入口，可跳转到 `blog.html`；
- 第一篇完整技术博客；
- 卡片 hover、按钮 hover、技能标签 hover；
- 滚动淡入动画；
- 移动端响应式导航。

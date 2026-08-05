北斗注册测速【Q-——333307——】北斗注册测速【 辋芷《888yx●vip》 】
北斗注册测速【Q-——333307——】北斗注册测速【 辋芷《888yx●vip》 】

 从0到1搭建个人博客：GitHub Pages + Hexo 完整指南（小白友好）

> 你是否想过拥有一个完全属于自己的博客？无需购买服务器，无需备案，甚至不用花一分钱——GitHub Pages + Hexo 就能帮你实现。本文将手把手教你从零开始，搭建一个高速、稳定、可定制的个人博客。

 为什么选择 GitHub Pages + Hexo？

在众多博客方案中，这对组合是免费、轻量、高效的佼佼者。GitHub Pages 提供无限流量和全球 CDN 加速，而 Hexo 作为 Node.js 驱动的静态博客框架，秒级生成页面，对 SEO 极其友好。更重要的是，你拥有完全的控制权，数据永不丢失。

 环境准备：三分钟搞定基础工具

在开始之前，请确保电脑已安装：

1. Node.js（建议 LTS 版本）——访问官网下载安装包，一路 Next 即可
2. Git——用于代码版本管理和推送
3. GitHub 账号——用于托管博客源码和页面

小贴士：Windows 用户建议使用 PowerShell 或 Cmder 作为终端工具，体验更佳。

 安装 Hexo 并初始化项目

打开终端，依次执行以下命令：

```bash
 全局安装 Hexo 命令行工具
npm install -g hexo-cli

 初始化博客项目（blog 可替换为你的项目名）
hexo init blog
cd blog

 安装依赖包
npm install

 本地预览：启动服务后访问 http://localhost:4000
hexo s
```

看到默认的 Hello World 页面，恭喜你，本地博客已经跑起来了！

 部署到 GitHub Pages：让你的博客上线

第一步：创建 GitHub 仓库

登录 GitHub，新建仓库，仓库名格式必须为 `你的用户名.github.io`（例如 `john.github.io`），选择 Public。

第二步：安装部署插件并配置

```bash
npm install hexo-deployer-git --save
```

然后修改 `_config.yml` 文件，在末尾添加：

```yaml
deploy:
  type: git
  repository: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

第三步：一键部署

```bash
hexo clean && hexo generate && hexo deploy
```

等待几秒钟，浏览器访问 `https://你的用户名.github.io`，你的博客已经面向全世界开放了！

 进阶优化：让博客更好看、更好被收录

- 更换主题：Hexo 官网有上百款主题，推荐 Next、Fluid、Volantis。下载后放入 `themes` 目录，修改 `_config.yml` 中的 `theme: 主题名` 即可
- SEO 优化：安装 `hexo-generator-seo-friendly-sitemap` 生成站点地图，并在 Google Search Console 中提交，加速收录
- 自定义域名：购买域名后在仓库 Settings → Pages 中绑定，记得添加 CNAME 记录

 遇到问题？这份排查指南请收好

| 问题现象 | 解决方法 |
|---------|---------|
| `hexo d` 报权限错误 | 检查是否配置了 SSH Key，或改用 HTTPS 方式 |
| 页面样式丢失 | 执行 `hexo clean` 后重新生成 |
| 部署后 404 | 确认仓库名和用户名完全一致，且分支为 main |

---

互动时间：你在搭建博客时遇到过什么奇葩问题？欢迎在评论区留言，我们一起解决！如果这篇文章对你有帮助，记得点赞 👍 和收藏 ⭐，让更多朋友看到～

持续更新：关注我，获取更多 GitHub 实战技巧、前端开发干货。你的支持是我创作的最大动力！

相关推荐：

https://github.com/francocrystal17/jearfg/blob/main/Th%E1%BB%83%20thao%20%E2%9A%BD%EF%B8%8F%EF%BC%9A%E5%8C%97%E6%96%97%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E6%B0%96%E5%B3%AD%E8%A4%82%E7%BA%A6%E6%9C%B4eklex.md

<img src="https://i.postimg.cc/4dPpdw0z/beidou-00010.png" />

相关推荐：

https://github.com/francocrystal17/jearfg/commit/73287e02fcf299a1a104065ff6e6be0446e5c41d

<img src="https://i.postimg.cc/vHNLfqmd/beidou-00006.png" />
相关推荐：

https://github.com/smithaudrey570/cicarv/blob/main/Th%E1%BB%83%20thao%20%E2%9A%BD%EF%B8%8F%EF%BC%9A%E5%8C%97%E6%96%97%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%91%E7%8B%88%E8%82%9B%E4%BB%AC%E8%A7%88ibpjj.md

<img src="https://i.postimg.cc/Z5vPc89T/beidou-00007.png" />
相关推荐：

https://github.com/smithaudrey570/cicarv/commit/a984e0c57fc8e98a254e9ec9e878edf21038ea5d

<img src="https://i.postimg.cc/SxYLr6X9/beidou-00008.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。

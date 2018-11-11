# Hexo Blog Backup

## 简介
Hexo主题来源于[litten/hexo-theme-yilia](https://github.com/litten/hexo-theme-yilia)，这是个非常精美的主题

## 修改
1. 针对博客评论系统Gitment一些过时API和Css样式改进
2. 文章图片资源统一使用hexo-asset-image插件进行管理，hexo博客根目录下运行 `npm install hexo-asset-image --save` 
3. 公共或主题所需资源一律放入 **public/assets/** 中，示例：[horacework.github.io/assets/](https://github.com/horacework/horacework.github.io/tree/master/assets)
4. 更新微信二维码分享API
5. 删除一些不必要的分享按钮

## 部署

1. 安装Git、NodeJS；
2. 使用npm安装hexo(全局安装)；

```bash
    $ npm install -g hexo-cli
```

3. 创建并初始化hexo文件夹
```bash
    $ hexo i blogDir  //init，blogDir是文件夹名称
```
4. 把本项目直接下载下来，替换到blogDir里面去；

5. 注意公共或主题所需资源一律放入 **public/assets/** 中，示例：[horacework.github.io/assets/](https://github.com/horacework/horacework.github.io/tree/master/assets)

6. 常用操作
```bash
    $ hexo g    //generetor，写完md文章后，使用该命令生成并更新静态文件
    $ hexo d    //deploy，一键部署到githubIO，这需要修改_config.yml文件中deploy属性
    $ hexo s    //server，默认部署到本地4000端口方便调试
```

***
Horace Chan

2018.11.10

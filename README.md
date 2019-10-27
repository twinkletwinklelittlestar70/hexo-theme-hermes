![hexo-theme-hermes](https://cloud.githubusercontent.com/assets/9530963/13026956/08e76eca-d277-11e5-8bfc-2e80cea20a0d.png)

## 文档

- [中文文档](https://github.com/claymcleod/hexo-theme-hermes/blob/master/doc%2Fdoc-zh.md)
- [Document](https://github.com/claymcleod/hexo-theme-hermes/blob/master/doc%2Fdoc-en.md)

## 贡献

该项目不再接受添加新特性、功能的 pull request，所有创造性的想法请 fork 该项目之后自由发挥。

## 安装

``` bash
hexo init Blog 
cd Blog 
npm install
npm install --save hexo-renderer-pug hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
git clone https://github.com/claymcleod/hexo-theme-hermes.git themes/hermes
```

## 启用

修改 `_config.yml` 的 `theme` 配置项为 `hermes`:

```yaml
theme: hermes

# 在归档页面显示所有文章
# 需要上面安装的 hexo-generator-archive 插件支持
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## 更新

``` bash
cd themes/hermes 
git pull
```

## License

MIT

## Gatsby Theme

如果你正在使用 Gatsbyjs 建站，欢迎使用专为 Gatsbyjs 开发的主题 [gatsby-theme-wink](https://github.com/pinggod/gatsby-theme-wink) 😘

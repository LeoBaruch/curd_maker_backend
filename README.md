# LeoBaruch.github.io
my blog

## 使用

### 安装依赖

```
// node >= 16
pnpm i

```

### 本地预览

```
npm run server

```

### 发布新post


```
hexo new [layout] <title>

```

新建一篇文章。如果没有设置 **layout** 的话，默认使用 _config.yml 中的 default_layout 参数代替。如果标题包含空格的话，请使用引号括起来。因为没有全局安装hexo,
在这里使用pnpm, 如下:

```
// 发布新文章(省略布局)
pnpm hexo new new-post 

// 发布新文章 
pnpm hexo new post new-post 

// 新草稿
pnpm hexo new draft new-drafted-post (部署不展示, 需要publish部署才会展示)

```

发布

```
npm run deploy

```







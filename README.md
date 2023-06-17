# 关于

- 使用`stack`主题
- 从[stack模板]()创建
- 使用`github action`部署

# 如何使用

- 下载仓库

```bash
git clone --recursive https://github.com/QuietSugar/xu-stack-blog.git
```
- 如果忘记加`recursive`

> 手动更新
```
git submodule update --init --recursive

```

# 启动

> disableFastRender 禁用快速渲染,每次都完全渲染
> navigateToChanged 更改某一个文件的时候,在浏览器中导航到这个文件


``` bash

# 开发环境
hugo server --disableFastRender --navigateToChanged --bind 0.0.0.0
# 正式环境
hugo server --disableFastRender --navigateToChanged --environment production --bind 0.0.0.0

# 在云环境中启动
hugo server --baseURL  https://c424c2cf-66db-4b51-a986-8db615d80ba6-1313-public.devstudio.aliyuncs.com/ --bind 0.0.0.0  --appendPort=false

# 创建页面

hugo new posts/my-first-post.md

```



# 手动更新主题

Run:

```bash
hugo mod get -u github.com/CaiJimmy/hugo-theme-stack/v3
hugo mod tidy
```



# 其他优秀的主题

- 文档风

[hugo-theme-relearn](https://github.com/McShelby/hugo-theme-relearn)

- 轻松-卡通-图标多

[PaperMod](https://www.sulvblog.cn/posts/blog/)

- 素色-文字

[Eureka](https://www.wangchucheng.com/zh/docs/hugo-eureka/)

- 丑-文档详细

[fixit](https://fixit.lruihao.cn/zh-cn/documentation/basics/)
[]()
[]()
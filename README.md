# NyaNest-Website

猫窝 NyaNest 官网。 || Powered by VitePress

![VitePress_Banner](https://api.ymbit.cn/images/nyanest/vitepress_banner.png)

## Develop
此项目使用 [Bun](https://bun.sh) 创建 [VitePress](https://vitepress.dev)，请先安装 Bun。

安装依赖项：
```bash
bun install
```
开发模式运行VitePress：
```bash
bun run dev:docs
```
投入开发环境：
### 此处仅笼统描述，具体请查看 VitePress 官方编译文档。链接：<https://vitepress.dev/zh/guide/deploy>。
编译：
```bash
bun run docs:build
```
存放的文件将会在`/init/.vitepress/dist`中。
## Cloudflare Pages
框架预设：无<br>
构建命令：`bun run docs:build`<br>
部署输出目录：`/init/.vitepress/dist`

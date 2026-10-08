# Project Demo

视频作品展示页，使用仓库根目录中的原始 MP4 文件。

网站地址（启用 GitHub Pages 后生效）：https://yefanh940-cmyk.github.io/short_drama_demo/

## 启用 GitHub Pages

打开仓库 Settings → Pages：
- Source：Deploy from a branch
- Branch：main
- Folder：/ (root)
- 点击 Save，等待发布完成。

## 页面功能

- 六个视频在线播放，支持浏览器原生全屏与音量控制
- 按文件名前缀 SD、BC、LIVE、MUSIC 筛选
- 播放新视频时自动暂停其他视频
- 适配手机与桌面屏幕
- 原视频直达链接与加载失败提示

## 更新视频

替换同名 MP4 文件即可更新视频。新增视频时，在 index.html 中复制一张 article.card，修改标题、data-category 和两个视频链接；如新增分类，再添加筛选按钮。页面不需要安装依赖或运行构建。

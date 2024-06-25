# blog-site

## 注意事项

在阿里云 Linux 云服务器上安装 `hexo-word-counter` 时，可能会出现缺少 `index.node` 文件的情况，这会导致项目启动异常。

暂未找到问题原因，可能按照如下步骤操作，能安装正常： 
1. 执行 `npm uninstall hexo-word-counter` 将其卸载。
2. 执行 `hexo server` 启动服务，访问页面，会发现项目由于缺少这个插件而报错。
3. 再重新执行 `npm install hexo-word-counter` 可能可以安装成功 (如果不行，再多试几次)。
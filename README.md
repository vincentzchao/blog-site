# blog-site

## 注意事项

`hexo-word-counter` 在安装时可能会缺少 `index.node` 文件，这会导致异常。
暂未找到原因，可能是需要这样操作： 
1. 执行 `npm uninstall hexo-word-counter` 将其卸载。
2. 执行 `hexo server` 启动服务。
3. 访问页面，会发现由于缺少这个插件会报错，再重新执行 `npm install hexo-word-counter` 可能就能安装成功了。
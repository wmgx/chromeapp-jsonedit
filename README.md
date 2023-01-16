# 简约好用的json编辑chrome插件

## 简介
基于 [sunzsh/chromeapp-jsonedit](https://github.com/sunzsh/chromeapp-jsonedit) 的思路，在使用过程中遇到了js的大数问题，替换底层组件成
[josdejong/svelte-jsoneditor](https://github.com/josdejong/svelte-jsoneditor)



## 使用方法
> 由于chrome目前已经不支持app类型的插件上架应用商店了，所以只能下载源码后自己安装了（很简单）

1. 下载源码
2. 在chrome中打开 `chrome://extensions`
3. 右上角找到并开启“开发者模式”
4. 将源码的根目录拖拽到chrome中（安装成功）
5. 在chrome中打开 `chrome://apps` ，找到“JsonEditor” 单击打开
6. 打开url中可以追加 `?clipboard` 自动加载剪切板里的json
7. \[可选\] 方便以后进入，建议打开后，添加到收藏夹
8. \[可选\] 可以配合安装 [alfred插件](https://github.com/sunzsh/favoritesWorkflow4Alfred/blob/main/jsonEditor.alfredworkflow) 快速打开（支持按住command自动加载剪切板内json）(感谢[sunzsh](https://github.com/sunzsh) 大佬的插件，替换chrome插件即可)

## 特别鸣谢
* [chromeapp-jsoneditor](https://github.com/josdejong)  开源的 [josdejong/svelte-jsoneditor](https://github.com/josdejong/svelte-jsoneditor)
* [sunzsh](https://github.com/sunzsh) 提供的思路

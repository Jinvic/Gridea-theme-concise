# Gridea-theme-clean
是一款免费的Gridea主题，在[Alanrk的Gridea-theme-clean](https://github.com/Alanrk/Gridea-theme-clean) 

>本Theme在Clean的基础上进行魔改，虽偏离了其主题本意，但使用上方便不少；

## 修改内容
    1. 主题-自定义配置-增加Valine评论配置
    2. 主题-自定义配置-增加'关于页面'
    3. 主题-自定义配置-增加live2d看板娘配置
    4. 文章内增加目录索引
    5. 增加封面图显示
    6. 添加模糊搜索
 
## 说明
### 1. live2d
参考了：[gridea-theme-fog](https://github.com/850552586/gridea-theme-fog)
- 模型下载地址: [下载地址](https://gitee.com/ericam/live2d-widget-models)
- 模型样式预览: [预览地址](https://blog.csdn.net/wang_123_zy/article/details/87181892)
- 如想修改，有2种方式，最后修改live2d.ejs里引用的model.json即可：
  - 修改：可直接覆盖live2d/assets直接修改，
  - 添加：按照目前结构继续添加（要修改下载下来的目录文件结构，及对应的model.json里相关path）

### 2. ’关于‘页面
需在Gridea客户端-菜单-关于中，将其路径改为'/about'


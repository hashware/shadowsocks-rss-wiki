- SSR全称是什么？  
正确为`ShadowsocksR`，有人称之为Shadowsocks-rss是错误的，rss是Really Simple Syndication的缩写

- 服务端混淆参数需要和客户端一样吗？  
不需要，服务端的参数含义完全不一样，建议详细阅读说明，且在多用户模式下，其参数不应由用户自定义，应该由管理员预设好

- 如何清空客户端统计的总流量？  
关闭客户端后删除目录下的`transfer_log.json`再重新打开

- 客户端任务栏图标有什么快捷操作？  
左键点击弹出服务器编辑窗口，中键点击弹出服务器统计窗口，右键弹出菜单，shift+左键弹出选项设置窗口

- 客户端任务栏图标颜色有什么含义？  
关闭系统代理时为蓝色，PAC模式时绿色，全局时青色，开启负载均衡时在前面的颜色里加上红色
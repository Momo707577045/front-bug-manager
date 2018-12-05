# 项目详细介绍请[点击这里](https://segmentfault.com/a/1190000017271720)查看

# bug管理系统配置说明
- av.js是leadCloud插件。
- VUE.js就是VUE库。
- bug-list.html是数据列表页面。
- bug-detail.html是详情页面。
- 修改bug-list.html及bug-detail.html页面中的LeanCloud配置，同样找到AV.init，填入「App ID」和「App Key」。
- 将这四个文件放进静态服务器，直接访问bug-list对应链接。即可看到上报的数据列表，点击详情可查看某条数据的详情信息

  ![使用配图](http://momo-project.b0.upaiyun.com/Assets/bugSystem/imgs/002.png)
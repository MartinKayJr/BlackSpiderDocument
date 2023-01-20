# BlackSpiderDocument
Android动态分析工具(黑蜘蛛)

工具演示视频：https://www.bilibili.com/video/BV1vy4y1R7Dc/?spm_id_from=333.999.list.card_archive.click


反射大师的后续维护将由BlackSpider完成。

1.对反射功能做特向优化，以便快速定位 组件。
2.多数APP都由Fragment完成页面开发，因此对Fragment做特向优化分析。
3.对image组件做查看视图按钮(VIEW)
4.增加对activity的所有函数调用监听(需要开启悬浮窗)


正在实现（详细点击issues查看）：
完成弹出窗口最小化功能 #1
完成对ListView与RecyclerView的定位 #2
增加细粒度的功能控制 #3
支持自定义HOOK #4
支持对变量进行插件化功能 #5
自动捕获按钮点击事件 #6

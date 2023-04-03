# BlackSpiderDocument

Android动态分析工具(黑蜘蛛)

工具演示视频：https://www.bilibili.com/video/BV1vy4y1R7Dc/?spm_id_from=333.999.list.card_archive.click

反射大师的后续维护将由BlackSpider完成。

- [x] 对反射功能做特向优化，以便快速定位 组件。
- [x] 多数APP都由Fragment完成页面开发，因此对Fragment做特向优化分析。
- [x] 对image组件做查看视图按钮(VIEW)
- [x] 增加对activity的所有函数调用监听(需要开启悬浮窗)

v1.1版本增加：  
- [x] 支持多个Frida脚本的执行。
- [x] 内置IDE编辑器让你更好的完成脚本的编写。


正在实现（详细点击issues查看）
- [ ] 完成弹出窗口最小化功能 https://github.com/MartinKayJr/BlackSpiderDocument/issues/1
- [ ] 完成对ListView与RecyclerView的定位 https://github.com/MartinKayJr/BlackSpiderDocument/issues/2
- [ ] 增加细粒度的功能控制 https://github.com/MartinKayJr/BlackSpiderDocument/issues/3
- [ ] 支持自定义HOOK https://github.com/MartinKayJr/BlackSpiderDocument/issues/4
- [ ] 支持对变量进行插件化功能 https://github.com/MartinKayJr/BlackSpiderDocument/issues/5
- [ ] 自动捕获按钮点击事件 https://github.com/MartinKayJr/BlackSpiderDocument/issues/6

v1.2版本未来拓展(调试台)
- [ ] 调试台监视器功能(干涉内容)
- [ ] 调试台表达式评估功能(计算内容)
- [ ] 调试台堆栈跟踪功能、异步跟踪功能(跟踪内容)
- [ ] 调试台控制台功能(插桩日志)

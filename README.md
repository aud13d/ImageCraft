#更新日志：

2024-6-18：添加了：整个菜单页，及基本的自定义菜单和菜单整理

2024-6-19：添加了：工具栏，修改了文件结构

2024-6-20上午：合并并添加项目周开始之前协同开发的c++与qml结合部分，本次更新后项目周正式项目与之前开发项目的进度追平，进入正式开发阶段，主要内容包括：
构建文件改为cmake,qml端添加EditorView、dialog等，c++端添加单例ActiveCtrl,ToolCtrl,类Editor，imageprovider.
2024-6-20下午：修改了保存、保存为的逻辑结构，添加了导出功能，图片格式转换；关闭图片、关闭全部、刷新、截取当前屏幕，吸管。

2024-6-21 添加了画笔工具，放大缩小工具，优化了图片展示和关闭的处理逻辑

2024-6-22 添加了新的退出和保存交互框，矩阵工具，底部画板，优化了放缩工具

2024-6-23 添加了撤销和重做功能，椭圆工具

2024-6-24 添加了画板颜色选择工具，垂直翻转、水平翻转功能，移动的撤销和重做，优化了画笔和矩阵绘制的定位问题，重写图层组件

2024-6-25 添加了缩放和设置可见性的撤销与重做，旋转功能和菜单下的缩放功能，优化了画笔和矩阵的绘制逻辑，以创建画布图层代替直接在原图上的绘制

2024-6-26 添加了图层模块和右侧展示模块的信号连接，用户自定义的旋转功能，画笔的大小更改，钢笔和喷漆工具，优化了绘图的实现逻辑，修复了缩放撤销bug


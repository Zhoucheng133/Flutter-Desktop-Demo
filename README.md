# Flutter桌面开发的模板

本模板添加了以下的依赖
- 使用`window_manager`作为窗口管理工具
- 使用`flutter_localizations`进行框架本地化
- 使用`google_fonts`代替默认的字体

另进行了以下配置
- 根据`window_manager`的说明文档对`window/runner/flutter_window.cpp`和`macos/Runner/MainFlutterWindow.swift`进行了配置
- 根据`window_manager`的说明文档在主函数中创建了一个大小为`800x600`的窗口
- 根据`window_manager`创建了在Windows系统中的窗口控制按钮和监听
- 根据`flutter_localizations`的说明文档在主函数中添加了框架本地化，添加了简体中文语言和美国英语语言
- 根据`google_fonts`的说明文档在主函数中设置了默认字体为`NotoSansSC`
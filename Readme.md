超级电容控制板Plus CubeMX工程文件
----

**此仓库为CubeMX生成的初始化工程。完整的代码依赖[RM-SuperCapCtrlLib](https://github.com/DonotFreeze/RM-SuperCapCtrlLib) 库文件，需要手动将此库文件添加到工程目录下。**

主要是因为，CubeMX生成的工程文件仅需要添加必要的初始化函数，为了保持[RM-SuperCapCtrlLib](https://github.com/DonotFreeze/RM-SuperCapCtrlLib) 兼容Lite与Plus版本超级电容控制板，且为了能够方便下载。故将核心代码独立做成库，并且绝大多数情况下都只会修改库函数，不会影响CubeMX生成的工程文件的有效性。

# 许可证

使用MIT协议进行授权。
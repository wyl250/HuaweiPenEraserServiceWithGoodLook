# HuaweiPenEraserService

MateBook E 系列全应用双击切换橡皮。

在使用它之前，你需要先去 `C:\Program C:\Program Files\Huawei\PCManager\components\accessories_center\accessories_app\AccessoryApp\Lib\Plugins` 下面删除和你的笔相关的 DLL 来阻止原先的笔事件响应程序加载。

博客：https://blog.qwq.ren/posts/huawei-matebook-e-pencil-eraser-whitelist-analysis-mitigation/

将原本托盘的拟物化图标改成扁平化了，并且用tkinter写了一个跟原本驱动差不多的弹窗

使用方法：将eraser_service_tcp文件夹中的同名exe设为开机自启（你手动点开也行）
然后进入设置》蓝牙和其他设备》笔和windowslink》选择快捷方式按钮功能”》双击 设为打开程序，程序选择trigger文件夹里的同名exe   

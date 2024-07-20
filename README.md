# HuaweiPenEraserService

MateBook E 系列全应用双击切换橡皮。

在使用它之前，你需要先去 `C:\Program C:\Program Files\Huawei\PCManager\components\accessories_center\accessories_app\AccessoryApp\Lib\Plugins` 下面删除和你的笔相关的 DLL 来阻止原先的笔事件响应程序加载。

博客：https://blog.qwq.ren/posts/huawei-matebook-e-pencil-eraser-whitelist-analysis-mitigation/

将原本托盘的拟物化图标改成扁平化了，并且用tkinter写了一个跟原本驱动差不多的弹窗

代码改得依托，能跑就行

问题是用pyinstaller打包后Windows defender会报毒

重新写了一下，不会报毒了

但我的环境似乎有点问题，编译出的程序在退出时会弹一个warrning，就连编译没修改的程序也会这样

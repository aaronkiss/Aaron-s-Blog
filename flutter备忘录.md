## 优化安卓应用图标
在 Android Studio 中打开项目后，打开 *android/app/src/main/AndroidManifest.xml* 。此文件定义了许多与启动、权限、Play 商店和 Android 系统相关的应用的 Android 属性。

下面的属性之一`application`定义了启动器屏幕图标：

`android:icon="@mipmap/ic_launcher`

该`@mipmap`部分意味着它解析为`mipmap-{resolution}`文件夹以加载正确设备屏幕比例的图形。`ic_launcher`是图标的文件名。

在*main/res* 下，您将找到各种*mpimap-*子文件夹。

在 Finder 中，从章节材料中打开assets/icons/android。从 Finder复制res文件夹并替换Android Studio 中的android/app/src/main/res。

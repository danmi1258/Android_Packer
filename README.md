# Android_Packer
此项目是Android 加壳程序示例代码。

仓库中存储一个完整的Android Studio项目，可在API 19直接运行，其他版本并未测试。由于在较低API的版本中，/frameworks/base/core/java/android/app/ActivityThread.java中使用了HashMap，而高API版本中相对应的是（final ArrayMap<String, WeakReference<LoadedApk>> mPackages = new ArrayMap<String,WeakReference<LoadedApk>>();） ArrayMap，由此可造成不兼容。

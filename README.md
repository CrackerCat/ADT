# android_decompile_tool

* 集成jadx快速查看apk包内容
* 集成apktool可以快速实现包体的反编译和回编译
* 集成jar2dex、dex2jar，实现文件格式类型转换
* 集成apksigner和zipalign，快速实现包体的签名和对齐
* 集成bundletool，实现aab转apks
* 根据新旧dex快速生成增量包patch.dex


使用方法
1. 直接下载release中的release/adt.zip，解压到本地目录,双击adt.bat文件即可
2. 通过gradle的task命令生成      生成路径：**项目的根目录/release/adt.zip**
```
./gradlew release
```
提示:
请确保您的PC包含java 11环境并配置了环境变量
```
如果觉得本工具对你有帮助，不妨请作者喝杯奶茶😊😊😊
```
![收款码](./tools/wx_payment_code.jpg)

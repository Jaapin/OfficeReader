# libreoffice_android
##目的
是LibreOffice的Android版本(5.3.0.0.alpha0+/05c89af)，提供方便的编译版本，在前人的基础上编译，修改可以编译成功，需要下载Python,配置环境变量
##使用说明
<p>clone好后，修改android/source/liboSettings.gradle文件中ext的定义，如liboSrcRoot的路径信息，改写成实际的路径信息，即可编译。
<p>此版本只是修改配置文件信息，提供了so库（没有源文件），因此也只能完成上层的修改优化。
后续有需要了再及时同步LibreOffice最新版本，自己想编译的话参考[编译开源LibreOffice的Android版本](http://blog.csdn.net/w7849516230/article/details/52556469)

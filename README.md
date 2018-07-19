# -IPA---python-
python 自动打ios debug/release包

使用步骤:



1. 打开命令行 , cd到脚本所在目录
cd到脚本所在目录

2.执行Configuration.py , 配置打包选项

3.选择是否包含.xcworkspace文件
configuration选项 1

4.输入项目路径(.xcworkspace 或 .xcodeproj 所在文件夹路径 ) , 可直接拖入命令行
configuration选项 2


5.输入项目名
configuration选项 3

6.输入打包的target名
configuration选项 4

7.输入打包完成后.ipa文件的输出位置
configuration选项 5


到这里所有的配置都已设置完成 , 接下来执行Release.py
8.执行Release.py
选择build类型
选择类型
确认打包
确认


注意:

1. 项目相关设置需要在XCode里进行,包括证书之类的选择 和 bundleVersion , displayName等

2.第一次配置完成后 , 如果打包的相关配置(项目位置 , 打包的target名等) 不需要改变 , 那么可以直接运行Release.py , 即cd到脚本目录 , 然后执行python Release.py  


这个脚本只是简单的封装了几个终端打包的命令 , 关于命令行打包的相关知识我就不介绍了 , 有兴趣的童鞋可以移步iOS自动打包并发布脚本 这篇介绍的很详细 .

参考文档：

https://www.jianshu.com/p/c9e338ad3ab4

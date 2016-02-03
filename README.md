#README
##echarts2.0
echarts2.0是使用单文件模块化导入的方式来载入包的
##echarts3.0
echarts3.0也是使用单文件模块化导入的方式来载入包的，但是引用的js文件也是在dist目录下的，包含的包也在ehcarts3.0/echarts下
##echarts-x
######echarts-x使用的是单文件模块化导入的方式来载入包的，但是要注意的是官方文档的包的文件路径和最新的release版本是不同的，下载了老版本的release版本才搞定，确定版本可以通过看它的example的源文件，版本信息如下：
* zrender, version 2.0.8
* qtek, version 0.2.1
* echarts, version 2.2.1
* echarts-x, version 0.2.0

######所有的包都包含在echarts-x/dep文件夹下了。代码里要还改config的那个路径，不是src,而是build/dist。

# slpkTools_Pro2.6

如果Pro 2.6中直接执行Create Integrated Mesh Scene Layer Package工具报错，可以使用osgbToslpk工具。

osgbToslpk工具：
1，输入osgb文件夹路径那里选择Data的上一级文件夹；
2，工具会自动寻找输入文件夹下有没有metadata.xml文件，如果有的话，输入锚点文件参数下会自动识别出该文件，
没有的话可以手动选择shapefile文件；
3，空间参考输入WKID即可。

如果需要优化slpk的大小，可以使用Optimize Slpk Size工具，可以优化3D Object以及倾斜类型的slpk。
Optimize Slpk Size工具：
1，输入slpk所在的文件夹路径即可，支持批量执行
2，输出的slpk在同一文件夹下，以原始slpk名称+_tar结尾命名。


tips: 
以上工具针对Pro 2.6以及I3S 1.7版本

传统obj通过Import 3D files导入Pro后变暗，而Quick Import工具导入正常的问题，可以使用Optimize Obj工具。
Optimize Obj工具：
输入obj所在的文件夹路径即可，可以批量处理。该工具不涉及Pro版本，都可以用。


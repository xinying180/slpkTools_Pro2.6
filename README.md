# slpkTools_Pro2.6

一、osgbToslpk工具：
如果使用Pro中的Create Integrated Mesh Scene Layer Package工具报错，可以使用osgbToslpk工具，使用方法：
1，输入osgb文件夹路径那里选择Data的上一级文件夹；
2，工具会自动寻找输入文件夹下有没有metadata.xml文件，如果有的话，输入锚点文件参数下会自动识别出该文件，
没有的话可以手动选择shapefile文件；
3，空间参考输入WKID即可。

tips：该工具目前仅针对Pro 2.6版本

二、Optimize Slpk Size工具：
如果需要优化3D Object以及倾斜类型的slpk的大小，可以使用Optimize Slpk Size工具，使用方法：
1，输入slpk所在的文件夹路径即可，支持批量执行
2，输出的slpk在同一文件夹下，以原始slpk名称+_tar结尾命名。

tips: 该工具仅支持I3S 1.7版本

三、Optimize Obj工具：
该工具解决传统obj模型通过Import 3D files导入Pro后变暗或者纹理丢失问题，使用方法： 
1，输入obj所在的文件夹路径即可，支持批量处理。

四、Chaifen Obj工具：
该工具用于将较大的Obj拆分成小的obj，拆分后的obj以原始object名称命名，如遇重复名称则末尾加_1,_2,_3...处理，使用方法：
1，输入obj所在的文件夹路径即可，支持批量处理。


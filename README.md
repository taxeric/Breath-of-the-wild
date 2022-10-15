# Breath-of-the-wild
获取《Breath-of-the-wild》背景音乐

## 解包
使用[NSC_BUILDER](https://github.com/julesontheroad/NSC_BUILDER/releases),具体操作请参见:[文章](https://blog.csdn.net/today__present/article/details/123171658)第一步  
目录如下:  
![image](https://user-images.githubusercontent.com/51876689/195987009-8baa11c7-7885-435e-8528-f131c21a68bd.png)  
Sound-Resource目录即为**背景音乐及音效目录**

## 解析.bars
使用[BarsTool](https://github.com/NanobotZ/BarsTool/releases),步骤如下
1. 点击第一个Choose选择`.bras`文件
 ![image](https://user-images.githubusercontent.com/51876689/195986780-c4181e16-a72d-4c95-a805-ab2d6c8257ae.png)  
2. 点击Open
 ![image](https://user-images.githubusercontent.com/51876689/195986816-39c9a70f-a9f5-4cec-b98a-92f9480e1435.png)  
3. 点击Selece All
 ![image](https://user-images.githubusercontent.com/51876689/195986878-bce1db4d-92c3-4a78-a9d0-3444f34547e6.png)  
4. 点击Export
 ![image](https://user-images.githubusercontent.com/51876689/195986900-c55c18a3-066e-405a-8236-062cac81e87d.png)  
5. 输出路径为**原音效目录下对应文件夹**,不同音效打开后的数量会不同

## 解析bfwav
使用[LoopingAudioConverter](https://github.com/libertyernie/LoopingAudioConverter/releases),步骤如下
1. 添加.bars文件或文件目录
![image](https://user-images.githubusercontent.com/51876689/195987088-920e7a7e-f3fc-4018-929e-fa3b1317c377.png)  
2. 设置Output directory (设置输出路径,可选,默认为工具目录下的`output目录`)
3. 设置Output format,选择欲输出文件类型,这里选MP3
4. 点击Start等待转换完成

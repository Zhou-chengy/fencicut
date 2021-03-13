# fencicut中文分词

## 简介：这是一款分词工具，由小懒猫AI推出

示例
```Python

from fencicut import fenci

print(fenci.cut('这里是北京'))

```

效果：['这里','是','北京']

## 安装

下载后把fencicut目录挪到site-packages目录下或挪到您要使用的目录下

##使用说明

fenci.cut有一个参数：要切割的字符串

自定义词典：

示例：

```Python

from fencicut import fenci

a = fenci('xxx','xxx')

a.train('utf-8')

print(a.cut('我爱中国'))

```

其中第一个xxx是指数据文件，编写参考dict.txt,第二个xxx是指模型名

## 注意：

使用前请下载python3.8和预训练模型





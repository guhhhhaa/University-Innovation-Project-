# DaChuang
# bullshit 

# 之前的项目简介

## 一堆摄像头连一个主机，5分钟拍一次照片。

### 如何使用Python操作摄像头

- https://coolshell.cn/articles/1928.html

- 

	- http://videocapture.sourceforge.net/

- Python Imaging Library (PIL)

	- http://www.pythonware.com/products/pil/

- 

	- https://www.pygame.org/news

### python+opencv+android手机在ubuntu上作为IP摄像头

- https://blog.csdn.net/wuzuyu365/article/details/52469131

## 实例分割(Instance Segmentation)：

### 对照片进行语义分割(Semantic Segmentation )，把书架各个层识别出来。

- 对书架一个层的各个书做实例分割(Instance Segmentation)，检测出书的边界和排列顺序，并判断书是否倾斜。

	- PANet

		- Path Aggregation Network for Instance Segmentation

		- CVPR2018(IEEE Conference on Computer Vision and Pattern Recognition)

		- COCO2017/CityScapes instance segmentation 第一

		- https://arxiv.org/pdf/1803.01534.pdf

	- MX Mask R-CNN

		- https://github.com/TuSimple/mx-maskrcnn

		- https://arxiv.org/pdf/1703.06870v1.pdf

		- https://www.zhihu.com/question/67119841

	- Mask^X R-CNN 

		- https://www.jiqizhixin.com/articles/2017-12-02

		- https://arxiv.org/pdf/1711.10370.pdf

## 场景文字端到端识别 (Scene Text End-to-End Recognition)：识别图书侧边文字，得到书名，并判断是否颠倒放置。

### http://mclab.eic.hust.edu.cn/~xbai/Talk_slice/Oriented-Scene-Text-Detection-Revisited_VALSE2017.pdf

## 把从图像中获得的信息(书架号，书名，放置位置，是否倾斜，是否放反)存入一个数据库A。

### https://blog.csdn.net/Oscer2016/article/details/70257024

- MySQLdb 

	- https://pypi.python.org/pypi/MySQL-python

	- 用于 Python 连接 MySQL 数据库的接口，它实现了 Python 数据库 API 规范 V2.0，基于 MySQL C API 上建立的。

- mysql.connector

	- 需要支持 Python 的 MySQL 驱动来连接到 MySQL 服务器。

	- mysql-connector-python：是 MySQL 官方的纯 Python 驱动；

	- MySQL-python ：是封装了 MySQL C驱动的 Python 驱动。

## 将数据库A和图书馆现有的数据库B中的书籍信息，根据书名做模糊字符串匹配，判断书是否放错顺序。

### fuzzywuzzy

- https://pypi.python.org/pypi/fuzzywuzzy


- https://pypi.python.org/pypi/fuzzywuzzy

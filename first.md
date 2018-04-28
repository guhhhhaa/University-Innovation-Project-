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

## 啥？图像哈希值检索？啥？CBIR？
- Deep Supervised Discrete Hashing https://arxiv.org/abs/1705.10999
- “基于内容的图像检索”(content-based image retrieval (CBIR))
- Deep Binary Representation for Efficient Image Retrieval https://doi.org/10.1155/2017/8961091
- 图像检索：再叙ANN Search https://yongyuan.name/blog/ann-search.html
- FP-CNNH: 一种基于深度卷积神经网络的快速图像晗希算法 
  http://www.jsjkx.com/jsjkx/ch/reader/create_pdf.aspx?file_no=20160907&flag=&journal_id=jsjkx&year_id=2016
- java:均值哈希实现图像内容相似度比较 https://cloud.tencent.com/developer/article/1011693
- Java相似图片搜索算法之"感知哈希算法"实例 http://blog.sina.com.cn/s/blog_5ddc071f0101o9th.html
- java指纹识别+谷歌图片识别技术=======源码实现===分享出来===
  http://www.icodeguru.com/3/2451.html
- 计算图片之间的相似度
  https://github.com/nivance/image-similarity
- 图片相似度计算（直方图，峰值信噪比，结#构相似性，感知哈希算法），轮廓检测，直线检测，圆检测，角点检测，直线交点计算，旋转角度矫正，图像匹配的对应相似处连线，灰度，二值化，直方图均衡化。
  https://github.com/weichao66666/OpenCV_image_comparator  
- Google 以图搜图- 相似图片搜索原理- Java实现- 技术人生
  http://www.jishurensheng.com/580220004.html

---

### 华中科技大学 ppt

- [Deep Neural Networks for Scene Text Reading - Universal Pattern ...](http://u-pat.org/ICDAR2017/keynotes/ICDAR2017_Keynote_Prof_Bai.pdf)

- B. Shi, C. Yao, M. Liao, M Yang, P Xu, L Cui, S Belongie, S Lu, X Bai.

[ICDAR2017 Competition on Reading Chinese Text in the Wild ( RCTW-17). ICDAR’17](http://mclab.eic.hust.edu.cn/icdar2017chinese)


---



- [【大规模图像检索的利器】Deep哈希算法介绍](https://zhuanlan.zhihu.com/p/21396173)

- [中科院NIPS 2017论文提出深度离散哈希算法，可用于图像检索](https://www.jiqizhixin.com/articles/2017-11-02-20)

    - https://arxiv.org/abs/1705.10999
---

- [A Single-Shot Oriented Scene Text Detector - arXiv 1801.02765](https://arxiv.org/pdf/1801.02765)

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

## 啥？图像哈希值检索？啥？CBIR？
- Deep Supervised Discrete Hashing https://arxiv.org/abs/1705.10999
- “基于内容的图像检索”(content-based image retrieval (CBIR))
- Deep Binary Representation for Efficient Image Retrieval https://doi.org/10.1155/2017/8961091
- 图像检索：再叙ANN Search https://yongyuan.name/blog/ann-search.html
- FP-CNNH: 一种基于深度卷积神经网络的快速图像晗希算法 
  http://www.jsjkx.com/jsjkx/ch/reader/create_pdf.aspx?file_no=20160907&flag=&journal_id=jsjkx&year_id=2016
- java:均值哈希实现图像内容相似度比较 https://cloud.tencent.com/developer/article/1011693
- Java相似图片搜索算法之"感知哈希算法"实例 http://blog.sina.com.cn/s/blog_5ddc071f0101o9th.html
- java指纹识别+谷歌图片识别技术=======源码实现===分享出来===
  http://www.icodeguru.com/3/2451.html
- 计算图片之间的相似度
  https://github.com/nivance/image-similarity
- 图片相似度计算（直方图，峰值信噪比，结#构相似性，感知哈希算法），轮廓检测，直线检测，圆检测，角点检测，直线交点计算，旋转角度矫正，图像匹配的对应相似处连线，灰度，二值化，直方图均衡化。
  https://github.com/weichao66666/OpenCV_image_comparator  
- Google 以图搜图- 相似图片搜索原理- Java实现- 技术人生
  http://www.jishurensheng.com/580220004.html

---

### 华中科技大学 ppt

- [Deep Neural Networks for Scene Text Reading - Universal Pattern ...](http://u-pat.org/ICDAR2017/keynotes/ICDAR2017_Keynote_Prof_Bai.pdf)

- B. Shi, C. Yao, M. Liao, M Yang, P Xu, L Cui, S Belongie, S Lu, X Bai.

[ICDAR2017 Competition on Reading Chinese Text in the Wild ( RCTW-17). ICDAR’17](http://mclab.eic.hust.edu.cn/icdar2017chinese)


---



- [【大规模图像检索的利器】Deep哈希算法介绍](https://zhuanlan.zhihu.com/p/21396173)

- [中科院NIPS 2017论文提出深度离散哈希算法，可用于图像检索](https://www.jiqizhixin.com/articles/2017-11-02-20)

    - https://arxiv.org/abs/1705.10999
---

- [A Single-Shot Oriented Scene Text Detector - arXiv 1801.02765](https://arxiv.org/pdf/1801.02765)

Simple-Web-crawler_Zhihu
========================

网页爬虫扒取知乎主页源代码到本地硬盘进行存储，并简单筛选出一部分网址
注意点：
1.本地硬盘存储的文件：zhihu.txt由于是与代码同一个文件夹里，所以没有把文件绝对路径写进去
2.筛选出的部分网址结果如下：
  http://static.zhihu.com/static/img/ios/zhihu(57px).png
  http://static.zhihu.com/static/img/ios/zhihu(72px).png
  http://static.zhihu.com/static/img/ios/zhihu(76px).png
  http://static.zhihu.com/static/img/ios/zhihu(114px).png
  http://static.zhihu.com/static/img/ios/zhihu(120px).png
  http://static.zhihu.com/static/img/ios/zhihu(152px).png
  其他网址由于格式与这个网址不同，不能用同一个正则表达式进行筛选

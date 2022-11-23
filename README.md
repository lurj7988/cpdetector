# 软件简介
一个可以自动检测文本编码格式的项目

detector按照“谁最先返回非空的探测结果，就以该结果为准”的原则返回探测到的 字符集编码。

cpdetector是基于统计学原理的，不保证完全正确。

整合了三方包`chardet-1.0.jar`和`jargs-1.0.jar`

整合了自动获取文件的编码`EncodingDetect.java`
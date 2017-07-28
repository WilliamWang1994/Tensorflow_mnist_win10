运行环境：
python3.5.3

tensorflow 1.2.1

win10

nvidia geforce 940

[windows如何搭建运行环境](http://www.jianshu.com/p/f14960671ce3) anaconda方式


RUN：
建议先自行run regression  和 convolutional，这两个脚本是将tensorfly下载下来的四个压缩数据集进行训练，
然后保存模型。
如果想跳过的就直接运行main.py即可

相比于https://github.com/sugyan/tensorflow-mnist
不用通过nodejs编译js，加入了mnist原始数据集，
另外关键代码加了一些自己理解的注解

建议：手写数字时应当尽量居中写，运行main.py文件之前，应关闭电脑上的代理app，否者会报500错误。

参考：
https://github.com/sugyan/tensorflow-mnist

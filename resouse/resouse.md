# 数据调用和后端

## 创建

gitbook能创建模板书：`gitbook init[./directory] 12`最后一个参数为创建的目录，可省略，默认为当前目录下。![image-20201118154028943](https://img-blog.csdnimg.cn/img_convert/ebcfe1b255cf4151d8043f4c89a6f43a.png)命令执行完后会生成两个文件：`README.md`和`SUMMARY.md`README.md文件用来介绍该书籍，SUMMARY.md文件为该书籍的目录。对SUMMARY.md文件进行如下编辑：`# Summary * [Introduction](README.md)* [Easy](easy/README.md)    * [1.Two Sum](easy/1.Two Sum.md)    * [7.Reverse Integer](easy/7.Reverse Integer.md)* [Medium](medium/README.md)    * [2.Add Two Numbers](medium/2.Add Two Numbers.md)    * [3.Longest Substring Without Repeating Characters](medium/3.Longest Substring Without Repeating Characters.md)123456789`再次执行命令`gitbook init`，如果目录里的文件不存在，将会自动创建：![image-20201118155520614](https://img-blog.csdnimg.cn/img_convert/372b049390e6fa1fe32be4e85595d55a.png)然后我们对其中的md文件编写相应的内容即可。

## 输出



### 
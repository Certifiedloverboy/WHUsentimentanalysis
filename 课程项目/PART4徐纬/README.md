# ipynb文件

* 情感分析.ipynb为本项目的主文件，它包括项目运行所需要的所有代码以及运行结果。

# py文件

* 情感分析.py为本项目的完整程序，运行结果请参照上面“情感分析.ipynb”文件。

# 数据

* data.csv与data1.csv为从网站上爬取的贴子源文件。由于行数过多，文件一分为二。
* 将两份csv文件合并为武汉.csv

# 停用词表

* 程序进行中文分词时使用的停用词表是该文件夹中的stoplist.txt
* 由于汉语中存在多重否定现象，即当否定词出现奇数次时，表示否定；偶数表示肯定。采用not.csv标注否定词。

# 替换库

* Gensim是一款开源的第三方Python工具包，用于从原始的非结构化的文本中，无监督地学习到文本隐层的主题向量表达。
* jieba是一款优秀的 Python 第三方中文分词库。
* matplotlib是一个 Python 的 2D绘图库，它以各种硬拷贝格式和跨平台的交互式环境生成出版质量级别的图形。
* numpy是Python的开源的数值计算扩展库。
* pandas是基于NumPy 的一种工具，该工具是为解决数据分析任务而创建的。
* wordcloud是优秀的词云展示第三方库。

# 情感词表

采用OpenHowNet在中文世界有巨大影响力的语言知识库——知网（HowNet）作为情感词库。提供了四个文件：
共有中文正面评价、中文正面情感、中文负面情感、中文负面评价四份文档。
* 分别将前两者和后两者进行整合，作为正面、负面情感词表来源。

# 部分成果图

* 将论坛评论数年度走势绘制成折线图，并输出为“评论数走势.png”。
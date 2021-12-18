

# 1. 概述

这里用于汇集学习、科研入门所需的各种资料。固定网址 https://hanqn.com/tutorial/

`这个页面为韩博士个人总结和组内使用，未经许可请勿随意分享。`

# 2. 科研软件

## 2.0. abaqus学习参考

abaqus documentation：最好的abaqus学习资料，不仅有步骤讲解，还有详细的每个操作设置涉及的理论，abaqus界面点击help即可进入，网上搜索也能找到很多在线documentation例如 http://wufengyun.com:888/  。

abaqus documentation使用提示：

- 最常用的是Abaqus/CAE User's Guide（相当于入门教程，有很多详细的操作过程讲解）和 Abaqus Analysis User's Guide（部分稍难一些的操作、操作涉及的理论讲解）。
- 点击abaqus界面导航栏中“问号”，再点击一个窗口或者界面上任意位置，可以迅速进入abaqus documentation相应的内容讲解。
- 在abaqus documentation页面搜索框搜索关键词：查看搜索结果中数字最大的位置，一般可以找到需要搜索的内容。

庄茁《基于abaqus的有限元分析和应用》：本书有大量示例，以及详细的abaqus操作过程（例如下面提到的连接环静力分析），网上有pdf。



## 2.1. abaqus入门
   
abaqus安装包和安装教程：

链接：https://pan.baidu.com/s/1Sb8HwSpzhkVdtEekRJcmxw 
提取码：7i8z 


安装教程其实网上特别多，大部分都可以安装成功，而且基本都差不多。

abaqus连接环静力分析教程：https://hanqn.com/tutorial/%E8%BF%9E%E6%8E%A5%E7%8E%AF%E7%9A%84%E9%9D%99%E5%8A%9B%E5%88%86%E6%9E%90%E6%95%99%E7%A8%8B.doc?raw=true

abaqus XFEM扩展有限元裂纹分析教程：https://wk.baidu.com/view/dc0f1cc558f5f61fb73666ed?pcf=2

XFEM科普：https://mp.weixin.qq.com/s/9TN5fbOlIHs6WrGgPYRchQ 

**具体要求如下：** 

请按照第1个链接是一个安装教程，自己下载安装一下abaqus，那个教程的底部有百度网盘的下载链接。然后第2个和第3个是两个具体的案例，一个是连接环，一个是裂纹扩展，自己独立照着做一下。

然后把自己做的步骤（可以放若干重要的截图），加上计算结果分析（这一部分自己可以做一些自己的分析，多放一些结果图如：应力 应变 位移图，从图上能得到什么结论分析一下写一写）。发两个word（每个案例单独一个word）到我邮箱。

注意，软件比较大，安装要耐心。abaqus装好后不要汉化，就用英文版的，一个好处是可以锻炼英语，第2个好处是教程基本上提到abaqus的按钮名次都是英文 ，汉化了看教程反而费劲。

这个软件基本大家做毕设、读研、工作都会用到，提前学习一下是好事，另外报告撰写（格式、图表编号等）提前练一下，可以为以后打下很好的基础。

## 2.2. abaqus阶段二：微动的XFEM分析

参考文献：https://www.sciencedirect.com/science/article/pii/S0301679X16001377#f0025  的Fig.2进行微动接触模型建立，尺寸大概相似即可不要求完全一样，边界条件按照文献设置、载荷按照Table1中的Case2或3。网格划分与Fig3类似即可，不要求完全一致。参考XFEM入门教程实现的方法，在Specimen上、接触区中央设置XFEM裂纹，裂纹扩展准则等设置可以都按照XFEM入门教程。以上是模型设置的主要要求，其他可以自己学习、网上百度、参考文献书籍或者与我讨论。

**要求如下：**

模拟微动(fretting)载荷下的裂纹扩展，作出类似文献的Fig. 5和Fig.6（当然如果能仿照文献中的其他相关图片出图就更好了），注意由于选择的裂纹扩展准则不同，获得的结果与文献中的不同是完全正常的。自己做的步骤（可以放若干重要的截图），加上计算结果分析，写成一个word，发邮箱即可。

## 2.3. Origin作图软件

origin正版：https://my.originlab.com/forum/topic.asp?TOPIC_ID=22328      

盗版origin容易造成死机，并且作图极慢。

origin教程：

https://mp.weixin.qq.com/s/u3LsvCIROUnc-4UcVHJ9kw

https://mp.weixin.qq.com/s/5HLzQ07Gn4tr4OUYi56SZQ

# 3. 基本科研训练

每年5月份结束时候要交的报告模板，请浏览：https://hanqn.com/tutorial/%E5%9F%BA%E6%9C%AC%E7%A7%91%E7%A0%94%E8%83%BD%E5%8A%9B%E8%AE%AD%E7%BB%83-%E6%8A%A5%E5%91%8A%E6%A8%A1%E7%89%88-2019.zip

# 4. 本科毕设

时间节点：

春季学期开学前完成：开题报告word和开题ppt，因为开学基本就开题汇报了。同时应完成毕设第一章（大约十页），英文文献翻译，试件设计图纸（若涉及做实验）。开题报告word模板毕设系统网站有，除了布置的文献调研之外，还应包含拟采取的技术路线，可以按自己理解先写回来我再改。开题ppt应该包含：研究背景、文献调研、研究目标、研究内容的框架图、拟采取的研究方案、进度安排。

春季学期开始后：一般立刻进行开题答辩。

5月底：完成毕设论文撰写。



# 5. 文献调研和下载相关（本科生版本）

1、请点击pdf查看：

https://hanqn.com/tutorial/%E6%96%87%E7%8C%AE%E8%B0%83%E7%A0%94.pdf

感谢方健文整理。


2、高温合金和金属疲劳相关入门书籍：

（以下书籍均有电子版pdf，咨询方健文索取）

《材料的疲劳 第3版》 (美)S.SURESH著，王中光译 国防工业出版社

《高温合金基础与应用》  (英)Roger C.Reed著，何玉怀 等 译

《航空金属材料增材制造技术》 熊华平，郭绍庆，刘伟，张文扬 著



# 6. 文献调研和下载相关（本科毕设&研究生版本）

<!-- 锚点： https://hanqn.com/tutorial/index.html#4-%E6%9C%AC%E7%A7%91%E7%94%9F%E6%AF%95%E4%B8%9A%E8%AE%BE%E8%AE%A1  --> 

文献调研网站工具：

（推荐）谷歌学术 https://scholar.google.com  ，或者web of science：http://apps.webofknowledge.com/Search.do  。

不推荐使用百度学术，因为收录的sci很少而且检索排序较乱。

主要调研五年内文献，掌握近期进展。经验上来说被引用数高的文献看的价值大一些（但不绝对）。

论文写作中常用软件：word中文献插入用endnote，公式输入和公式编号mathtype，画图表origin，三维零件设计solidworks/ug/catia等（学精一个即可）。图表编号用word本身即可（百度有提示）。

sci文献下载（正常方式，推荐，网络需要处于学校ip）：谷歌学术点击文章链接可以直接跳转到文章页面（注意如果用的是谷歌学术镜像，一般无法跳转到真实页面），学校把elsevier、wilely的文章大部分都买了，在文章页面可以直接下载pdf。

使用 doi.org ：这个网站中输入doi号（每个文章唯一的身份证号），也可以直接跳转到文章页面（中间可能需要多次跳转，刷新网页即可）。或者直接在浏览器地址中输入doi.org/doi号。

sci文献免费下载（校外也可）：sci-hub（百度即有网址，大约是sci-hub.shop）。

Elsevier ScienceDirect文献远程访问（在家下载文献）：http://lib.nuaa.edu.cn/do/bencandy.php?fid=3&id=3669   这个我一直在用，很好用。

# 7. 学习科研心得

仅供参考，因人而异。

## 7.1. 制定个人计划的诀窍

**定一个大计划不如制定当前就可以实现的可操作的小计划（不怕小，越具体越好）。**例如：

下周把数学复习完 → 明天把数学的第1章第1节的第一小节复习完

下个月备考四六级 → 今天背5个单词听2分钟听力

2月份写完论文 → 今天写论文第1章第1节的第1句

每周学一个小时matlab → 明天学习matlab for循环的第一个例子

## 7.2. 好记性不如烂笔头

多记学习和科研笔记，例如，自己学习新软件中遇到的问题和解决方法记录下来，绝对胜于网上别人的教程。自己阅读英文文章、写作范文、sci文章积累的好句式，绝对胜于网上别人总结好的宝典。

建议学习使用云笔记（有道云笔记、印象笔记、微软OneNote，选一个一直用即可）。

养成长期记笔记的习惯。我从2013年开始用云笔记至今已经记录了10多GB笔记。

## 7.3. 看文献步骤

施一公教授讲述看文献要点：

https://mp.weixin.qq.com/s/o4tA_jWbU5Q8T3HixjB-Pw

看标题、看摘要、看结论→看图→看全文（如果发现不太相关就可以不读全文或者粗读）。

## 7.4. 学英语

主要在于坚持，每天学习10多分钟好于考前集中学两天。

【生活英语】背单词：扇贝单词app，以及利用有道词典app的单词记录本

【科技英语】背单词：看SCI论文的过程中积累单词

听力 阅读 口语：推荐一个练科技听力和阅读的nature podcast，里面都是自然科学的话题：（网页上有mp3、outline）

https://play.acast.com/s/nature/googleaibeatshumansatdesigningcomputerchips   

这个里面旧的cast有英语原文：

https://www.nature.com/nature/articles?type=nature-podcast

`这个页面为韩博士个人总结和组内使用，未经许可请勿随意分享。`

`Last update: 16/12/2021`



# 概述

**只点一下，将Web of Science搜索结果保存为参考文献。

**Generate citations from Web of Science by JUST ONE CLICK!


# 安装

推荐方式：Chrome Store安装：https://chrome.google.com/webstore/detail/web-of-science%E7%94%9F%E6%88%90%E5%8F%82%E8%80%83%E6%96%87%E7%8C%AE%E5%8A%A9%E6%89%8B/fdpfmjedelhpgjhdgchopbggaabmmbnm

如果您无法通过以上方式安装，请点击这里下载crx文件手动安装到Chrome浏览器。

# 使用说明

2021.2更新：

1、修复了Chrome更新、Web of Science改版之后无法运行的问题。
2、现在已经支持English、简体中文、繁體中文的web of science页面。
3、现在已经支持大部分库，不再需要限定Web of Science Core Collection库。
3、优化视图：主要是添加滚动条显示，以及不会每次刷新页面都有Alert（弹窗提示）了。
4、提示文字在ctrl+A全选时不会被选中了。

使用方法：

1. 在Web of Science中搜索时，点击右上角"W"标志的按钮，即可得到当前页面的参考引文；
2. 在"W"标志右键--选项，可以设置参考文献格式、编号格式、设置序号起始值，点击保存，回到搜索页面刷新页面（或者进行新的搜索时），右上角引文更新为新格式。

与"Google Scholar扩展程序"相比的优点：

1、没有Google Scholar扩展程序的功能多，如果能用Google Scholar还是推荐用Google Scholar。
2、可以一次输出多达几十条引文。
3、可以输出为ppt格式。

原理：

将Html页面的DOM拼接成引文格式，不需要发送网络请求（API）。
这与Google Scholar不同，后者是需要获得Html页面的DOM，拼接为paper的信息，再次向Google Scholar API请求引文格式。

提示：

此扩展程序适用于简历、项目申请书、ppt等不需要频繁调整引文顺序的情况。

如果是撰写论文，建议使用可与Word协作的endnote、NoteExpress等插入文献（web of science、google scholar页面具有输出为enw、ris文件的功能）。


# 注意事项和可能出错的原因

1. Web of Science搜索页面加载完时，才能得到结果，页面未加载完结果框会为空；
2. 【重要】保存了设定却没有生效：设定页面修改设定后请勿关闭，报纸页面开启、然后回到web of science刷新页面即可得到新格式的引文。后续将修复这个问题。

感谢您的支持！



`Last update: 01/03/2021`

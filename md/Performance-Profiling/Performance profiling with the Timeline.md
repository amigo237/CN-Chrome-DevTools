使用Timeline做性能分析
***
Timeline面板可以让你记录和分析web应用运行时的所有活动，这是你研究和查找性能问题的最佳途径。  

####Timeline面板概览
Timeline面板主要有三个部分构成：顶部的概述部分、记录视图和工具栏。  
![](https://developer.chrome.com/devtools/docs/timeline-images/timeline_ui_annotated.png)  
* 点击开始/停止切换按钮，开始或停止记录（参考[记录](https://developer.chrome.com/devtools/docs/timeline#making-a-recording)）
* 点击清理按钮来从Timeline中清除已有的记录
* 关联异步事件模式让你更容易的关联异步事件和这些异步事件的调用（参考[嵌套事件](https://developer.chrome.com/devtools/docs/timeline#about-nested-events)）
* 你可以根据记录中的类型、执行时长去过滤Timeline中的记录
在记录期间，每个事件以“瀑布”的形式记录在记录视图中。记录被分为四个基本组之一：加载、脚本执行、渲染和绘图。这些记录以颜色区分，如下：  
![](https://developer.chrome.com/devtools/docs/timeline-images/image01.png)  
以chrome加载一个html页面的记录为例，
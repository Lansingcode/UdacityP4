# UdacityP4
Udacity Data Visualization Project

## 概要  
本项目使用D3.js完成可交互式数据可视化，观察航班延误次数在一个月中的周期性变化，以及在每周七天内有几天的延误率特别高。
## 设计  
选定1987年10月份航班信息数据。使用散点图展示航班延误次数与时间之间的关系，点击DayofMonth按钮时，x轴为十月份包含的日期，y轴为相应日所有机场航班延误次数总和，点击DayofWeek时，y轴为十月份包含的所有周内相同周期所有机场所有航班延误次数总和。用户可通过点击按钮选择查看周期，希望读者通过该图可以看出飞机延误次数在每月中的周期性变化，在每周内的某些天延误次数较多。

## 反馈
1.index1.html文件中为初步设计的草图，但其中显示每周内飞机延误次数时的横坐标为浮点数，更改为整数  
2.在index2.html中加入了悬浮框显示每个点的具体数据，使读者更加直观的看到数据  
3.在悬浮窗中加入数字说明，使展示更加清晰。  
## 资源
[航班信息数据集](http://stat-computing.org/dataexpo/2009/the-data.html)  
[Using d3-tip to add tooltips to a d3 bar chart](http://bl.ocks.org/Caged/6476579)  
[Simple d3.js tooltips](http://bl.ocks.org/d3noob/a22c42db65eb00d4e369)

- 启动方式  
在命令行中进入html所在文件夹，输入命令`python -m SimpleHTTPServer 8080`启动web服务器，在浏览器地址栏中输入`localhost:8080`可显示页面。

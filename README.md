uba是用于监控用户页面行为的js插件。

**目前实现功能：**

1.可以记录用户在页面的，点击行为，记录值包括页面坐标、元素ID、元素链接、元素class。

2.可以通过坐标的记录绘制热点图。

**计划实现功能：**

**运行演示文件:**
```
(sudo) npm install
bower install
gulp serve (gulp watch)
```
（演示将用户点击行为记录和绘制热点图在一个页面里展示，开关为headmap=turle or false。）

**使用方法:**

引用以下两个文件

    app/uab/heatmap.js  // Heatmap plugin
    app/uab/uab.js   //For user click behavior detection.
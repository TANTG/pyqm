# 项目概况（project overview）：

### 项目主题（topic）：我国近年人口老龄化与养老行业情况分析
### 背景：1956年联合国发布的《人口老龄化及其社会经济后果》确定了老龄化社会的划分标准，用65岁以上人口占比划分一个国家进入老龄社会的三个阶段，进入阶段为65岁以上人口占比达到7％以上，深度阶段为达到14％以上，超级阶段为达到20％以上。2018年，我国65岁及以上占总人口比例已经接近12％，即将进入深度阶段。“四二一”家庭结构比较普遍，独居和空巢老人的增多，都给家庭和社会带来了养老压力。面对日益严重的老龄化问题，居民做好养老准备了吗？养老院是否供需平衡？养老行业的相关机构又有什么投资机会呢？这些问题已经迫在眉睫，需要引起社会的关注和重视。
### 项目相关（correlation）
* 项目代码 GitHub_URL：[请点击这里](https://github.com/TANTG/pyqm/tree/master/pyechart-master)
* pythonanywhere的个人部署URL：[请点击这里](http://ttttg.pythonanywhere.com/)
* pythonanywhere的小组最终部署URL：[请点击这里](http://zengjieting.pythonanywhere.com/)

### 个人网站介绍（website）
#### 数据源一共有6个（acs2.csv、bar.csv、bar2.csv、line.csv、map.csv、pie.csv）
#### 所呈现的网页URL一共有8个，其中一共7份图表
* [网站首页](http://zengjieting.pythonanywhere.com/)
* [各省老年人人口数量](http://zengjieting.pythonanywhere.com/toMap/oldMann)
* [各省城市化率](http://zengjieting.pythonanywhere.com/toMap/citys)
* [老年人人口抚养比](http://zengjieting.pythonanywhere.com/toLine)
* 我主要负责前四个交互
* [近五年养老保险情况分析](http://127.0.0.1:8083/toBar)
* [近五年养老院发展趋势](http://127.0.0.1:8083/DEVELOP)
* [2018年养老院行业情况](http://127.0.0.1:8083/BASE)
* [PPP模式下的养老行业](http://127.0.0.1:8083/PIE)

### 项目主要内容（content）
* 利用17级师姐杨幸提供的数据以及产出的交互式数据可视化产品，18级处理成可交互的网页，其中含有一些交互控件的功能实现以及数据的传递过滤，同时也实现了不同HTML的相互交互。

### 项目合作者（cooperator）：
* 中山大学南方学院网络与新媒体专业2017级：杨幸（171013089）
* 中山大学南方学院网络与新媒体专业2018级：曾洁婷（181013024）、谭天冠（181013089）

# 数据传递描述（data transfer description）
html传输数据是post ，app.py传输数据是get
 
### HTML档描述
1. 整体页面布局
* **text-align: center;** 定义整体文字元素居中布局，这样也使页面不过分杂乱；**background: papayawhip;** 定义页面的背景颜色。
* <style>中定义分页面的按钮样式：hover、active、visited、focus等应用效果，具体查看源代码。

2. 交互组件的添加
* 轮播图：轮播图中通过href标签的设置，达成图片与外网链接之间的相互连接。
* 侧边工具栏：分别链接了项目的仓库地址以及三位组员的GitHub页面，同时，最后一个按钮可以在页面下拉的时候迅速回到顶部。
* 页面按钮：
### webapp动作描述
实现了点击导航栏能到达该页面，也实现了在任意界面跳转。在banner图上也有链接，也可以实现跳转。选择下拉框也实现了跳转到正确的页面。用的是a标签。
### 我主要负责：前四个数据传递与交互（网站首页、各省老年人人口数量、各省城市化率、老年人人口抚养比）也参与了轮播图的制作。

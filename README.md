# XGderenjianmx.github.io

一个基于html本地存储（localStorage）的备忘录，无需登录，所有数据、状态将保存在浏览器的本地记录里。

## 功能说明：

#### 1、目前该页面有主要三个区域——home、ideas、todos

#### 2、home区内容（没想好写什么）

#### 3、ideas主要用于记录脑洞、学习笔记等

#### 4、todos作为一个日程表，记录待办事项以及完成情况

#### 5、在todos和ideas-notes区，标题会根据日期显示不同颜色：当前日期为红色，之前日期为灰色，之后日期为vue色；删除功能：可将该条从项目中删除；完成功能：通过滑动按钮标记该事项为待办或者已受理

#### 6、收起后会显示收起内容的条数，在标题（日期）后

#### 7、点击上方菜单可以调整字体大小、显示模式等（目前只有默认和黑暗模式）

#### 8、移动端添加待办，使用`+`唤出菜单，通过点击菜单唤出`form`，需要当`+`关联的数据为`true`才可以唤醒输入表单。但`+`关联的数据为`false`时，输入框所关联的数据也为`false`

##更新：2020/04/04##

--修复：无法比较当前月份与填入数据月份

##更新：2020/05/19##

--增加功能：黑夜模式

--暂时做了一部分移动端适配，添加事项、编辑暂时还没写、路由切换也还没写好（ps：我fo了，移动端兼容太难了，手势什么的太难了！！！）

##更新：2020/05/20##

--增加功能：可以在手机端添加待办了

#3更新：2020/05/23##

--增加功能：

1、可以在手机端添加ideas了

2、添加了手势，可以在触屏中使用手势切换路由

--下一步计划：

1、将idea.vue和todo.vue抽离出来为组件

2、开关改造，这种滑动开关太丑了...考虑换成一般图标

3、vuex分包，将数据结构优化，添加一些功能

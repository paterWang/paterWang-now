# Flutter 初探笔记
##第一点
* import 'package:flutter/material.dart';   //使用material 样式 必须先导入包
* void main() => runApp(MyApp());   //声明app开启的main   runapp 代表 启动app进行页面分发。类似于 android 里的application
* home: routes()      //代表主页面


##与android 语法对比
| 控件      | Android   | flutter |
| ------ | ------ | ------ |
| 容器|  LinearLayout | container|
|图片| imageView| image|
|文本| textview| text|
|图标|||
|按钮|||
|标题栏|appbar|appbar|
|applogo|||
|占位符|||
|导航悬浮的菜单|||
|按钮组|||
|进度条|ProgressBar|LinearProgressIndicator、CircularProgressIndicator|
|富文本|RichText|RichText|
|切换按钮组件|Switch|Switch|
|侧滑菜单|DrawerLayout|Drawer|
|复选框|Checkbox|Checkbox、CheckboxListTile|
|卡片布局|CardView|Card|
|浮动按钮|FloatingActionButton|FloatingActionButton|
|弹出Toast|Toast|Fluttertoast|
|底部弹出Toast|SnackBar|SnackBar|
|图片按钮|ImageButton|IconButton|
|输入文字，输入框|EditText|TextField|
|水平方向|horizontal|row|[README](media/15458759685574/README.md)
|垂直方向|vertical|Column|


## 1.安装ADB驱动到电脑
## 2.找到ADB安装路径
## 3.设置系统环境变量
###   1.此电脑-->属性-->高级系统设置-->环境变量
###   2.新建系统变量：
####    变量名：adb home
####    变量值：先前的ADB安装路径
####    点击“确定”
###   3.在系统变量中找到 path 系统变量，双击编辑
####    右上角点击新建
####    输入%adb home%
####    点击“确定”
## 4.关闭所有DOS窗口
## 5.打开DOS窗口
## 6.输入 adb （若列出ADB相关的帮助信息代表配置成功）

		一笔画问题程序简介
程序中定义有多种模式和状态，在不同模式和状态下支持相应
的功能。模式有编辑图形模式、自动求解模式、非自动求解模
式、普通模式。状态有：拖动图形状态、连线状态、全选移动
状态。

1. 模式
	(1). 编辑图形模式：在该模式下可以编辑当前图形，
	包括添加顶点(Ctrl+Mouse:leftButton)、边(Shift+
	Mouse:leftButton)和删除顶点和边(选中Mouse:Dou-
	bleClick)，程序中的状态是在该模式下工作的，拖
	动图形状态(选中：鼠标左击移动)、连线状态：鼠标
	选中顶点移动鼠标，然后释放鼠标(释放的位置是另)
	一个顶点、全选移动状态(Ctrl+A)：拖动当前图形。
	(2). 自动求解模式：程序默认的模式，在编辑模式
	下按下Q或ESC键可进入该模式。当处于该模式下时，
	按下Space键->程序自动求解问题。
	(3). 非自动求解模式：处于该模式下，玩家可以自
	行求解问题。
2. 菜单栏
	(1). 在菜单中有相应的动作和快捷键进入不同的模
	式。
3. 保存和打开文件
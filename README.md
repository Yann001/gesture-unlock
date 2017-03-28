模拟Android手机手势密码功能
--------------------------------------
主要采用H5 canvas实现
设计思路：
	第一步，采用重叠的三层canvas呈现界面。
		1.背景canvas，位于最底层，绘制背景及九个密码圆圈。
		2.信息提示canvas位于中间层，显示提示信息。
		3.绘制路径操作canvas位于顶层，进行路径绘制及鼠标或触屏事件的绑定。
	第二步，将系统操作步骤抽象出来，包括系统初始化类，画圆类，画线类，文字书写类，数据存储类，工具类等。
	第三步，进行每一个对象方法的编写。
	第四步，编写运行主函数，设计运行逻辑，处理相关事件。
	
	
	

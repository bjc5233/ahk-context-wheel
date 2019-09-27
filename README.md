# ahk-context-wheel
> 效率工具，使用鼠标滚轮执行切换标签\翻页操作


### 说明
1. 使用鼠标滚轮对窗口执行快捷操作
2. 配置多标签应用，一般在窗口标题栏时执行左右切换标签
3. 配置带滚动条应用，一般在窗口右侧边缘时执行上下翻页操作


### 演示
<div align=center><img src="https://github.com/bjc5233/ahk-context-wheel/raw/master/resources/demo.gif"/></div>



### 功能说明
|窗口|位置与功能|
|-|-|
|任务栏|左角落(300px): 增加\减少屏幕亮度(这里使用的是dell外接显示器处理程序)<br>右角落(300px): 增加\减少音量<br>中间: 切换虚拟桌面|
|chrome浏览器|标题栏: 切换标签<br>右边缘滚动条处: 页面上下翻页|
|SciTE编辑器|标题栏: 切换标签<br>右边缘滚动条处: 页面上下翻页|
|npp编辑器|标题栏: 切换标签|
|ideaIDE|标题栏: 切换标签<br>右边缘滚动条处: 页面上下翻页|
|VSCode编辑器|标题栏: 切换标签|
|网易云音乐|音乐控制区域: 上一曲\下一曲|



### 备注
1. 窗口标题栏的尺寸信息时通过WinSpy获取
2. 使用快捷键切换虚拟桌面会有动画效果, 如果要消除动画效果, 查看"C:\path\AHK\ahkLearn\wait\win-10-virtual-desktop-enhancer-bjc\a.ahk"


### TODO
1. 在任务栏中间: 切换桌面==>切换窗口    因为切换桌面操作比较少用
2. 随着功能变更，以后可能会将其名称修改为contextMouse
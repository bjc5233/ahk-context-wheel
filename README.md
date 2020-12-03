# ahk-context-wheel
> 效率工具，使用鼠标滚轮执行窗口切换、窗口标签切换、页面翻页、文件选择、窗口缩放动作


### 说明
1. 鼠标滚轮：在已配置窗口标题栏\滚动条处，执行左右切换标签\上下翻页等动作
2. Win+鼠标滚轮：执行窗口切换操作
3. Ctrl+Shift+鼠标滚轮：执行窗口缩放操作


### 演示
|chrome|explorer|
|-|-|
|<img src="https://github.com/bjc5233/ahk-context-wheel/raw/master/resources/demo.gif"/>|<img src="https://github.com/bjc5233/ahk-context-wheel/raw/master/resources/demo2.gif"/>|







### 功能说明
|窗口|位置与功能|
|-|-|
|任务栏|左角落(300px): 增加\减少屏幕亮度(这里是dell外接显示器处理程序)<br>右角落(300px): 增加\减少音量<br>中间: 切换虚拟桌面|
|资源管理器|标题栏: 上下垂直选择文件<br>标题栏+鼠标右键: 左右水平选择文件|
|chrome浏览器|标题栏: 切换标签<br>右边缘滚动条处: 页面上下翻页<br>下边缘滚动条处: 页面左右移动|
|SciTE编辑器|标题栏: 切换标签<br>右边缘滚动条处: 页面上下翻页|
|npp编辑器|标题栏: 切换标签|
|idea编辑器(IDE)|标题栏: 切换标签<br>右边缘滚动条处: 页面上下翻页|
|VSCode编辑器|标题栏: 切换标签|
|cmd|TODO等待完善|
|网易云音乐|音乐控制区域: 上一曲\下一曲|
|AHKScriptManager|全部区域: 上下选择脚本|
|OneNote|右边缘滚动条处: 页面上下翻页|
|Word|右边缘滚动条处: 页面上下翻页|



### 备注
1. 窗口标题栏的尺寸信息时通过WinSpy获取
2. 使用快捷键切换虚拟桌面会有动画效果, 如果要消除动画效果, 查看"C:\path\AHK\ahkLearn\wait\win-10-virtual-desktop-enhancer-bjc\a.ahk"


### TODO
1. 在任务栏中间: 切换桌面==>切换窗口    因为切换桌面操作比较少用
2. 随着功能变更，以后可能会将其名称修改为contextMouse
3. 不同分辨率下窗口的标题大小不同，需要验证下
4. 出现一次重启后，鼠标滚轮下失灵情况
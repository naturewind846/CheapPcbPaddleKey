# 经济适用型PCB自动键

这是用PCB和标准螺丝、螺杆、磁铁拼凑成的简易双桨电键，成本很低（只需要17元）

**为了方便大家修改，提供了立创eda专业版工程文件而不是Gerber，大家可以根据自己需求自行修改diy。

![image](/pictures/mianpic.jpg)
可以通过旋转桨键两侧的限位螺杆来改变行程。

目前发现的问题：

1.后侧两个磁铁可能与di dah焊盘碰上短路。

2.桨上螺丝和中间GND的螺丝穿过通孔时有小概率不和通孔的焊盘接触导电。

3.pcb板阻焊层可能被螺丝刮断从而短路。

2024-09-19更新：

1.更新了PCB与配方，希望能彻底解决短路问题。

2024-09-09更新：

1.修复了后侧支撑螺杆可能与di dah网络连接的错误；

2.删除了上面板没什么用的GND过孔；

3.把关键连电的焊盘调大，防止可能的螺丝与焊盘接触不良。

## 零件清单

|名称|个数|购买网址|
|:---|:---|:---|
|PCB板|1个|立创打样|
|1.5x4x2 法兰轴承|4个|https://detail.tmall.com/item.htm?id=737069498990&spm=a1z09.2.0.0.1ccc2e8dr7a8AF&_u=v3p7pmal71ca|
|C12 M3磁铁底座|3个|https://item.taobao.com/item.htm?spm=a1z09.2.0.0.1ccc2e8dr7a8AF&id=782371769988&_u=v3p7pmal3057|
|直径8厚度5孔3mm铷磁铁|2个|https://item.taobao.com/item.htm?spm=a1z09.2.0.0.1ccc2e8dr7a8AF&id=649750625831&_u=v3p7pmal5ead|
|M3x10 304不锈钢平头螺丝|2个|https://detail.tmall.com/item.htm?id=676763505793&spm=a1z09.2.0.0.1ccc2e8dr7a8AF&_u=v3p7pmal018a|
|M3x12 六角双通螺柱|5个|https://detail.tmall.com/item.htm?id=622436679073&spm=a1z09.2.0.0.1ccc2e8dr7a8AF&_u=v3p7pmalb905|
|M3x6 304不锈钢圆头带垫螺丝|9个|https://detail.tmall.com/item.htm?id=524314468365&spm=a1z09.2.0.0.1ccc2e8dr7a8AF&_u=v3p7pmal9d59|
|M3螺母|4个||
|*可选 M3簧片*|3个|备注：用于将磁铁底座垫高，可以购买M3螺丝垫片簧片组合|
|PJ322 3.5mm母座|1个|https://item.taobao.com/item.htm?spm=a1z09.2.0.0.1ccc2e8dr7a8AF&id=537955324331&_u=v3p7pmal55c0|


## 制作过程
PCB包含在立创eda工程文件中，可以免费打样。打样后pcb板按照下图红线剪开，桨的两小臂要用锉刀**打磨**后塞进轴承里

<div align=center><img src="/pictures/pcbpic.jpg" /></div>

注意小臂上的小凸起，锉刀打磨不应该超过这个边缘

<div align=center><img src="/pictures/detail.jpg" /></div>

成品前后视角

<div align=center><img src="/pictures/fwdpic.jpg" /><img src="/pictures/backpic.jpg" /></div>

制作需要使用0.5mm的漆包线或者导线在下图所示地方焊接，两边都要焊接连接上。导线最好像弹簧那样弯曲一两圈后再焊接，避免导线对桨键回弹的影响

<div align=center><img src="/pictures/weldpic.jpg" /></div>

注：图示中两个桨键的限位螺杆为了利用剩余零件，没有使用双通螺柱，效果一致。

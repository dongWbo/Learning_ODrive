# Learning_DengFOC
我打算为智能车大赛设计一款FOC无刷驱动软件，用于驱动平衡单车的动量轮。在此进行ODrive源码的学习。
<br/>

我的方案：
+ 编码器：as5047P ([官网在此不多解释](https://ams.com/zh/as5047p))
+ 电机： 预计400-900kv的航模电机  (还在测试当中)
+ 电流采样： 双电阻采样 (ODrive是双电阻采样方案copy，copy)
+ 控制方式： 速度闭环  (使用ODrive驱动无刷电机进行过倒立摆测试，效果最好。具体体现为：速度闭环的起摆角最大，抗干扰能力最好)

我将基于以上方案，对ODrive固件中的电机控制部分添加中文注释，便于自己的学习和日后的复盘总结。

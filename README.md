基于[https://github.com/Skythinker616/foc-wheel-legged-robot/] 在原有开源项目的基础上重写大部分主控制代码。主要改变如下：

1. 将机器人平衡控制换为PID控制。
2. 腿部关节控制方式为无刷电机位置控制方式。
3. 无刷电机使用4个瓴控ME4010和2个2805电机，模型经过改变以适应新电机。
4. 改进主控制板，增加多个电机接口和开关。

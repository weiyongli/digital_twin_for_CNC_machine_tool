# digital twin for CNC machine tool
This ia a research project for CNC machine tool.

google 最新发布的tensorflow 2.0 支持强化学习的agent，用来构建digital twin 决策模型与参数优化模型。

其实也可以通过构建完DT后，提前将各种可能发生的故障仿真一遍，然后建立设备的故障模式库，之后设备发生对应的情况后进行设备
模式和故障的搜索匹配。
这种思路和基于强化学习与仿真的迁移学习的设备运行优化决策是一样的。
其实设备的正常优化和故障都是设备的状态的某时刻特例。都可以通过DT仿真来得到，这也是DT的优势所在。
提前将可能发生的好的或者坏的仿真出来，之后迁移到设备上即可。

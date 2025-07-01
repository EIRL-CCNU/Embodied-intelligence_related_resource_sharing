# Isaac Lab安装(基于isaac sim 4.5)
中文教程：[https://docs.robotsfan.com/isaaclab/index.html](https://docs.robotsfan.com/isaaclab/index.html)

快速本地安装：[https://docs.robotsfan.com/isaaclab/source/setup/installation/binaries_installation.html](https://docs.robotsfan.com/isaaclab/source/setup/installation/binaries_installation.html)



安装中出现问题解决办法：

[https://zhuanlan.zhihu.com/p/716946951](https://zhuanlan.zhihu.com/p/716946951)

[https://zhuanlan.zhihu.com/p/29939886037](https://zhuanlan.zhihu.com/p/29939886037)

[https://zhuanlan.zhihu.com/p/27174960684](https://zhuanlan.zhihu.com/p/27174960684)



Isaac Lab 系列教程：

[https://www.zhihu.com/column/c_1796226143680069633](https://www.zhihu.com/column/c_1796226143680069633)

[**https://blog.csdn.net/weixin_43013761?type=lately**](https://blog.csdn.net/weixin_43013761?type=lately)

[https://www.zhihu.com/people/deng-kan-55/posts](https://www.zhihu.com/people/deng-kan-55/posts)



训练人形参考：

[https://blog.csdn.net/ModestCoder_/article/details/146885836](https://blog.csdn.net/ModestCoder_/article/details/146885836)



issac sim 本地资产（模型库）配置：

[https://docs.isaacsim.omniverse.nvidia.com/latest/installation/install_faq.html#](https://docs.isaacsim.omniverse.nvidia.com/latest/installation/install_faq.html#)

[https://blog.csdn.net/qq_45906972/article/details/146095565](https://blog.csdn.net/qq_45906972/article/details/146095565)



**<font style="color:rgb(5, 7, 59);background-color:rgb(244, 246, 252);">宇树资源：</font>**

**usdf描述文件：**[**https://github.com/unitreerobotics/unitree_ros/tree/master/robots/g1_description**](https://github.com/unitreerobotics/unitree_ros/tree/master/robots/g1_description)

[**https://www.unitree.com/cn/opensource**](https://www.unitree.com/cn/opensource)

[**https://github.com/unitreerobotics/unitree_rl_gym/blob/main/README_zh.md**](https://github.com/unitreerobotics/unitree_rl_gym/blob/main/README_zh.md)



> **搭建个人isaaclab脚手架（独立于isaaclab），**
>

+ **参考文章：**

[**https://blog.csdn.net/weixin_43013761/article/details/144952004?spm=1001.2014.3001.5501**](https://blog.csdn.net/weixin_43013761/article/details/144952004?spm=1001.2014.3001.5501)

[**https://blog.csdn.net/weixin_43013761/article/details/144986505?spm=1001.2014.3001.5501**](https://blog.csdn.net/weixin_43013761/article/details/144986505?spm=1001.2014.3001.5501)

[https://blog.csdn.net/weixin_43013761/article/details/144300473?spm=1001.2014.3001.5501](https://blog.csdn.net/weixin_43013761/article/details/144300473?spm=1001.2014.3001.5501)

[https://blog.csdn.net/weixin_43013761/article/details/144641464?spm=1001.2014.3001.5501](https://blog.csdn.net/weixin_43013761/article/details/144641464?spm=1001.2014.3001.5501)

[https://blog.csdn.net/weixin_43013761/article/details/146261043?spm=1001.2014.3001.5501](https://blog.csdn.net/weixin_43013761/article/details/146261043?spm=1001.2014.3001.5501)

[https://blog.csdn.net/weixin_43013761/article/details/146326298?spm=1001.2014.3001.5501](https://blog.csdn.net/weixin_43013761/article/details/146326298?spm=1001.2014.3001.5501)

****

> **参考isaaclab项目模板：**
>

[**https://github.com/NathanWu7/isaacLab.manipulation**](https://github.com/NathanWu7/isaacLab.manipulation)

[**https://github.com/fan-ziqi/robot_lab**](https://github.com/fan-ziqi/robot_lab)

[**https://github.com/isaac-sim/IsaacLabExtensionTemplate/tree/main**](https://github.com/isaac-sim/IsaacLabExtensionTemplate/tree/main)

****

****

> **训练宇树人形机器人G1项目模板（独立于isaaclab 可自定义机器人、设置mdp过程）：**
>

[**https://github.com/yangyixiang-cc/IsaacLab_RL_unitree_g1_template**](https://github.com/yangyixiang-cc/IsaacLab_RL_unitree_g1_template)

**下载后进行配置环境后，注意在issaclab环境中（conda），执行训练：**

```bash
python scripts/rsl_rl/train.py --task=Template-Isaac-Velocity-Rough-Unitree-G1-v0
```



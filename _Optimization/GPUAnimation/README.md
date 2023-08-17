# GPU驱动动画系统
![](_res/gpu%E5%8A%A8%E7%94%BB.gif)
介绍：
Animator动画是在CPU上计算骨骼，unity的GPU蒙皮有硬件限制需要Transform feekback效率不好在低端机下跑不起来，这套方案将骨骼计算和转移到GPU。
实现一个批次渲染几百个动画单位。集成了：动画剔除，gpu instance的支持。
使用场景：大量动画的小怪或随从
![Alt text](_res/1.png)


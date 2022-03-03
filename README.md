# Graduation-Project
清华大学毕业设计进行中
# 项目简介 Read Me
本项目旨在开发自动化神经元形态（neural morphology）指标的检测算法。
## I. 导语 Introduction
这部分作者主要介绍该项目相关的生物学研究进展和大致的需要的知识。
### 常见神经元和胶质细胞的形态学指标

在神经科学研究当中，对神经元轴突（axons）、树突（dendrites）以及小胶质细胞（microglia）进行追踪是必不可少的一环。而神经元本身不规则且发散的细胞形态，使得手动追踪十分繁杂。

### 神经元形态学分析常见方法

#### 简易神经元跟踪（Simple Neurite Tracer，SNT)


图像J（ImageJ）中有一款专门为神经元追踪（neural tracing）而设计的插件——Simple Neurite Tracer（SNT），可以满足2D、3D神经元图片的追踪、可视化和重构[1]。Simple Neurite Tracer是开源软件，在2011年爱丁堡大学的计算神经生物学系（Institute for Adaptive and Neural Computation, School of Informatics, The University of Edinburgh）阿姆斯特朗教授（J. Douglas Armstrong）团队发表文章之前，已获得 GNU 通用公共许可证 （GPL）认可。

神经元具有胞体，树突和轴突，穿过树突与轴突中线，描绘出神经元分支形态的技术过程被叫做追踪（tracing）。这种方法可以简化三维数据，有效辅助神经元形态学数据的统计和分类。这个过程如果没有自动化工具辅助，就像学龄前儿童做的简笔画描红一样繁琐且费时。

## 参考文献 References

1. Longair M H , Baker D A , Armstrong J D . Simple Neurite Tracer: open source software for reconstruction, visualization and analysis of neuronal processes[J]. Bioinformatics, 2011, 27(17):2453-2454.
2. 

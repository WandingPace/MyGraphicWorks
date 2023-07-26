# 简介 
  使用DrawMeshInstanced + MaterialPropertyBlock兼顾兼容性和性能的GPUInstance方案，硬件支持的话可以使用DrawMeshInstancedIndirect + ComputeBuffer

![](GPUInstanceCullingbyJob.gif)
# 介绍：
    FrustumJob执行视锥剔除
    
![](GPUInstaceDynamic&ECS.gif)
# 介绍：
    基于ECS动态物件的GPUInstancing

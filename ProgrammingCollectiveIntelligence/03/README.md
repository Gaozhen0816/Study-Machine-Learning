# 聚类

* 层次化聚类
  1. 构建节点类
  2. 计算当前所有节点距离
  3. 将距离最近的两个节点合成一个子节点
  4. 从所有叶节点开始递归聚类至只剩一个节点
  
 * k-means
   1. 随机生成k个中心
   2. 把所有点归类到距离最近的中心
   3. 更新中心
   4. 重复至所有点的归属无变化
  
 * 多维缩放(Multidimensional Scaling)
   1. 计算真实距离矩阵
   2. 随机生成坐标
   3. 计算坐标距离矩阵
   4. 计算误差矩阵及总误差
   5. 根据误差矩阵计算坐标移动比例
   6. 按移动速度和移动比例更新坐标
   7. 重复至当前总误差大于上次总误差
    
 *  tamimoto距离

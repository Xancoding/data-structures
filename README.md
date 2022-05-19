# learn data structures
## 查找
- 基本概念
***
- 二叉搜索树
    - 初始化
    - 查找
    - 插入
    - 删除
***
- 二叉平衡树
    - 构造
    - 插入
***
## 排序
- 插入排序
- 选择排序
- 冒泡排序
- 快速排序
- 归并排序
- 希尔排序
- 堆排序
- 桶排序
- 基数排序
- 计数排序
***

## 图
- 存储
    - 邻接矩阵 **稠密图**
    - 邻接表 **稀疏图**
- 创建
- 显示
- 遍历
    - DFS
        - 求所有包含**无向图**中所有顶点的**简单路径**(Hamilton)
        - 判断**有向图**中是否有环
        - 求一条**无向图**的顶点v到顶点w的**简单路径**
    - BFS
        - 求**无向图**的顶点v到顶点w的**最短路径**
***
- 算法
    - **最短路** **有向网**
        - **朴素版Dijkstra**
            - 某个源点到其余各点的最短路
            - 适用于**稠密图**
            - O(n^2)
        - **Floyd**
            - 每一对顶点之间的最短路
            - 适用于**稠密图**
            - O(n^3)
    - **最小生成树** **无向网**
        - **Prim**
            - 适用于**稠密图**
            - O(n^2 + m)
        - **Kruskal**
            - 适用于**稀疏图**
            - O(mlogm)  
    - **AOE网络关键路径**
    - **AOV网络拓扑序列**          


***
## 二叉树和树
### 二叉树
- 二叉树的性质
***
- 二叉树的结点
- 二叉树的创建
    - 递归创建
    - 用边创建
- 二叉树的销毁
- 二叉树的显示(凹入表)
- 查找
- 删除
- 插入
***
- 二叉树的遍历
    - 深度优先遍历
        - 先序 中序 后序 **递归**
        - 先序 中序 后序 **迭代**
    - 广度优先遍历
*** 
- 应用
    - 求深度
    - 求结点个数
    - 求叶结点个数
    - 由先序序列和中序序列确定二叉树
    - 由后序序列和中序序列确定二叉树
***
### 树
- 树的存储
    - 双亲表示法
    - 孩子表示法
    - 孩子双亲表示法
***
- 树的结点（采用**孩子兄弟链表**存储）
- 树的创建
    - 递归创建
    - 用边创建
- 树的销毁
- 树的显示(凹入表)
- 查找
- 删除
- 插入
***
- 树的遍历
    - 深度优先遍历
        - 先序 中序 后序 **递归**
    - 广度优先遍历
***
- 应用
    - 求树的深度
    - 输出指定结点的子结点
    - 求根结点到指定结点的路径
    - 求所有叶子结点路径
***    
## 链表
### 单链表
- 数据类型定义
- 初始化
- 插入
- 删除
- 查找
- 遍历
***
### 栈
#### 顺序栈
#### 链栈
- 数据类型定义
- 初始化
- 判空
- 入栈
- 出栈
- 遍历栈
- 取栈顶
***
### 队列
#### 循环队列
- 数据类型定义
- 初始化
- 判空
- 入队
- 出队
- 取队头
#### 链队列
- 数据类型定义
- 初始化
- 判空
- 入队
- 出队
- 遍历队列
- 取队头
***



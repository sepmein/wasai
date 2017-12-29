# Tensorflow TUTORIAL

## BASICS

### key difference
Tensorflow is symbolic.
与一般计算方法直接计算结果不同，构建tf程序的基本思路是先构建计算流程，然后通过运行计算流程来获得计算结果。
所以Tensorflow中最为核心的概念就是“图”（Graph)。

### 什么是Graph
Graph很抽象，又很简单，先看一个例子：
```
c = a + b
```
用Graph的概念来解释这个式子，即：如果要知道c，那么我要知道a是什么、b是什么，并且要知道如何通过a和b计算c（这里是加法）

Graph即为计算关系的集合。

与NumPy等框架直接输入数字计算结果不同，构建Tensorflow框架时，首先构建的是Graph，即首先告诉Tensorflow，定义的变量是什么，他们之间的关系是什么。

**先定义图，再运行图**

与其他框架直接计算获得结果不同，Tensorflow的逻辑是把计算过程分解为两步，定义完并不直接运行。Tensorflow更像是搭建一个程序，再运行这个程序。

### Why is that？

### Building Graph

### Running Graph

## Tensorflow resources
### Github repos

1. vahidk/EffectiveTensorflow
Thourough introduction, explain the mechanism from the very fundamental part.

### Books

1. Tensorflow for machine intelligence(Chinese Translation)
Bad translation.

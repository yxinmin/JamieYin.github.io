### To-do List

- [x] 已完成项目1
  - [x] 已完成事项1
  - [x] 已完成事项2
- [ ] 待办事项1
- [ ] 待办事项2

#### 流程图
######  自上而下

```
graph TB
J-->D
```

###### 自下而上
```
graph BT
D-->C
```

###### 从左至右
```
graph LR
C-->D
```
#### 流程图
```
graph TD
  A[Christmas]-->B(Go SHOPPING)
  B -->C{LET ME THINK}
  C-->|ONE|D[LAPTOP]
  C-->|TWO|E[IPHONE]
  C-->|THREE|F[CAR]
  ```
 ```
 graph LR
    A[A]---B[B]
```
```
 graph LR
 A(A)-->|插入文本|B[B]
 ```
 
```
gantt
dateFormat YYYY-MM-DD
title 产品计划表
section 初期阶段
明确需求: 2016-03-01, 10d
section 中期阶段
跟进开发: 2016-03-11, 15d
section 后期阶段
走查测试: 2016-03-20,  9d
```

header 1 | header 2
---|---
row 1 col 1 | row 1 col 2

```
从中学习一些图标绘制，甘特图、流程图等图形。

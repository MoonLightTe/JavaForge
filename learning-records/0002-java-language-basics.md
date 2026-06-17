---
title: Java 语言基础快速入门
date: 2026-06-16
lesson: 0002
status: in-progress
---

# 学习记录：Java 语言基础快速入门

## 学习目标
- 掌握 Java 基础语法（对比 JavaScript）
- 理解面向对象编程的核心概念
- 学会 Java 异常处理机制
- 能够编写简单的 Java 命令行程序

## 核心知识点

### 1. 类型系统差异
- **Java 静态类型** vs JavaScript 动态类型
- 必须声明变量类型，类型不可改变
- 基本数据类型：int, long, double, boolean, char, byte, short, float

### 2. 面向对象编程
- **类和对象**：类是模板，对象是实例
- **封装**：private 属性 + public getter/setter
- **继承**：extends 关键字，单继承
- **多态**：方法重写，同一接口不同实现
- **接口**：implements 关键字，多实现

### 3. 异常处理
- try-catch-finally 结构
- 受检异常 vs 非受检异常
- throws 声明 vs throw 抛出

### 4. 数组和字符串
- 数组：固定长度，类型一致
- String：不可变，丰富的方法
- StringBuilder：可变，高效拼接

## 关键对比

| 特性 | JavaScript | Java |
|------|-----------|------|
| 类型系统 | 动态 | 静态 |
| 类定义 | class + function | class |
| 继承 | 原型链 | extends |
| 接口 | 无（TypeScript 有） | interface |
| 异常处理 | try-catch | try-catch-finally |
| 数组 | 动态，可混合类型 | 固定长度，单一类型 |

## 待完成练习
- [ ] 类型转换练习
- [ ] Student 类编写
- [ ] 知识检查测验

## 下一步
- 完成练习和测验
- 开始第三课：Spring Boot 项目搭建

---

**学习心得**：Java 的静态类型系统一开始可能感觉繁琐，但能在编译时发现很多错误，这是 JavaScript 没有的优势。
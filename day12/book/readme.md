- instanceof 用于判断对象是否是类的实例

- 面向对象属性和方法 public 和 private
- 用闭包来构建
  + 函数内嵌函数 就会形成作用域的嵌套，形成闭包
  + 闭包内部的函数，会保存对外部函数内的变量的持久引用
  + 延长变量的生命周期
  + 可以引用定义时的上下文环境内的变量
  + 快速构建闭包(IIFE + 返回一个函数)
- 静态属性和方法， 只在类上调用
- prototype 原型链上的方法， 公有
- 闭包中函数方法 私有
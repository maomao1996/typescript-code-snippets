# 声明

- [声明](#%e5%a3%b0%e6%98%8e)
  - [定义声明](#%e5%ae%9a%e4%b9%89%e5%a3%b0%e6%98%8e)
  - [扩展声明](#%e6%89%a9%e5%b1%95%e5%a3%b0%e6%98%8e)
  - [自动生成声明文件](#%e8%87%aa%e5%8a%a8%e7%94%9f%e6%88%90%e5%a3%b0%e6%98%8e%e6%96%87%e4%bb%b6)

## 定义声明

- `declare [var let const]` 声明全局变量的类型

- `declare function` 声明全局函数的类型

- `declare class` 声明全局类

- `declare enum` 声明全局枚举类型

- `declare namespace` 声明（含有子属性的）全局对象

- `interface` 和 `type` 声明全局类型

## 扩展声明

- `declare global` 扩展全局变量

- `declare module` 扩展模块

## 自动生成声明文件

- 在 `tsconfig.json` 中，可以配置 `"declaration": true`
- 命令行添加 `--declaration` 或 `-d`

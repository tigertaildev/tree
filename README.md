# TigerTail Tree -- 通过层级结构组织资源

## 介绍

* 高性能的 tree 数据结构，在内存内运行；
* 基于 OpenAPI 的操作接口，客户端可通过这些接口完成各种操作；

TigerTail Tree 是 TigerTail 的子项目，可以配合其他 TigerTail 子项目一起工作，也可以单独使用。

## 应用场景

层级化管理可以有效实现资源的访问范围问题，例如同一系统内不同角色可访问的资源范围不同，这些`范围`普遍具有层级关系。

在不同场景中，资源的定义各不相同，TigerTail Tree 抽象一个通用的 tree 模型，帮助系统构造合适的模型。

## 持久存储

TigerTail Tree 支持持久存储，可以将内存数据结构存储到 `JSON 文件`、 `PostgresSQL 数据库`，也可以从这些存储中加载到内存。

## TigerTail 子项目

* IDP - 身份管理系统

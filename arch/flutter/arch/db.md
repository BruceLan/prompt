# 数据库框架 (Database)

用于在设备上进行本地数据持久化。

-   **drift** (原Moor): 一个强大的响应式持久化库，构建于`sqflite`之上。它让你能用纯Dart代码编写类型安全的SQL查询，并能将查询结果转化为响应式的数据流（Stream），是Flutter中关系型数据库的最佳选择。
-   **isar**: 一个为Flutter设计的极速、跨平台的NoSQL数据库。它拥有优秀的查询性能和易于使用的API，支持全文搜索和ACID事务，是现代Flutter应用中非关系型数据的有力竞争者。
-   **sqflite**: Flutter中与底层SQLite数据库交互的基础插件。它提供了执行原始SQL语句的能力，给予开发者完全的控制权，但需要手动编写SQL和处理数据转换，较为繁琐。
-   **hive**: 一个用纯Dart编写的轻量级、超快速的键值对（Key-Value）数据库。非常适合存储简单的配置数据、缓存或非结构化对象，但不支持复杂查询。

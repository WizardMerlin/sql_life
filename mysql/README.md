关系型数据库的基本知识点:
  
  1.  关系模型(实体,属性,关系)
  2.  范式
  3.  基本的SQL操作(crud)
  4.  多表查询,分组查询,子查询
  5.  函数
  6.  基本命令
  7.  常用的开发工具
  8.  事务
  9.  索引
  10. 视图
  11. 存储过程(5.5之后才加入的)
  12. 触发器


涉及的数据库对象如下:

  1. tables
  2. views
  3. stored procs
  4. functions
  5. triggers

 

我系统学习mysql的时候(注意不是数据库理论), 留下了一些笔记.
基本上是下图的顺序:

```
表--> 约束(执行数据校验,保证完整性) ---> 数据字典(系统表,元数据的表)
---> 视图(多个表的逻辑显示) ---> 索引 ---> 函数 ---> 存储过程
```



下面是映射关系图:

1. 基本操作(安装,开关服务,登录,书写规范,建库操作)
   补充一下数据库的基本概念,包括索引

2. 数据类型(整型,浮点型,日期类型,字符型)

3. 二维表相关的操作(建表,查看表结构/见表语句,插入数据,自增长, 5种约束)
   (包括约束参照：delete on cascade, set null, restrict)
   
4. 修改表结构(表名,列,约束,类型定义等等)

5. CRUD

6. 子查询

7. 多表连接

8. 无限级分类表

9. 多表删除

10. 常用函数(字符串函数)

11. 其他函数

12. 自定义函数

13. 存储过程

14. 存储引擎

15. 事务

16. 视图

17. 基数关系和范式

18. 字符集和校验规则

19. 语言支持  

20. mysql常见问题

(客户端其实可以通过tcp/ip协议连接到mysql)



补充内容:

* 索引

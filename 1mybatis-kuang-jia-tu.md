### 1、mybatis的整体设计图

![](/assets/mybatis-framework.png)

### 2、mybatis的几大组件

- SqlSession

    mybatis顶层的API，表示和数据库交互会话，完成CURD功能

- Executor

    mybatis的执行器
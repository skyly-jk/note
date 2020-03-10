# Redis

## redis安装

1. redis安装

   - window安装

     安装地址:https://github.com/MSOpenTech/redis/releases

   - linux安装

2. redis服务启动

    - Windows注册服务

      进入redis安装目录，输入命令

      ```
      redis-server.exe --service-install redis.windows.conf --loglevel verbose
      ```

## redis数据类型

 	在redis中，数据类型分为string，hash，list，set，sorted_set五种，这五种数据类型的操作指令和存储方式也各不相同

### string

- 存储模型

  ![](image\string类型数据的存储模型.png)

- 基础指令

  - 添加/修改数据

    ```markdown
    set <key> <value>
    ```

  - 获取数据

    ```markdown
    get <key>
    ```

  - 删除数据

    ```markdown
    del <key>
    ```

  - 添加/修改多个数据

    ```markdown
    mset <key1> <value1> <key2> <value2> ... 
    ```

  - 获取多个数据

    ```markdown
    mget <key1> <key2>
    ```

  - 获取数据字符长度

    ```markdown
    strlen <key>
    ```

  - 对原始信息进行追加（如果key不存在就进行新建）

    ```markdown
    append <key> <value>
    ```

  - 设置数据数值增加指定范围的值

    ```markdown
    incr <key>                   	key对应的值加一
    incrby <key> <increment>     	key对应的值增加increment，increment必须为整数
    increbyfloat <key> <increment> 	key对应的值增加increment，increment可以为小数
    ```

  - 

### hash

### list

### set

### sorted_set




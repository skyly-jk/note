# Redis

## redis安装与服务启动

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

        在服务中即可找到redis的服务
      
      ## 基础指令
      
      ​	redis数据主要分为string,hash,set,sorted_set几种数据类型
      
      1.string
      
      - redis对于string类型数据的存储空间
      
      - 添加/修改数据
      
        ```
        set <key> <value>
        ```
      
        
      
      2.hash
      
      
      
      3.list
      
      
      
      4.set
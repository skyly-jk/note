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
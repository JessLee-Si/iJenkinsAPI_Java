Jenkins API 调用演示程序
====

用于演示通过客户端程序调用Jenkins API，运行Jenkins任务，并获取任务运行结果。

配置方法
====
1. 运行设备上需要安装 java 环境
2. 需要将 ijenkins_config.properties 配置文件复制/粘贴到运行设备的 user.home 目录下
3. 更新 ijenkins_config.properties 内容，使之符合运行设备上的实际参数值
    - 用户名
    - 密码
    - 任务名称
    - host
    - port

运行
====
方法1.
Intellij Idea中运行ClientApi.main()

方法2.
构建jar包： mvn clean packages
运行： java -jar iJenkinsAPI.jar
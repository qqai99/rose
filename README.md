# rose
cmd：程序的入口，存放main.go文件

etc：存放配置文件，使用yaml文件作为配置文件

common：公共能力代码包，http框架、job调度、im框架，通用的工具都放在这个目录下，可以被外部引用

internal：项目私有代码，不能被其他人在其他项目导入的代码

conf：配置文件对应的结构定义，以及一些配置逻辑处理

handler：定义路由

repo：数据库操作，数据库，缓存，第三方调用等

server：服务的启动

service：业务核心逻辑
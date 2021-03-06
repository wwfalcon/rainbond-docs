---
title: 语言支持
summary: 多语言支持
toc: false
---
&emsp;&emsp;云帮提供了多种语言的快速部署服务，您提交的代码只需简单遵循该语言的提交规范就可以一键构建环境并运行，具体构建方法参见[创建应用-源码构建](/docs/stable/user-app-docs/addapp/addapp-code.html)。云帮从api接口查询当前服务的信息，获取下列信息：开发语言、运行环境、系统依赖、启动命令等，具体规范如下：

- 语言类型

  目前平台只支持**单一**语言部署，支持语言包括：Java、Php、Python、Ruby、Node.js、Golang、Static html、DockerFile。

- 运行环境

  不同语言需要指定不同的运行环境，详细请看**语言支持**对应语言介绍。

- 依赖包

  每个应用需要定义自己的依赖包，依赖包的格式与传统方式相同。

- 启动命令procfile

  帮助用户在云平台上将自己编写的程序运行起来的描述文件，我们称为procfile。
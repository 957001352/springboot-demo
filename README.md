# SpringBoot 示例项目

这是一个基础的SpringBoot项目，可以用作学习和开发的起点。

## 功能特性

- SpringBoot 2.7.5
- RESTful API 示例
- 简单的控制器实现

## 快速开始

### 前提条件

- JDK 1.8或更高版本
- Maven 3.6.3或更高版本

### 构建与运行

1. 克隆仓库

```bash
git clone https://github.com/957001352/springboot-demo.git
cd springboot-demo
```

2. 使用Maven构建项目

```bash
mvn clean package
```

3. 运行应用

```bash
java -jar target/springboot-demo-0.0.1-SNAPSHOT.jar
```

或者使用Maven运行：

```bash
mvn spring-boot:run
```

4. 访问应用

打开浏览器，访问：`http://localhost:8080/hello`

也可以传入name参数：`http://localhost:8080/hello?name=张三`

## 项目结构

```
src
├── main
│   ├── java
│   │   └── com
│   │       └── example
│   │           └── springbootdemo
│   │               ├── SpringbootDemoApplication.java  # 主应用类
│   │               └── controller
│   │                   └── HelloController.java        # 示例控制器
│   └── resources
│       └── application.properties  # 应用配置文件
```

## 许可证

MIT
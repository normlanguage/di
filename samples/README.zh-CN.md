# 依赖注入示例

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) 定义两个单例服务，将其中一个注入另一个，通过 `Container` 取得组装好的服务，并关闭容器。示例通过自己的 `Module module()` 声明依赖，是独立的模块消费者。

在仓库根目录运行：

```sh
norm run samples/hello.norm
```

预期程序输出：`Hello from DI`。

# di

[English](README.md) | [简体中文](README.zh-CN.md)

模块身份和依赖见 [module.norm](di/module.norm)，发布使用的工具链见[工作流](.github/workflows/package.yml)。

构建：`norm package di --output build/repository`。

测试：`norm test di`。

[示例](samples/README.zh-CN.md)展示独立模块中的单例注入与容器生命周期。

# Dependency injection samples

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) defines two singleton services, injects one into the other, obtains the assembled service from `Container`, and closes the container. It is a standalone consumer with its own `Module module()` dependency.

From the repository root, run:

```sh
norm run samples/hello.norm
```

Expected program output: `Hello from DI`. Micronaut may also print an SLF4J no-provider warning to stderr.

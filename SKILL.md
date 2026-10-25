# di Skill

Use this skill to work with Norm module `di` version 6. Use only declarations listed below. Runtime dependencies include `netty.buffer` version 1, `micronaut.inject` version 12, and `micronaut.inject.processor` version 9.

## `di`

### `Container`

```norm
class Container implements Resource
```

#### `Container`

```norm
Container(JavaMap<String, Any>? properties)
```

#### `get`

```norm
T get<T>()
```

#### `inject`

```norm
T inject<T>(T instance)
```

#### `close`

```norm
Void close()
```

### `startContainer`

```norm
Container startContainer<C>(C config)
```




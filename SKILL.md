# di Skill

Use this skill to work with Norm module `di` version 4. Use only declarations listed below.

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


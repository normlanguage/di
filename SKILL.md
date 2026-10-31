# di Skill

Use this skill to work with Norm module `di` version 11. Use only declarations listed below.

## `di`

Source: `container.norm`

### `Container`

```norm
class Container implements Resource
```

#### `Container`

```norm
Container(JavaMap<String, Any>? properties)
```

Parameters:

- `properties`: `JavaMap<String, Any>?`

#### `get`

```norm
T get<T>()
```

Type parameters:

- `T`

Returns: `T`

#### `inject`

```norm
T inject<T>(T instance)
```

Type parameters:

- `T`

Parameters:

- `instance`: `T`

Returns: `T`

#### `close`

```norm
Void close()
```

Returns: `Void`

### `startContainer`

```norm
Container startContainer<C>(C config)
```

Type parameters:

- `C`

Parameters:

- `config`: `C`

Returns: `Container`


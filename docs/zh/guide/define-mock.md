# defineMock(mockConfig)

mock配置 类型帮助函数

## 使用

```ts [*.mock.ts]
import { defineMock } from 'vite-plugin-mock-dev-server'

export default defineMock({
  url: '/api/test',
  body: {}
})
```

或者传入数组：

```ts [*.mock.ts]
import { defineMock } from 'vite-plugin-mock-dev-server'

export default defineMock([
  {
    url: '/api/test',
    body: {},
  },
  {
    url: '/api/test2',
    body: {}
  }
])
```

## `mockConfig`

`type: MockOptionsItem | MockOptionsItem[]`

查看 [mock-config](/guide/mock-config)

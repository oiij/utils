# @oiij/utils

Features:

- Bundle with [tsup](https://github.com/egoist/tsup)
- Test with [vitest](https://vitest.dev)

# Usage

## Install

```bash
pnpm add @oiij/utils
```

## Use

```ts
import { isFunction } from '@oiij/utils/is'
isFunction(1) // false
isFunction(() => {}) // true
```

# License

MIT

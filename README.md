# deno package.json issue repro

Steps:

```
deno run hello.js
```

- Expected: just prints “hello” to stdout
- Actual: dumps the dependencies from deno.lock to node_modules.

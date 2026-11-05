# hello

The example application of the Nexus **staging** index
(<https://index-staging.nx-lang.org/>): a greeting, published by pull request,
signed, and installed with `nxapp`.

```sh
nxapp run hello --index https://index-staging.nx-lang.org/ -- Ada     # Hello, Ada!
nxapp install hello --index https://index-staging.nx-lang.org/
HELLO_NAME=Ada hello
```

`HELLO_NAME` (default `world`) says whom to greet; the first argument wins over it.

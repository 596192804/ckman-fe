# ckman

## Project setup

```yarn
yarn install
```

### Compiles and hot-reloads for development

```yarn
yarn run serve
```

### Compiles and minifies for production

```yarn
yarn run build
```

### 修复错误"error:0308010C:digital envelope routines::unsupported"
```
#执行以下命令

#power shell
$env:NODE_OPTIONS = "--openssl-legacy-provider"

#Unix-like (Linux, macOS, Git bash, etc.):
export NODE_OPTIONS=--openssl-legacy-provider
```
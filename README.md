# action-format

Format ArkScript code

## Inputs

```
inputs:
  folder:
    description: 'Folder with .ark files to check'
    required: true
  exclude:
    description: 'Folders to exclude, comma separated'
```

- **folder**: path to ArkScript files ; will be scanned recursively for `*.ark` files
- **exclude**: list of path to exclude, eg `foo,bar,egg/test`


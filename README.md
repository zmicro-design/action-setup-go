# GitHub Action to Setup Go

![https://github.com/zmicro-design/action-setup-go](https://img.shields.io/github/v/release/zmicro-design/action-setup-go)
![https://github.com/zmicro-design/action-setup-go](https://github.com/zmicro-design/action-setup-go/workflows//Publish/badge.svg)

### Usage

| option | required | description |
| ------ | -------- | ----------- |
| node-version | false | sepcify node version |

### Example

```yml
name: CI

on: [push]

jobs:
  build:
    name: Test
    runs-on: ubuntu-latest
    steps:
      - name: Setup Go
        uses: zmicro-design/action-setup-go@v1
```

### License

[MIT](./LICENSE)

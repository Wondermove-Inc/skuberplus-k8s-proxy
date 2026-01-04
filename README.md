<h1 align="center">Skuberplus K8s Proxy</h1>

<!-- markdownlint-disable MD013 -->

<p align="center">
  <a href="https://github.com/Wondermove-Inc/skuberplus-k8s-proxy/releases"><img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="Version"></a>
  <a href="https://github.com/Wondermove-Inc/skuberplus-k8s-proxy/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License"></a>
</p>

<!-- markdownlint-enable MD013 -->

More secure alternative to `kubectl proxy`.

## How to build

On Mac and Linux install tools using [mise](https://mise.jdx.dev/):

```sh
mise install
make download
make build
```

On Windows:

```powershell
winget install GoLang.Go
winget install goreleaser.goreleaser
./Makefile.ps1 download
./Makefile.ps1 build
```

## License

This repository is a fork of [lens-k8s-proxy](https://github.com/lensapp/lens-k8s-proxy/tree/main).

Copyright (c) 2025 SkuberPlus Authors.

Copyright (c) 2022 Mirantis, Inc.

[MIT License](https://opensource.org/licenses/MIT)

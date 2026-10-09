# Lumera releases

Releases of Lumera SDKs, libraries and services. Development happens in private
repositories; this repository holds releases only.

The Lumera chain and SuperNode publish in their own repositories:
[lumera](https://github.com/LumeraProtocol/lumera/releases) and
[supernode](https://github.com/LumeraProtocol/supernode/releases).

| Product | What it is | Releases |
|---|---|---|
| sdk-go | Go SDK | [sdk-go](https://github.com/LumeraProtocol/releases/releases?q=sdk-go) |
| sdk-js | JavaScript/TypeScript SDK | [sdk-js](https://github.com/LumeraProtocol/releases/releases?q=sdk-js) |
| sdk-rs | Rust SDK | [sdk-rs](https://github.com/LumeraProtocol/releases/releases?q=sdk-rs) |
| rq-go | RaptorQ Go bindings | [rq-go](https://github.com/LumeraProtocol/releases/releases?q=rq-go) |
| rq-library | RaptorQ library (native, wasm, Rust) | [rq-library](https://github.com/LumeraProtocol/releases/releases?q=rq-library) |
| sn-api-server | SuperNode API server (self-hostable) | [sn-api-server](https://github.com/LumeraProtocol/releases/releases?q=sn-api-server) |
| lumescope | LumeScope | [lumescope](https://github.com/LumeraProtocol/releases/releases?q=lumescope) |

## Install

Products without a section here have no release yet; theirs is added with the
first one.

### rq-library

- **Native libraries** (static and shared, with the C header `rq-library.h`):
  `rq-library-v<version>-<os>-<arch>.tar.gz` on the
  [rq-library releases](https://github.com/LumeraProtocol/releases/releases?q=rq-library),
  for linux amd64/arm64 and macOS arm64/amd64.
- **Browser (WASM):** `npm install rq-library-wasm`
- **Rust:** `cargo add rq-library`

### rq-go

```bash
go get lumera.build/rq-go@v0.3.0
```

From v0.3.0 the module path is `lumera.build/rq-go`; earlier versions were
`github.com/LumeraProtocol/rq-go`.

### sdk-rs

```bash
cargo add lumera-sdk-rs
```

## Releases

- Tags are `<product>-v<version>`, for example `sdk-go-v1.3.0`.
- Each release carries `<product>-v<version>-src.tar.gz` (the source) and
  `SHA256SUMS`. Verify downloads with `sha256sum -c SHA256SUMS`.
- GitHub's "Source code" archives on a release contain only this README.

## Issues

Issues are welcome: open one and pick the product. Pull requests are not
accepted here.

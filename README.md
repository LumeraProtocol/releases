# Lumera releases

Releases of Lumera SDKs, libraries and services. Development happens in private
repositories; this repository holds releases only.

The Lumera chain and SuperNode publish in their own repositories:
[lumera](https://github.com/LumeraProtocol/lumera/releases) and
[supernode](https://github.com/LumeraProtocol/supernode/releases).

| Product | What it is |
|---|---|
| sdk-go | Go SDK |
| sdk-js | JavaScript/TypeScript SDK |
| sdk-js-react | React components for sdk-js |
| sdk-rs | Rust SDK |
| rq-go | RaptorQ Go bindings |
| rq-library | RaptorQ library (native, wasm, Rust) |
| sn-api-server | SuperNode API server (self-hostable) |
| lumescope | LumeScope |

No release has been published here yet. Each product's install line is added
here with its first release.

## Releases

- Tags are `<product>-v<version>`, for example `sdk-go-v1.3.0`.
- Each release carries `<product>-v<version>-src.tar.gz` (the source) and
  `SHA256SUMS`. Verify downloads with `sha256sum -c SHA256SUMS`.
- GitHub's "Source code" archives on a release contain only this README.

## Issues

Issues are welcome: open one and pick the product. Pull requests are not
accepted here.

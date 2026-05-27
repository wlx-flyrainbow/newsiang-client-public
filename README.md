# 新祥编程客户端公开源码

This repository contains the public AGPL corresponding source for the
NewSiang / 新祥编程 desktop client.

It is generated from the internal core repository and intentionally excludes
production secrets, certificates, user data, payment proofs, operations notes,
commercial plans, and private service implementations.

## License

- License: AGPL-3.0-only
- Source disclosure: `docs/agpl-source-disclosure.md`
- Build and run: `docs/build-and-run.md`
- Release source map: `docs/release-source-map.md`

## Quick Start

```bash
npm install
npm run prepublish
npm run build
npm start
```

For desktop packaging:

```bash
npm run electron-dev
```
